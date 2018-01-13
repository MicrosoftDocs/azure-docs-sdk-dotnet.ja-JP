<Type Name="ITriggersOperations" FullName="Microsoft.Azure.Management.DataFactory.ITriggersOperations">
  <TypeSignature Language="C#" Value="public interface ITriggersOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ITriggersOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.ITriggersOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface ITriggersOperations" />
  <TypeSignature Language="F#" Value="type ITriggersOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="4d2d1-101">TriggersOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-101">TriggersOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginStartWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginStartWithHttpMessagesAsync (string resourceGroupName, string factoryName, string triggerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginStartWithHttpMessagesAsync(string resourceGroupName, string factoryName, string triggerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.ITriggersOperations.BeginStartWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginStartWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iTriggersOperations.BeginStartWithHttpMessagesAsync (resourceGroupName, factoryName, triggerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="triggerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="4d2d1-102">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-102">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="4d2d1-103">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-103">The factory name.</span></span>
            </param>
        <param name="triggerName">
            <span data-ttu-id="4d2d1-104">トリガーの名前です。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-104">The trigger name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="4d2d1-105">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-105">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4d2d1-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4d2d1-107">トリガーを起動します。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-107">Starts a trigger.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataFactory.Models.ErrorResponseException">
            <span data-ttu-id="4d2d1-108">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-108">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4d2d1-109">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-109">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginStopWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginStopWithHttpMessagesAsync (string resourceGroupName, string factoryName, string triggerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginStopWithHttpMessagesAsync(string resourceGroupName, string factoryName, string triggerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.ITriggersOperations.BeginStopWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginStopWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iTriggersOperations.BeginStopWithHttpMessagesAsync (resourceGroupName, factoryName, triggerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="triggerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="4d2d1-110">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-110">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="4d2d1-111">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-111">The factory name.</span></span>
            </param>
        <param name="triggerName">
            <span data-ttu-id="4d2d1-112">トリガーの名前です。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-112">The trigger name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="4d2d1-113">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-113">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4d2d1-114">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-114">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4d2d1-115">トリガーを停止します。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-115">Stops a trigger.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataFactory.Models.ErrorResponseException">
            <span data-ttu-id="4d2d1-116">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-116">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4d2d1-117">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-117">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string factoryName, string triggerName, Microsoft.Azure.Management.DataFactory.Models.TriggerResource trigger, string ifMatch = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string factoryName, string triggerName, class Microsoft.Azure.Management.DataFactory.Models.TriggerResource trigger, string ifMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.ITriggersOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactory.Models.TriggerResource,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.DataFactory.Models.TriggerResource * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt;&gt;" Usage="iTriggersOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, factoryName, triggerName, trigger, ifMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="triggerName" Type="System.String" />
        <Parameter Name="trigger" Type="Microsoft.Azure.Management.DataFactory.Models.TriggerResource" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="4d2d1-118">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-118">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="4d2d1-119">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-119">The factory name.</span></span>
            </param>
        <param name="triggerName">
            <span data-ttu-id="4d2d1-120">トリガーの名前です。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-120">The trigger name.</span></span>
            </param>
        <param name="trigger">
            <span data-ttu-id="4d2d1-121">リソース定義をトリガーします。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-121">Trigger resource definition.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="4d2d1-122">トリガーのエンティティの ETag です。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-122">ETag of the trigger entity.</span></span>  <span data-ttu-id="4d2d1-123">更新については、対象の既存のエンティティが一致していることもできますのみ指定する必要があります \* の無条件更新します。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-123">Should only be specified for update, for which it should match existing entity or can be \* for unconditional update.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="4d2d1-124">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-124">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4d2d1-125">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-125">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4d2d1-126">作成するか、トリガーを更新します。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-126">Creates or updates a trigger.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataFactory.Models.ErrorResponseException">
            <span data-ttu-id="4d2d1-127">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-127">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="4d2d1-128">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-128">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4d2d1-129">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-129">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string factoryName, string triggerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string factoryName, string triggerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.ITriggersOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iTriggersOperations.DeleteWithHttpMessagesAsync (resourceGroupName, factoryName, triggerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="triggerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="4d2d1-130">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-130">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="4d2d1-131">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-131">The factory name.</span></span>
            </param>
        <param name="triggerName">
            <span data-ttu-id="4d2d1-132">トリガーの名前です。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-132">The trigger name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="4d2d1-133">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-133">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4d2d1-134">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-134">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4d2d1-135">トリガーを削除します。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-135">Deletes a trigger.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataFactory.Models.ErrorResponseException">
            <span data-ttu-id="4d2d1-136">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-136">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4d2d1-137">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-137">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string factoryName, string triggerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string factoryName, string triggerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.ITriggersOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt;&gt;" Usage="iTriggersOperations.GetWithHttpMessagesAsync (resourceGroupName, factoryName, triggerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="triggerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="4d2d1-138">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-138">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="4d2d1-139">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-139">The factory name.</span></span>
            </param>
        <param name="triggerName">
            <span data-ttu-id="4d2d1-140">トリガーの名前です。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-140">The trigger name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="4d2d1-141">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-141">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4d2d1-142">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4d2d1-143">トリガーを取得します。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-143">Gets a trigger.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataFactory.Models.ErrorResponseException">
            <span data-ttu-id="4d2d1-144">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-144">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="4d2d1-145">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-145">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4d2d1-146">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-146">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByFactoryNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt;&gt;&gt; ListByFactoryNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt;&gt;&gt; ListByFactoryNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.ITriggersOperations.ListByFactoryNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByFactoryNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt;&gt;&gt;" Usage="iTriggersOperations.ListByFactoryNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="4d2d1-147">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-147">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="4d2d1-148">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-148">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4d2d1-149">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-149">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4d2d1-150">トリガーを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-150">Lists triggers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataFactory.Models.ErrorResponseException">
            <span data-ttu-id="4d2d1-151">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-151">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="4d2d1-152">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-152">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4d2d1-153">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-153">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByFactoryWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt;&gt;&gt; ListByFactoryWithHttpMessagesAsync (string resourceGroupName, string factoryName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt;&gt;&gt; ListByFactoryWithHttpMessagesAsync(string resourceGroupName, string factoryName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.ITriggersOperations.ListByFactoryWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByFactoryWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt;&gt;&gt;" Usage="iTriggersOperations.ListByFactoryWithHttpMessagesAsync (resourceGroupName, factoryName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="4d2d1-154">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-154">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="4d2d1-155">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-155">The factory name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="4d2d1-156">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-156">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4d2d1-157">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-157">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4d2d1-158">トリガーを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-158">Lists triggers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataFactory.Models.ErrorResponseException">
            <span data-ttu-id="4d2d1-159">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-159">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="4d2d1-160">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-160">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4d2d1-161">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-161">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListRunsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerRun&gt;&gt;&gt; ListRunsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.TriggerRun&gt;&gt;&gt; ListRunsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.ITriggersOperations.ListRunsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListRunsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerRun&gt;&gt;&gt;" Usage="iTriggersOperations.ListRunsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerRun&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="4d2d1-162">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-162">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="4d2d1-163">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-163">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4d2d1-164">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-164">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4d2d1-165">一覧のトリガーが実行されます。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-165">List trigger runs.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataFactory.Models.ErrorResponseException">
            <span data-ttu-id="4d2d1-166">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-166">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="4d2d1-167">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-167">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4d2d1-168">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-168">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListRunsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerRun&gt;&gt;&gt; ListRunsWithHttpMessagesAsync (string resourceGroupName, string factoryName, string triggerName, DateTime startTime, DateTime endTime, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.TriggerRun&gt;&gt;&gt; ListRunsWithHttpMessagesAsync(string resourceGroupName, string factoryName, string triggerName, valuetype System.DateTime startTime, valuetype System.DateTime endTime, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.ITriggersOperations.ListRunsWithHttpMessagesAsync(System.String,System.String,System.String,System.DateTime,System.DateTime,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListRunsWithHttpMessagesAsync : string * string * string * DateTime * DateTime * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerRun&gt;&gt;&gt;" Usage="iTriggersOperations.ListRunsWithHttpMessagesAsync (resourceGroupName, factoryName, triggerName, startTime, endTime, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerRun&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="triggerName" Type="System.String" />
        <Parameter Name="startTime" Type="System.DateTime" />
        <Parameter Name="endTime" Type="System.DateTime" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="4d2d1-169">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-169">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="4d2d1-170">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-170">The factory name.</span></span>
            </param>
        <param name="triggerName">
            <span data-ttu-id="4d2d1-171">トリガーの名前です。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-171">The trigger name.</span></span>
            </param>
        <param name="startTime">
            <span data-ttu-id="4d2d1-172">トリガーの実行の開始時刻。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-172">Start time for trigger runs.</span></span>
            </param>
        <param name="endTime">
            <span data-ttu-id="4d2d1-173">トリガーの終了時刻を実行します。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-173">End time for trigger runs.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="4d2d1-174">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-174">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4d2d1-175">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-175">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4d2d1-176">一覧のトリガーが実行されます。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-176">List trigger runs.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataFactory.Models.ErrorResponseException">
            <span data-ttu-id="4d2d1-177">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-177">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="4d2d1-178">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-178">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4d2d1-179">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-179">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="StartWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; StartWithHttpMessagesAsync (string resourceGroupName, string factoryName, string triggerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; StartWithHttpMessagesAsync(string resourceGroupName, string factoryName, string triggerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.ITriggersOperations.StartWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member StartWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iTriggersOperations.StartWithHttpMessagesAsync (resourceGroupName, factoryName, triggerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="triggerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="4d2d1-180">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-180">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="4d2d1-181">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-181">The factory name.</span></span>
            </param>
        <param name="triggerName">
            <span data-ttu-id="4d2d1-182">トリガーの名前です。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-182">The trigger name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="4d2d1-183">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-183">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4d2d1-184">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-184">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4d2d1-185">トリガーを起動します。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-185">Starts a trigger.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataFactory.Models.ErrorResponseException">
            <span data-ttu-id="4d2d1-186">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-186">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4d2d1-187">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-187">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="StopWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; StopWithHttpMessagesAsync (string resourceGroupName, string factoryName, string triggerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; StopWithHttpMessagesAsync(string resourceGroupName, string factoryName, string triggerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.ITriggersOperations.StopWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member StopWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iTriggersOperations.StopWithHttpMessagesAsync (resourceGroupName, factoryName, triggerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="triggerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="4d2d1-188">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-188">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="4d2d1-189">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-189">The factory name.</span></span>
            </param>
        <param name="triggerName">
            <span data-ttu-id="4d2d1-190">トリガーの名前です。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-190">The trigger name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="4d2d1-191">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-191">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4d2d1-192">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-192">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4d2d1-193">トリガーを停止します。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-193">Stops a trigger.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataFactory.Models.ErrorResponseException">
            <span data-ttu-id="4d2d1-194">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-194">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4d2d1-195">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4d2d1-195">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>