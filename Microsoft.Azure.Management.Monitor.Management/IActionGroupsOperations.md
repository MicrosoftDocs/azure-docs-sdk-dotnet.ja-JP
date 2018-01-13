<Type Name="IActionGroupsOperations" FullName="Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations">
  <TypeSignature Language="C#" Value="public interface IActionGroupsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IActionGroupsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IActionGroupsOperations" />
  <TypeSignature Language="F#" Value="type IActionGroupsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0265e-101">ActionGroupsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="0265e-101">ActionGroupsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string actionGroupName, Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource actionGroup, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string actionGroupName, class Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource actionGroup, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource&gt;&gt;" Usage="iActionGroupsOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, actionGroupName, actionGroup, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="actionGroupName" Type="System.String" />
        <Parameter Name="actionGroup" Type="Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="0265e-102">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="0265e-102">The name of the resource group.</span></span>
            </param>
        <param name="actionGroupName">
            <span data-ttu-id="0265e-103">アクション グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="0265e-103">The name of the action group.</span></span>
            </param>
        <param name="actionGroup">
            <span data-ttu-id="0265e-104">作成または更新に使用するアクション グループ。</span><span class="sxs-lookup"><span data-stu-id="0265e-104">The action group to create or use for the update.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="0265e-105">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="0265e-105">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0265e-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0265e-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0265e-107">新しいアクション グループを作成または既存のものを更新します。</span><span class="sxs-lookup"><span data-stu-id="0265e-107">Create a new action group or update an existing one.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Monitor.Management.Models.ErrorResponseException">
            <span data-ttu-id="0265e-108">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0265e-108">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="0265e-109">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0265e-109">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="0265e-110">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0265e-110">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string actionGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string actionGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iActionGroupsOperations.DeleteWithHttpMessagesAsync (resourceGroupName, actionGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="actionGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="0265e-111">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="0265e-111">The name of the resource group.</span></span>
            </param>
        <param name="actionGroupName">
            <span data-ttu-id="0265e-112">アクション グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="0265e-112">The name of the action group.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="0265e-113">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="0265e-113">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0265e-114">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0265e-114">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0265e-115">アクション グループを削除します。</span><span class="sxs-lookup"><span data-stu-id="0265e-115">Delete an action group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Monitor.Management.Models.ErrorResponseException">
            <span data-ttu-id="0265e-116">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0265e-116">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="0265e-117">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0265e-117">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="EnableReceiverWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; EnableReceiverWithHttpMessagesAsync (string resourceGroupName, string actionGroupName, string receiverName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; EnableReceiverWithHttpMessagesAsync(string resourceGroupName, string actionGroupName, string receiverName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations.EnableReceiverWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member EnableReceiverWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iActionGroupsOperations.EnableReceiverWithHttpMessagesAsync (resourceGroupName, actionGroupName, receiverName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="actionGroupName" Type="System.String" />
        <Parameter Name="receiverName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="0265e-118">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="0265e-118">The name of the resource group.</span></span>
            </param>
        <param name="actionGroupName">
            <span data-ttu-id="0265e-119">アクション グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="0265e-119">The name of the action group.</span></span>
            </param>
        <param name="receiverName">
            <span data-ttu-id="0265e-120">サブスクライブする受信者の名前。</span><span class="sxs-lookup"><span data-stu-id="0265e-120">The name of the receiver to resubscribe.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="0265e-121">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="0265e-121">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0265e-122">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0265e-122">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0265e-123">アクション グループ内の受信機を有効にします。</span><span class="sxs-lookup"><span data-stu-id="0265e-123">Enable a receiver in an action group.</span></span> <span data-ttu-id="0265e-124">[有効] に、無効から受信側の状態を変更します。</span><span class="sxs-lookup"><span data-stu-id="0265e-124">This changes the receiver's status from Disabled to Enabled.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Monitor.Management.Models.ErrorResponseException">
            <span data-ttu-id="0265e-125">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0265e-125">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="0265e-126">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0265e-126">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string actionGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string actionGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource&gt;&gt;" Usage="iActionGroupsOperations.GetWithHttpMessagesAsync (resourceGroupName, actionGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="actionGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="0265e-127">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="0265e-127">The name of the resource group.</span></span>
            </param>
        <param name="actionGroupName">
            <span data-ttu-id="0265e-128">アクション グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="0265e-128">The name of the action group.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="0265e-129">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="0265e-129">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0265e-130">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0265e-130">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0265e-131">アクション グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="0265e-131">Get an action group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Monitor.Management.Models.ErrorResponseException">
            <span data-ttu-id="0265e-132">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0265e-132">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="0265e-133">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0265e-133">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="0265e-134">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0265e-134">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync (string resourceGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync(string resourceGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations.ListByResourceGroupWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource&gt;&gt;&gt;" Usage="iActionGroupsOperations.ListByResourceGroupWithHttpMessagesAsync (resourceGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="0265e-135">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="0265e-135">The name of the resource group.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="0265e-136">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="0265e-136">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0265e-137">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0265e-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0265e-138">リソース グループ内のすべてのアクション グループの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="0265e-138">Get a list of all action groups in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Monitor.Management.Models.ErrorResponseException">
            <span data-ttu-id="0265e-139">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0265e-139">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="0265e-140">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0265e-140">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="0265e-141">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0265e-141">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListBySubscriptionIdWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource&gt;&gt;&gt; ListBySubscriptionIdWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource&gt;&gt;&gt; ListBySubscriptionIdWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations.ListBySubscriptionIdWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListBySubscriptionIdWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource&gt;&gt;&gt;" Usage="iActionGroupsOperations.ListBySubscriptionIdWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="0265e-142">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="0265e-142">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0265e-143">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0265e-143">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0265e-144">サブスクリプションのすべてのアクション グループの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="0265e-144">Get a list of all action groups in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Monitor.Management.Models.ErrorResponseException">
            <span data-ttu-id="0265e-145">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0265e-145">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="0265e-146">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0265e-146">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="0265e-147">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0265e-147">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>