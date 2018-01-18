<Type Name="INotificationHubsOperations" FullName="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations">
  <TypeSignature Language="C#" Value="public interface INotificationHubsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract INotificationHubsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface INotificationHubsOperations" />
  <TypeSignature Language="F#" Value="type INotificationHubsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0ced8-101">NotificationHubsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="0ced8-101">NotificationHubsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CheckAvailabilityWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult&gt;&gt; CheckAvailabilityWithHttpMessagesAsync (string resourceGroupName, string namespaceName, Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult&gt;&gt; CheckAvailabilityWithHttpMessagesAsync(string resourceGroupName, string namespaceName, class Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations.CheckAvailabilityWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CheckAvailabilityWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult&gt;&gt;" Usage="iNotificationHubsOperations.CheckAvailabilityWithHttpMessagesAsync (resourceGroupName, namespaceName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="0ced8-102">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="0ced8-102">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="0ced8-103">名前空間の名前。</span><span class="sxs-lookup"><span data-stu-id="0ced8-103">The namespace name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0ced8-104">NotificationHub 名。</span><span class="sxs-lookup"><span data-stu-id="0ced8-104">The notificationHub name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="0ced8-105">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="0ced8-105">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0ced8-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0ced8-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ced8-107">名前空間に指定された notificationHub の可用性を確認します。</span><span class="sxs-lookup"><span data-stu-id="0ced8-107">Checks the availability of the given notificationHub in a namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="0ced8-108">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0ced8-108">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="0ced8-109">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0ced8-109">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="0ced8-110">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0ced8-110">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAuthorizationRuleWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt; CreateOrUpdateAuthorizationRuleWithHttpMessagesAsync (string resourceGroupName, string namespaceName, string notificationHubName, string authorizationRuleName, Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt; CreateOrUpdateAuthorizationRuleWithHttpMessagesAsync(string resourceGroupName, string namespaceName, string notificationHubName, string authorizationRuleName, class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations.CreateOrUpdateAuthorizationRuleWithHttpMessagesAsync(System.String,System.String,System.String,System.String,Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAuthorizationRuleWithHttpMessagesAsync : string * string * string * string * Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt;" Usage="iNotificationHubsOperations.CreateOrUpdateAuthorizationRuleWithHttpMessagesAsync (resourceGroupName, namespaceName, notificationHubName, authorizationRuleName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="notificationHubName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="0ced8-111">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="0ced8-111">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="0ced8-112">名前空間の名前。</span><span class="sxs-lookup"><span data-stu-id="0ced8-112">The namespace name.</span></span>
            </param>
        <param name="notificationHubName">
            <span data-ttu-id="0ced8-113">通知ハブの名前。</span><span class="sxs-lookup"><span data-stu-id="0ced8-113">The notification hub name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="0ced8-114">承認規則の名前。</span><span class="sxs-lookup"><span data-stu-id="0ced8-114">Authorization Rule Name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0ced8-115">共有アクセス認証ルール。</span><span class="sxs-lookup"><span data-stu-id="0ced8-115">The shared access authorization rule.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="0ced8-116">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="0ced8-116">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0ced8-117">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0ced8-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ced8-118">A NotificationHub の承認規則の作成/更新</span><span class="sxs-lookup"><span data-stu-id="0ced8-118">Creates/Updates an authorization rule for a NotificationHub</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="0ced8-119">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0ced8-119">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="0ced8-120">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0ced8-120">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="0ced8-121">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0ced8-121">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string namespaceName, string notificationHubName, Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubCreateOrUpdateParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string namespaceName, string notificationHubName, class Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubCreateOrUpdateParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubCreateOrUpdateParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubCreateOrUpdateParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt;&gt;" Usage="iNotificationHubsOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, namespaceName, notificationHubName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="notificationHubName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubCreateOrUpdateParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="0ced8-122">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="0ced8-122">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="0ced8-123">名前空間の名前。</span><span class="sxs-lookup"><span data-stu-id="0ced8-123">The namespace name.</span></span>
            </param>
        <param name="notificationHubName">
            <span data-ttu-id="0ced8-124">通知ハブの名前。</span><span class="sxs-lookup"><span data-stu-id="0ced8-124">The notification hub name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0ced8-125">パラメーターは、作成/更新に NotificationHub リソースを指定します。</span><span class="sxs-lookup"><span data-stu-id="0ced8-125">Parameters supplied to the create/update a NotificationHub Resource.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="0ced8-126">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="0ced8-126">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0ced8-127">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0ced8-127">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ced8-128">名前空間に NotificationHub の作成/更新します。</span><span class="sxs-lookup"><span data-stu-id="0ced8-128">Creates/Update a NotificationHub in a namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="0ced8-129">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0ced8-129">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="0ced8-130">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0ced8-130">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="0ced8-131">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0ced8-131">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteAuthorizationRuleWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteAuthorizationRuleWithHttpMessagesAsync (string resourceGroupName, string namespaceName, string notificationHubName, string authorizationRuleName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteAuthorizationRuleWithHttpMessagesAsync(string resourceGroupName, string namespaceName, string notificationHubName, string authorizationRuleName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations.DeleteAuthorizationRuleWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAuthorizationRuleWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iNotificationHubsOperations.DeleteAuthorizationRuleWithHttpMessagesAsync (resourceGroupName, namespaceName, notificationHubName, authorizationRuleName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="notificationHubName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="0ced8-132">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="0ced8-132">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="0ced8-133">名前空間の名前。</span><span class="sxs-lookup"><span data-stu-id="0ced8-133">The namespace name.</span></span>
            </param>
        <param name="notificationHubName">
            <span data-ttu-id="0ced8-134">通知ハブの名前。</span><span class="sxs-lookup"><span data-stu-id="0ced8-134">The notification hub name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="0ced8-135">承認規則の名前。</span><span class="sxs-lookup"><span data-stu-id="0ced8-135">Authorization Rule Name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="0ced8-136">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="0ced8-136">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0ced8-137">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0ced8-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ced8-138">NotificationHub の承認規則を削除します。</span><span class="sxs-lookup"><span data-stu-id="0ced8-138">Deletes a notificationHub authorization rule</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="0ced8-139">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0ced8-139">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="0ced8-140">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0ced8-140">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string namespaceName, string notificationHubName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string namespaceName, string notificationHubName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iNotificationHubsOperations.DeleteWithHttpMessagesAsync (resourceGroupName, namespaceName, notificationHubName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="notificationHubName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="0ced8-141">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="0ced8-141">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="0ced8-142">名前空間の名前。</span><span class="sxs-lookup"><span data-stu-id="0ced8-142">The namespace name.</span></span>
            </param>
        <param name="notificationHubName">
            <span data-ttu-id="0ced8-143">通知ハブの名前。</span><span class="sxs-lookup"><span data-stu-id="0ced8-143">The notification hub name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="0ced8-144">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="0ced8-144">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0ced8-145">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0ced8-145">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ced8-146">名前空間に関連付けられた通知ハブを削除します。</span><span class="sxs-lookup"><span data-stu-id="0ced8-146">Deletes a notification hub associated with a namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="0ced8-147">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0ced8-147">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="0ced8-148">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0ced8-148">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetAuthorizationRuleWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt; GetAuthorizationRuleWithHttpMessagesAsync (string resourceGroupName, string namespaceName, string notificationHubName, string authorizationRuleName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt; GetAuthorizationRuleWithHttpMessagesAsync(string resourceGroupName, string namespaceName, string notificationHubName, string authorizationRuleName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations.GetAuthorizationRuleWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAuthorizationRuleWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt;" Usage="iNotificationHubsOperations.GetAuthorizationRuleWithHttpMessagesAsync (resourceGroupName, namespaceName, notificationHubName, authorizationRuleName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="notificationHubName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="0ced8-149">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="0ced8-149">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="0ced8-150">名前空間の名前</span><span class="sxs-lookup"><span data-stu-id="0ced8-150">The namespace name</span></span>
            </param>
        <param name="notificationHubName">
            <span data-ttu-id="0ced8-151">通知ハブの名前。</span><span class="sxs-lookup"><span data-stu-id="0ced8-151">The notification hub name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="0ced8-152">承認規則の名前。</span><span class="sxs-lookup"><span data-stu-id="0ced8-152">authorization rule name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="0ced8-153">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="0ced8-153">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0ced8-154">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0ced8-154">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ced8-155">名前では NotificationHub の承認規則を取得します。</span><span class="sxs-lookup"><span data-stu-id="0ced8-155">Gets an authorization rule for a NotificationHub by name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="0ced8-156">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0ced8-156">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="0ced8-157">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0ced8-157">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="0ced8-158">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0ced8-158">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPnsCredentialsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.NotificationHubs.Models.PnsCredentialsResource&gt;&gt; GetPnsCredentialsWithHttpMessagesAsync (string resourceGroupName, string namespaceName, string notificationHubName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.PnsCredentialsResource&gt;&gt; GetPnsCredentialsWithHttpMessagesAsync(string resourceGroupName, string namespaceName, string notificationHubName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations.GetPnsCredentialsWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetPnsCredentialsWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.NotificationHubs.Models.PnsCredentialsResource&gt;&gt;" Usage="iNotificationHubsOperations.GetPnsCredentialsWithHttpMessagesAsync (resourceGroupName, namespaceName, notificationHubName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.NotificationHubs.Models.PnsCredentialsResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="notificationHubName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="0ced8-159">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="0ced8-159">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="0ced8-160">名前空間の名前。</span><span class="sxs-lookup"><span data-stu-id="0ced8-160">The namespace name.</span></span>
            </param>
        <param name="notificationHubName">
            <span data-ttu-id="0ced8-161">通知ハブの名前。</span><span class="sxs-lookup"><span data-stu-id="0ced8-161">The notification hub name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="0ced8-162">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="0ced8-162">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0ced8-163">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0ced8-163">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ced8-164">通知ハブに関連付けられている PNS 資格情報を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="0ced8-164">Lists the PNS Credentials associated with a notification hub .</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="0ced8-165">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0ced8-165">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="0ced8-166">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0ced8-166">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="0ced8-167">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0ced8-167">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string namespaceName, string notificationHubName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string namespaceName, string notificationHubName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt;&gt;" Usage="iNotificationHubsOperations.GetWithHttpMessagesAsync (resourceGroupName, namespaceName, notificationHubName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="notificationHubName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="0ced8-168">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="0ced8-168">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="0ced8-169">名前空間の名前。</span><span class="sxs-lookup"><span data-stu-id="0ced8-169">The namespace name.</span></span>
            </param>
        <param name="notificationHubName">
            <span data-ttu-id="0ced8-170">通知ハブの名前。</span><span class="sxs-lookup"><span data-stu-id="0ced8-170">The notification hub name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="0ced8-171">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="0ced8-171">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0ced8-172">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0ced8-172">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ced8-173">名前空間に関連付けられた通知ハブを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="0ced8-173">Lists the notification hubs associated with a namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="0ced8-174">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0ced8-174">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="0ced8-175">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0ced8-175">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="0ced8-176">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0ced8-176">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRulesNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt;&gt; ListAuthorizationRulesNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt;&gt; ListAuthorizationRulesNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations.ListAuthorizationRulesNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAuthorizationRulesNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt;&gt;" Usage="iNotificationHubsOperations.ListAuthorizationRulesNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="0ced8-177">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="0ced8-177">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="0ced8-178">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="0ced8-178">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0ced8-179">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0ced8-179">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ced8-180">A NotificationHub の承認規則を取得します。</span><span class="sxs-lookup"><span data-stu-id="0ced8-180">Gets the authorization rules for a NotificationHub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="0ced8-181">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0ced8-181">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="0ced8-182">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0ced8-182">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="0ced8-183">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0ced8-183">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRulesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt;&gt; ListAuthorizationRulesWithHttpMessagesAsync (string resourceGroupName, string namespaceName, string notificationHubName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt;&gt; ListAuthorizationRulesWithHttpMessagesAsync(string resourceGroupName, string namespaceName, string notificationHubName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations.ListAuthorizationRulesWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAuthorizationRulesWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt;&gt;" Usage="iNotificationHubsOperations.ListAuthorizationRulesWithHttpMessagesAsync (resourceGroupName, namespaceName, notificationHubName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="notificationHubName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="0ced8-184">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="0ced8-184">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="0ced8-185">名前空間の名前</span><span class="sxs-lookup"><span data-stu-id="0ced8-185">The namespace name</span></span>
            </param>
        <param name="notificationHubName">
            <span data-ttu-id="0ced8-186">通知ハブの名前。</span><span class="sxs-lookup"><span data-stu-id="0ced8-186">The notification hub name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="0ced8-187">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="0ced8-187">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0ced8-188">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0ced8-188">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ced8-189">A NotificationHub の承認規則を取得します。</span><span class="sxs-lookup"><span data-stu-id="0ced8-189">Gets the authorization rules for a NotificationHub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="0ced8-190">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0ced8-190">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="0ced8-191">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0ced8-191">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="0ced8-192">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0ced8-192">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListKeysWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys&gt;&gt; ListKeysWithHttpMessagesAsync (string resourceGroupName, string namespaceName, string notificationHubName, string authorizationRuleName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys&gt;&gt; ListKeysWithHttpMessagesAsync(string resourceGroupName, string namespaceName, string notificationHubName, string authorizationRuleName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations.ListKeysWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListKeysWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys&gt;&gt;" Usage="iNotificationHubsOperations.ListKeysWithHttpMessagesAsync (resourceGroupName, namespaceName, notificationHubName, authorizationRuleName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="notificationHubName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="0ced8-193">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="0ced8-193">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="0ced8-194">名前空間の名前。</span><span class="sxs-lookup"><span data-stu-id="0ced8-194">The namespace name.</span></span>
            </param>
        <param name="notificationHubName">
            <span data-ttu-id="0ced8-195">通知ハブの名前。</span><span class="sxs-lookup"><span data-stu-id="0ced8-195">The notification hub name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="0ced8-196">指定した authorizationRule の NotificationHub の接続文字列。</span><span class="sxs-lookup"><span data-stu-id="0ced8-196">The connection string of the NotificationHub for the specified authorizationRule.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="0ced8-197">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="0ced8-197">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0ced8-198">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0ced8-198">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ced8-199">NotificationHub にプライマリとセカンダリの ConnectionStrings を取得します。</span><span class="sxs-lookup"><span data-stu-id="0ced8-199">Gets the Primary and Secondary ConnectionStrings to the NotificationHub</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="0ced8-200">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0ced8-200">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="0ced8-201">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0ced8-201">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="0ced8-202">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0ced8-202">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt;&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt;&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations.ListNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt;&gt;&gt;" Usage="iNotificationHubsOperations.ListNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="0ced8-203">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="0ced8-203">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="0ced8-204">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="0ced8-204">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0ced8-205">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0ced8-205">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ced8-206">名前空間に関連付けられた通知ハブを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="0ced8-206">Lists the notification hubs associated with a namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="0ced8-207">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0ced8-207">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="0ced8-208">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0ced8-208">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="0ced8-209">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0ced8-209">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt;&gt;&gt; ListWithHttpMessagesAsync (string resourceGroupName, string namespaceName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt;&gt;&gt; ListWithHttpMessagesAsync(string resourceGroupName, string namespaceName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations.ListWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt;&gt;&gt;" Usage="iNotificationHubsOperations.ListWithHttpMessagesAsync (resourceGroupName, namespaceName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="0ced8-210">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="0ced8-210">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="0ced8-211">名前空間の名前。</span><span class="sxs-lookup"><span data-stu-id="0ced8-211">The namespace name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="0ced8-212">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="0ced8-212">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0ced8-213">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0ced8-213">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ced8-214">名前空間に関連付けられた通知ハブを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="0ced8-214">Lists the notification hubs associated with a namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="0ced8-215">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0ced8-215">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="0ced8-216">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0ced8-216">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="0ced8-217">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0ced8-217">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeysWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys&gt;&gt; RegenerateKeysWithHttpMessagesAsync (string resourceGroupName, string namespaceName, string notificationHubName, string authorizationRuleName, Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys&gt;&gt; RegenerateKeysWithHttpMessagesAsync(string resourceGroupName, string namespaceName, string notificationHubName, string authorizationRuleName, class Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations.RegenerateKeysWithHttpMessagesAsync(System.String,System.String,System.String,System.String,Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RegenerateKeysWithHttpMessagesAsync : string * string * string * string * Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys&gt;&gt;" Usage="iNotificationHubsOperations.RegenerateKeysWithHttpMessagesAsync (resourceGroupName, namespaceName, notificationHubName, authorizationRuleName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="notificationHubName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="0ced8-218">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="0ced8-218">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="0ced8-219">名前空間の名前。</span><span class="sxs-lookup"><span data-stu-id="0ced8-219">The namespace name.</span></span>
            </param>
        <param name="notificationHubName">
            <span data-ttu-id="0ced8-220">通知ハブの名前。</span><span class="sxs-lookup"><span data-stu-id="0ced8-220">The notification hub name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="0ced8-221">指定した authorizationRule の NotificationHub の接続文字列。</span><span class="sxs-lookup"><span data-stu-id="0ced8-221">The connection string of the NotificationHub for the specified authorizationRule.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0ced8-222">NotificationHub 承認規則のキーを再生成する指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="0ced8-222">Parameters supplied to regenerate the NotificationHub Authorization Rule Key.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="0ced8-223">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="0ced8-223">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0ced8-224">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0ced8-224">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ced8-225">NotificationHub の承認規則にプライマリ/セカンダリ キーが再生成します。</span><span class="sxs-lookup"><span data-stu-id="0ced8-225">Regenerates the Primary/Secondary Keys to the NotificationHub Authorization Rule</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="0ced8-226">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0ced8-226">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="0ced8-227">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0ced8-227">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="0ced8-228">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0ced8-228">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>