<Type Name="IQueuesOperations" FullName="Microsoft.Azure.Management.ServiceBus.IQueuesOperations">
  <TypeSignature Language="C#" Value="public interface IQueuesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IQueuesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.IQueuesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IQueuesOperations" />
  <TypeSignature Language="F#" Value="type IQueuesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="23ec8-101">QueuesOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="23ec8-101">QueuesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateAuthorizationRuleWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;&gt; CreateOrUpdateAuthorizationRuleWithHttpMessagesAsync (string resourceGroupName, string namespaceName, string queueName, string authorizationRuleName, Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;&gt; CreateOrUpdateAuthorizationRuleWithHttpMessagesAsync(string resourceGroupName, string namespaceName, string queueName, string authorizationRuleName, class Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.IQueuesOperations.CreateOrUpdateAuthorizationRuleWithHttpMessagesAsync(System.String,System.String,System.String,System.String,Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAuthorizationRuleWithHttpMessagesAsync : string * string * string * string * Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;&gt;" Usage="iQueuesOperations.CreateOrUpdateAuthorizationRuleWithHttpMessagesAsync (resourceGroupName, namespaceName, queueName, authorizationRuleName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="queueName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="23ec8-102">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="23ec8-102">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="23ec8-103">名前空間の名前</span><span class="sxs-lookup"><span data-stu-id="23ec8-103">The namespace name</span></span>
            </param>
        <param name="queueName">
            <span data-ttu-id="23ec8-104">キュー名。</span><span class="sxs-lookup"><span data-stu-id="23ec8-104">The queue name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="23ec8-105">Authorizationrule 名前です。</span><span class="sxs-lookup"><span data-stu-id="23ec8-105">The authorizationrule name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="23ec8-106">共有アクセス認証ルール。</span><span class="sxs-lookup"><span data-stu-id="23ec8-106">The shared access authorization rule.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="23ec8-107">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="23ec8-107">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="23ec8-108">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="23ec8-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="23ec8-109">キューの承認規則を作成します。</span><span class="sxs-lookup"><span data-stu-id="23ec8-109">Creates an authorization rule for a queue.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.ServiceBus.Models.ErrorResponseException">
            <span data-ttu-id="23ec8-110">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="23ec8-110">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="23ec8-111">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="23ec8-111">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="23ec8-112">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="23ec8-112">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ServiceBus.Models.SBQueue&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string namespaceName, string queueName, Microsoft.Azure.Management.ServiceBus.Models.SBQueue parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.SBQueue&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string namespaceName, string queueName, class Microsoft.Azure.Management.ServiceBus.Models.SBQueue parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.IQueuesOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.ServiceBus.Models.SBQueue,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.ServiceBus.Models.SBQueue * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ServiceBus.Models.SBQueue&gt;&gt;" Usage="iQueuesOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, namespaceName, queueName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ServiceBus.Models.SBQueue&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="queueName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ServiceBus.Models.SBQueue" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="23ec8-113">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="23ec8-113">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="23ec8-114">名前空間の名前</span><span class="sxs-lookup"><span data-stu-id="23ec8-114">The namespace name</span></span>
            </param>
        <param name="queueName">
            <span data-ttu-id="23ec8-115">キュー名。</span><span class="sxs-lookup"><span data-stu-id="23ec8-115">The queue name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="23ec8-116">作成またはキュー リソースの更新に渡されるパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="23ec8-116">Parameters supplied to create or update a queue resource.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="23ec8-117">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="23ec8-117">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="23ec8-118">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="23ec8-118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="23ec8-119">作成するか、Service Bus キューを更新します。</span><span class="sxs-lookup"><span data-stu-id="23ec8-119">Creates or updates a Service Bus queue.</span></span> <span data-ttu-id="23ec8-120">この操作は、べき等です。</span><span class="sxs-lookup"><span data-stu-id="23ec8-120">This operation is idempotent.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639395.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.ServiceBus.Models.ErrorResponseException">
            <span data-ttu-id="23ec8-121">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="23ec8-121">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="23ec8-122">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="23ec8-122">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="23ec8-123">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="23ec8-123">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteAuthorizationRuleWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteAuthorizationRuleWithHttpMessagesAsync (string resourceGroupName, string namespaceName, string queueName, string authorizationRuleName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteAuthorizationRuleWithHttpMessagesAsync(string resourceGroupName, string namespaceName, string queueName, string authorizationRuleName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.IQueuesOperations.DeleteAuthorizationRuleWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAuthorizationRuleWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iQueuesOperations.DeleteAuthorizationRuleWithHttpMessagesAsync (resourceGroupName, namespaceName, queueName, authorizationRuleName, customHeaders, cancellationToken)" />
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
        <Parameter Name="queueName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="23ec8-124">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="23ec8-124">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="23ec8-125">名前空間の名前</span><span class="sxs-lookup"><span data-stu-id="23ec8-125">The namespace name</span></span>
            </param>
        <param name="queueName">
            <span data-ttu-id="23ec8-126">キュー名。</span><span class="sxs-lookup"><span data-stu-id="23ec8-126">The queue name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="23ec8-127">Authorizationrule 名前です。</span><span class="sxs-lookup"><span data-stu-id="23ec8-127">The authorizationrule name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="23ec8-128">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="23ec8-128">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="23ec8-129">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="23ec8-129">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="23ec8-130">キューの承認規則を削除します。</span><span class="sxs-lookup"><span data-stu-id="23ec8-130">Deletes a queue authorization rule.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt705609.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.ServiceBus.Models.ErrorResponseException">
            <span data-ttu-id="23ec8-131">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="23ec8-131">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="23ec8-132">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="23ec8-132">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string namespaceName, string queueName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string namespaceName, string queueName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.IQueuesOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iQueuesOperations.DeleteWithHttpMessagesAsync (resourceGroupName, namespaceName, queueName, customHeaders, cancellationToken)" />
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
        <Parameter Name="queueName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="23ec8-133">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="23ec8-133">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="23ec8-134">名前空間の名前</span><span class="sxs-lookup"><span data-stu-id="23ec8-134">The namespace name</span></span>
            </param>
        <param name="queueName">
            <span data-ttu-id="23ec8-135">キュー名。</span><span class="sxs-lookup"><span data-stu-id="23ec8-135">The queue name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="23ec8-136">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="23ec8-136">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="23ec8-137">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="23ec8-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="23ec8-138">リソース グループ内の指定した名前空間、キューを削除します。</span><span class="sxs-lookup"><span data-stu-id="23ec8-138">Deletes a queue from the specified namespace in a resource group.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639411.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.ServiceBus.Models.ErrorResponseException">
            <span data-ttu-id="23ec8-139">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="23ec8-139">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="23ec8-140">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="23ec8-140">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetAuthorizationRuleWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;&gt; GetAuthorizationRuleWithHttpMessagesAsync (string resourceGroupName, string namespaceName, string queueName, string authorizationRuleName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;&gt; GetAuthorizationRuleWithHttpMessagesAsync(string resourceGroupName, string namespaceName, string queueName, string authorizationRuleName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.IQueuesOperations.GetAuthorizationRuleWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAuthorizationRuleWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;&gt;" Usage="iQueuesOperations.GetAuthorizationRuleWithHttpMessagesAsync (resourceGroupName, namespaceName, queueName, authorizationRuleName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="queueName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="23ec8-141">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="23ec8-141">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="23ec8-142">名前空間の名前</span><span class="sxs-lookup"><span data-stu-id="23ec8-142">The namespace name</span></span>
            </param>
        <param name="queueName">
            <span data-ttu-id="23ec8-143">キュー名。</span><span class="sxs-lookup"><span data-stu-id="23ec8-143">The queue name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="23ec8-144">Authorizationrule 名前です。</span><span class="sxs-lookup"><span data-stu-id="23ec8-144">The authorizationrule name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="23ec8-145">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="23ec8-145">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="23ec8-146">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="23ec8-146">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="23ec8-147">ルールの名前で、キューの承認規則を取得します。</span><span class="sxs-lookup"><span data-stu-id="23ec8-147">Gets an authorization rule for a queue by rule name.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt705611.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.ServiceBus.Models.ErrorResponseException">
            <span data-ttu-id="23ec8-148">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="23ec8-148">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="23ec8-149">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="23ec8-149">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="23ec8-150">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="23ec8-150">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ServiceBus.Models.SBQueue&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string namespaceName, string queueName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.SBQueue&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string namespaceName, string queueName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.IQueuesOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ServiceBus.Models.SBQueue&gt;&gt;" Usage="iQueuesOperations.GetWithHttpMessagesAsync (resourceGroupName, namespaceName, queueName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ServiceBus.Models.SBQueue&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="queueName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="23ec8-151">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="23ec8-151">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="23ec8-152">名前空間の名前</span><span class="sxs-lookup"><span data-stu-id="23ec8-152">The namespace name</span></span>
            </param>
        <param name="queueName">
            <span data-ttu-id="23ec8-153">キュー名。</span><span class="sxs-lookup"><span data-stu-id="23ec8-153">The queue name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="23ec8-154">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="23ec8-154">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="23ec8-155">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="23ec8-155">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="23ec8-156">指定したキューの説明を返します。</span><span class="sxs-lookup"><span data-stu-id="23ec8-156">Returns a description for the specified queue.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639380.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.ServiceBus.Models.ErrorResponseException">
            <span data-ttu-id="23ec8-157">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="23ec8-157">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="23ec8-158">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="23ec8-158">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="23ec8-159">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="23ec8-159">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRulesNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;&gt;&gt; ListAuthorizationRulesNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;&gt;&gt; ListAuthorizationRulesNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.IQueuesOperations.ListAuthorizationRulesNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAuthorizationRulesNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;&gt;&gt;" Usage="iQueuesOperations.ListAuthorizationRulesNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="23ec8-160">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="23ec8-160">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="23ec8-161">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="23ec8-161">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="23ec8-162">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="23ec8-162">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="23ec8-163">キューのすべての承認規則を取得します。</span><span class="sxs-lookup"><span data-stu-id="23ec8-163">Gets all authorization rules for a queue.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt705607.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.ServiceBus.Models.ErrorResponseException">
            <span data-ttu-id="23ec8-164">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="23ec8-164">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="23ec8-165">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="23ec8-165">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="23ec8-166">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="23ec8-166">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRulesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;&gt;&gt; ListAuthorizationRulesWithHttpMessagesAsync (string resourceGroupName, string namespaceName, string queueName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;&gt;&gt; ListAuthorizationRulesWithHttpMessagesAsync(string resourceGroupName, string namespaceName, string queueName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.IQueuesOperations.ListAuthorizationRulesWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAuthorizationRulesWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;&gt;&gt;" Usage="iQueuesOperations.ListAuthorizationRulesWithHttpMessagesAsync (resourceGroupName, namespaceName, queueName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="queueName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="23ec8-167">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="23ec8-167">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="23ec8-168">名前空間の名前</span><span class="sxs-lookup"><span data-stu-id="23ec8-168">The namespace name</span></span>
            </param>
        <param name="queueName">
            <span data-ttu-id="23ec8-169">キュー名。</span><span class="sxs-lookup"><span data-stu-id="23ec8-169">The queue name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="23ec8-170">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="23ec8-170">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="23ec8-171">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="23ec8-171">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="23ec8-172">キューのすべての承認規則を取得します。</span><span class="sxs-lookup"><span data-stu-id="23ec8-172">Gets all authorization rules for a queue.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt705607.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.ServiceBus.Models.ErrorResponseException">
            <span data-ttu-id="23ec8-173">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="23ec8-173">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="23ec8-174">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="23ec8-174">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="23ec8-175">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="23ec8-175">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByNamespaceNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBQueue&gt;&gt;&gt; ListByNamespaceNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.SBQueue&gt;&gt;&gt; ListByNamespaceNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.IQueuesOperations.ListByNamespaceNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByNamespaceNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBQueue&gt;&gt;&gt;" Usage="iQueuesOperations.ListByNamespaceNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBQueue&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="23ec8-176">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="23ec8-176">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="23ec8-177">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="23ec8-177">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="23ec8-178">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="23ec8-178">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="23ec8-179">名前空間内のキューを取得します。</span><span class="sxs-lookup"><span data-stu-id="23ec8-179">Gets the queues within a namespace.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639415.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.ServiceBus.Models.ErrorResponseException">
            <span data-ttu-id="23ec8-180">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="23ec8-180">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="23ec8-181">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="23ec8-181">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="23ec8-182">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="23ec8-182">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByNamespaceWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBQueue&gt;&gt;&gt; ListByNamespaceWithHttpMessagesAsync (string resourceGroupName, string namespaceName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.SBQueue&gt;&gt;&gt; ListByNamespaceWithHttpMessagesAsync(string resourceGroupName, string namespaceName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.IQueuesOperations.ListByNamespaceWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByNamespaceWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBQueue&gt;&gt;&gt;" Usage="iQueuesOperations.ListByNamespaceWithHttpMessagesAsync (resourceGroupName, namespaceName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBQueue&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="23ec8-183">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="23ec8-183">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="23ec8-184">名前空間の名前</span><span class="sxs-lookup"><span data-stu-id="23ec8-184">The namespace name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="23ec8-185">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="23ec8-185">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="23ec8-186">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="23ec8-186">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="23ec8-187">名前空間内のキューを取得します。</span><span class="sxs-lookup"><span data-stu-id="23ec8-187">Gets the queues within a namespace.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639415.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.ServiceBus.Models.ErrorResponseException">
            <span data-ttu-id="23ec8-188">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="23ec8-188">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="23ec8-189">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="23ec8-189">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="23ec8-190">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="23ec8-190">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListKeysWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ServiceBus.Models.AccessKeys&gt;&gt; ListKeysWithHttpMessagesAsync (string resourceGroupName, string namespaceName, string queueName, string authorizationRuleName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.AccessKeys&gt;&gt; ListKeysWithHttpMessagesAsync(string resourceGroupName, string namespaceName, string queueName, string authorizationRuleName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.IQueuesOperations.ListKeysWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListKeysWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ServiceBus.Models.AccessKeys&gt;&gt;" Usage="iQueuesOperations.ListKeysWithHttpMessagesAsync (resourceGroupName, namespaceName, queueName, authorizationRuleName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ServiceBus.Models.AccessKeys&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="queueName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="23ec8-191">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="23ec8-191">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="23ec8-192">名前空間の名前</span><span class="sxs-lookup"><span data-stu-id="23ec8-192">The namespace name</span></span>
            </param>
        <param name="queueName">
            <span data-ttu-id="23ec8-193">キュー名。</span><span class="sxs-lookup"><span data-stu-id="23ec8-193">The queue name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="23ec8-194">Authorizationrule 名前です。</span><span class="sxs-lookup"><span data-stu-id="23ec8-194">The authorizationrule name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="23ec8-195">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="23ec8-195">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="23ec8-196">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="23ec8-196">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="23ec8-197">キューにプライマリとセカンダリの接続文字列です。</span><span class="sxs-lookup"><span data-stu-id="23ec8-197">Primary and secondary connection strings to the queue.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt705608.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.ServiceBus.Models.ErrorResponseException">
            <span data-ttu-id="23ec8-198">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="23ec8-198">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="23ec8-199">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="23ec8-199">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="23ec8-200">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="23ec8-200">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeysWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ServiceBus.Models.AccessKeys&gt;&gt; RegenerateKeysWithHttpMessagesAsync (string resourceGroupName, string namespaceName, string queueName, string authorizationRuleName, Microsoft.Azure.Management.ServiceBus.Models.RegenerateAccessKeyParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.AccessKeys&gt;&gt; RegenerateKeysWithHttpMessagesAsync(string resourceGroupName, string namespaceName, string queueName, string authorizationRuleName, class Microsoft.Azure.Management.ServiceBus.Models.RegenerateAccessKeyParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.IQueuesOperations.RegenerateKeysWithHttpMessagesAsync(System.String,System.String,System.String,System.String,Microsoft.Azure.Management.ServiceBus.Models.RegenerateAccessKeyParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RegenerateKeysWithHttpMessagesAsync : string * string * string * string * Microsoft.Azure.Management.ServiceBus.Models.RegenerateAccessKeyParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ServiceBus.Models.AccessKeys&gt;&gt;" Usage="iQueuesOperations.RegenerateKeysWithHttpMessagesAsync (resourceGroupName, namespaceName, queueName, authorizationRuleName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ServiceBus.Models.AccessKeys&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="queueName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ServiceBus.Models.RegenerateAccessKeyParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="23ec8-201">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="23ec8-201">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="23ec8-202">名前空間の名前</span><span class="sxs-lookup"><span data-stu-id="23ec8-202">The namespace name</span></span>
            </param>
        <param name="queueName">
            <span data-ttu-id="23ec8-203">キュー名。</span><span class="sxs-lookup"><span data-stu-id="23ec8-203">The queue name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="23ec8-204">Authorizationrule 名前です。</span><span class="sxs-lookup"><span data-stu-id="23ec8-204">The authorizationrule name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="23ec8-205">承認規則を再生成する指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="23ec8-205">Parameters supplied to regenerate the authorization rule.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="23ec8-206">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="23ec8-206">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="23ec8-207">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="23ec8-207">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="23ec8-208">キューへのプライマリまたはセカンダリの接続文字列を再生成します。</span><span class="sxs-lookup"><span data-stu-id="23ec8-208">Regenerates the primary or secondary connection strings to the queue.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt705606.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.ServiceBus.Models.ErrorResponseException">
            <span data-ttu-id="23ec8-209">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="23ec8-209">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="23ec8-210">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="23ec8-210">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="23ec8-211">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="23ec8-211">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>