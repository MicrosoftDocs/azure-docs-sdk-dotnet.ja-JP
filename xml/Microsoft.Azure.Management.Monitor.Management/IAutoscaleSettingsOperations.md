<Type Name="IAutoscaleSettingsOperations" FullName="Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations">
  <TypeSignature Language="C#" Value="public interface IAutoscaleSettingsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IAutoscaleSettingsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IAutoscaleSettingsOperations" />
  <TypeSignature Language="F#" Value="type IAutoscaleSettingsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="07c23-101">AutoscaleSettingsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="07c23-101">AutoscaleSettingsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string autoscaleSettingName, Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string autoscaleSettingName, class Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource&gt;&gt;" Usage="iAutoscaleSettingsOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, autoscaleSettingName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="autoscaleSettingName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="07c23-102">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="07c23-102">The name of the resource group.</span></span>
            </param>
        <param name="autoscaleSettingName">
            <span data-ttu-id="07c23-103">自動スケール設定の名前。</span><span class="sxs-lookup"><span data-stu-id="07c23-103">The autoscale setting name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="07c23-104">パラメーターは、操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="07c23-104">Parameters supplied to the operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="07c23-105">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="07c23-105">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="07c23-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="07c23-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="07c23-107">作成するか、自動スケーリングの設定を更新します。</span><span class="sxs-lookup"><span data-stu-id="07c23-107">Creates or updates an autoscale setting.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Monitor.Management.Models.ErrorResponseException">
            <span data-ttu-id="07c23-108">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="07c23-108">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="07c23-109">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="07c23-109">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="07c23-110">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="07c23-110">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string autoscaleSettingName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string autoscaleSettingName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iAutoscaleSettingsOperations.DeleteWithHttpMessagesAsync (resourceGroupName, autoscaleSettingName, customHeaders, cancellationToken)" />
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
        <Parameter Name="autoscaleSettingName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="07c23-111">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="07c23-111">The name of the resource group.</span></span>
            </param>
        <param name="autoscaleSettingName">
            <span data-ttu-id="07c23-112">自動スケール設定の名前。</span><span class="sxs-lookup"><span data-stu-id="07c23-112">The autoscale setting name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="07c23-113">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="07c23-113">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="07c23-114">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="07c23-114">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="07c23-115">削除、および自動スケーリングの設定</span><span class="sxs-lookup"><span data-stu-id="07c23-115">Deletes and autoscale setting</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Monitor.Management.Models.ErrorResponseException">
            <span data-ttu-id="07c23-116">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="07c23-116">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="07c23-117">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="07c23-117">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string autoscaleSettingName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string autoscaleSettingName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource&gt;&gt;" Usage="iAutoscaleSettingsOperations.GetWithHttpMessagesAsync (resourceGroupName, autoscaleSettingName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="autoscaleSettingName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="07c23-118">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="07c23-118">The name of the resource group.</span></span>
            </param>
        <param name="autoscaleSettingName">
            <span data-ttu-id="07c23-119">自動スケール設定の名前。</span><span class="sxs-lookup"><span data-stu-id="07c23-119">The autoscale setting name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="07c23-120">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="07c23-120">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="07c23-121">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="07c23-121">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="07c23-122">自動スケール設定を取得します。</span><span class="sxs-lookup"><span data-stu-id="07c23-122">Gets an autoscale setting</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Monitor.Management.Models.ErrorResponseException">
            <span data-ttu-id="07c23-123">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="07c23-123">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="07c23-124">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="07c23-124">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="07c23-125">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="07c23-125">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource&gt;&gt;&gt; ListByResourceGroupNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource&gt;&gt;&gt; ListByResourceGroupNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations.ListByResourceGroupNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource&gt;&gt;&gt;" Usage="iAutoscaleSettingsOperations.ListByResourceGroupNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="07c23-126">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="07c23-126">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="07c23-127">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="07c23-127">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="07c23-128">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="07c23-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="07c23-129">リソース グループの自動スケール設定を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="07c23-129">Lists the autoscale settings for a resource group</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Monitor.Management.Models.ErrorResponseException">
            <span data-ttu-id="07c23-130">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="07c23-130">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="07c23-131">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="07c23-131">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="07c23-132">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="07c23-132">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync (string resourceGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync(string resourceGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations.ListByResourceGroupWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource&gt;&gt;&gt;" Usage="iAutoscaleSettingsOperations.ListByResourceGroupWithHttpMessagesAsync (resourceGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="07c23-133">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="07c23-133">The name of the resource group.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="07c23-134">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="07c23-134">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="07c23-135">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="07c23-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="07c23-136">リソース グループの自動スケール設定を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="07c23-136">Lists the autoscale settings for a resource group</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Monitor.Management.Models.ErrorResponseException">
            <span data-ttu-id="07c23-137">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="07c23-137">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="07c23-138">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="07c23-138">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="07c23-139">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="07c23-139">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource&gt;&gt; UpdateWithHttpMessagesAsync (string resourceGroupName, string autoscaleSettingName, Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch autoscaleSettingResource, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource&gt;&gt; UpdateWithHttpMessagesAsync(string resourceGroupName, string autoscaleSettingName, class Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch autoscaleSettingResource, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations.UpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource&gt;&gt;" Usage="iAutoscaleSettingsOperations.UpdateWithHttpMessagesAsync (resourceGroupName, autoscaleSettingName, autoscaleSettingResource, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="autoscaleSettingName" Type="System.String" />
        <Parameter Name="autoscaleSettingResource" Type="Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="07c23-140">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="07c23-140">The name of the resource group.</span></span>
            </param>
        <param name="autoscaleSettingName">
            <span data-ttu-id="07c23-141">自動スケール設定の名前。</span><span class="sxs-lookup"><span data-stu-id="07c23-141">The autoscale setting name.</span></span>
            </param>
        <param name="autoscaleSettingResource">
            <span data-ttu-id="07c23-142">パラメーターは、操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="07c23-142">Parameters supplied to the operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="07c23-143">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="07c23-143">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="07c23-144">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="07c23-144">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="07c23-145">既存の AutoscaleSettingsResource を更新します。</span><span class="sxs-lookup"><span data-stu-id="07c23-145">Updates an existing AutoscaleSettingsResource.</span></span> <span data-ttu-id="07c23-146">更新するには、その他のフィールドは、CreateOrUpdate メソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="07c23-146">To update other fields use the CreateOrUpdate method.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Monitor.Management.Models.ErrorResponseException">
            <span data-ttu-id="07c23-147">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="07c23-147">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="07c23-148">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="07c23-148">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="07c23-149">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="07c23-149">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>