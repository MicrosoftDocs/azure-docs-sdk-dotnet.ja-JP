<Type Name="IAppServicePlansOperations" FullName="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations">
  <TypeSignature Language="C#" Value="public interface IAppServicePlansOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IAppServicePlansOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IAppServicePlansOperations" />
  <TypeSignature Language="F#" Value="type IAppServicePlansOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="deaa1-101">AppServicePlansOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-101">AppServicePlansOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string name, Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner appServicePlan, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string name, class Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner appServicePlan, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations.BeginCreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt;" Usage="iAppServicePlansOperations.BeginCreateOrUpdateWithHttpMessagesAsync (resourceGroupName, name, appServicePlan, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="appServicePlan" Type="Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="deaa1-102">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-102">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="deaa1-103">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-103">Name of the App Service plan.</span></span>
            </param>
        <param name="appServicePlan">
            <span data-ttu-id="deaa1-104">App Service の詳細を計画します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-104">Details of the App Service plan.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="deaa1-105">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-105">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="deaa1-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="deaa1-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="deaa1-107">作成するか、App Service プランを更新します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-107">Creates or updates an App Service Plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="deaa1-108">作成するか、App Service プランを更新します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-108">Creates or updates an App Service Plan.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="deaa1-109">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-109">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="deaa1-110">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-110">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="deaa1-111">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-111">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateVnetRouteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt;&gt; CreateOrUpdateVnetRouteWithHttpMessagesAsync (string resourceGroupName, string name, string vnetName, string routeName, Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner route, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt;&gt; CreateOrUpdateVnetRouteWithHttpMessagesAsync(string resourceGroupName, string name, string vnetName, string routeName, class Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner route, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations.CreateOrUpdateVnetRouteWithHttpMessagesAsync(System.String,System.String,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateVnetRouteWithHttpMessagesAsync : string * string * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt;&gt;" Usage="iAppServicePlansOperations.CreateOrUpdateVnetRouteWithHttpMessagesAsync (resourceGroupName, name, vnetName, routeName, route, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="routeName" Type="System.String" />
        <Parameter Name="route" Type="Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="deaa1-112">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-112">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="deaa1-113">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-113">Name of the App Service plan.</span></span>
            </param>
        <param name="vnetName">
            <span data-ttu-id="deaa1-114">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-114">Name of the Virtual Network.</span></span>
            </param>
        <param name="routeName">
            <span data-ttu-id="deaa1-115">仮想ネットワーク ルートの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-115">Name of the Virtual Network route.</span></span>
            </param>
        <param name="route">
            <span data-ttu-id="deaa1-116">仮想ネットワーク ルートを定義します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-116">Definition of the Virtual Network route.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="deaa1-117">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-117">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="deaa1-118">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="deaa1-118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="deaa1-119">作成または、App Service プラン内の仮想ネットワーク ルートを更新します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-119">Create or update a Virtual Network route in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="deaa1-120">作成または、App Service プラン内の仮想ネットワーク ルートを更新します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-120">Create or update a Virtual Network route in an App Service plan.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="deaa1-121">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-121">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="deaa1-122">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-122">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="deaa1-123">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-123">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string name, Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner appServicePlan, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string name, class Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner appServicePlan, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt;" Usage="iAppServicePlansOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, name, appServicePlan, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="appServicePlan" Type="Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="deaa1-124">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-124">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="deaa1-125">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-125">Name of the App Service plan.</span></span>
            </param>
        <param name="appServicePlan">
            <span data-ttu-id="deaa1-126">App Service の詳細を計画します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-126">Details of the App Service plan.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="deaa1-127">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-127">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="deaa1-128">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="deaa1-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="deaa1-129">作成するか、App Service プランを更新します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-129">Creates or updates an App Service Plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="deaa1-130">作成するか、App Service プランを更新します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-130">Creates or updates an App Service Plan.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="deaa1-131">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-131">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="deaa1-132">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-132">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="deaa1-133">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-133">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteHybridConnectionWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteHybridConnectionWithHttpMessagesAsync (string resourceGroupName, string name, string namespaceName, string relayName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteHybridConnectionWithHttpMessagesAsync(string resourceGroupName, string name, string namespaceName, string relayName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations.DeleteHybridConnectionWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteHybridConnectionWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iAppServicePlansOperations.DeleteHybridConnectionWithHttpMessagesAsync (resourceGroupName, name, namespaceName, relayName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="relayName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="deaa1-134">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-134">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="deaa1-135">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-135">Name of the App Service plan.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="deaa1-136">Service Bus 名前空間の名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-136">Name of the Service Bus namespace.</span></span>
            </param>
        <param name="relayName">
            <span data-ttu-id="deaa1-137">Service Bus リレーの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-137">Name of the Service Bus relay.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="deaa1-138">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-138">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="deaa1-139">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="deaa1-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="deaa1-140">App Service プラン内で使用するハイブリッド接続を削除します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-140">Delete a Hybrid Connection in use in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="deaa1-141">App Service プラン内で使用するハイブリッド接続を削除します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-141">Delete a Hybrid Connection in use in an App Service plan.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="deaa1-142">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-142">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="deaa1-143">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-143">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteVnetRouteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteVnetRouteWithHttpMessagesAsync (string resourceGroupName, string name, string vnetName, string routeName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteVnetRouteWithHttpMessagesAsync(string resourceGroupName, string name, string vnetName, string routeName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations.DeleteVnetRouteWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteVnetRouteWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iAppServicePlansOperations.DeleteVnetRouteWithHttpMessagesAsync (resourceGroupName, name, vnetName, routeName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="routeName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="deaa1-144">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-144">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="deaa1-145">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-145">Name of the App Service plan.</span></span>
            </param>
        <param name="vnetName">
            <span data-ttu-id="deaa1-146">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-146">Name of the Virtual Network.</span></span>
            </param>
        <param name="routeName">
            <span data-ttu-id="deaa1-147">仮想ネットワーク ルートの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-147">Name of the Virtual Network route.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="deaa1-148">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-148">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="deaa1-149">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="deaa1-149">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="deaa1-150">App Service プラン内の仮想ネットワーク ルートを削除します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-150">Delete a Virtual Network route in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="deaa1-151">App Service プラン内の仮想ネットワーク ルートを削除します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-151">Delete a Virtual Network route in an App Service plan.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="deaa1-152">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-152">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="deaa1-153">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-153">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iAppServicePlansOperations.DeleteWithHttpMessagesAsync (resourceGroupName, name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="deaa1-154">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-154">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="deaa1-155">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-155">Name of the App Service plan.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="deaa1-156">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-156">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="deaa1-157">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="deaa1-157">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="deaa1-158">App Service プランを削除します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-158">Delete an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="deaa1-159">App Service プランを削除します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-159">Delete an App Service plan.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="deaa1-160">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-160">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="deaa1-161">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-161">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetHybridConnectionPlanLimitWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionLimitsInner&gt;&gt; GetHybridConnectionPlanLimitWithHttpMessagesAsync (string resourceGroupName, string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionLimitsInner&gt;&gt; GetHybridConnectionPlanLimitWithHttpMessagesAsync(string resourceGroupName, string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations.GetHybridConnectionPlanLimitWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetHybridConnectionPlanLimitWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionLimitsInner&gt;&gt;" Usage="iAppServicePlansOperations.GetHybridConnectionPlanLimitWithHttpMessagesAsync (resourceGroupName, name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionLimitsInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="deaa1-162">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-162">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="deaa1-163">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-163">Name of the App Service plan.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="deaa1-164">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-164">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="deaa1-165">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="deaa1-165">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="deaa1-166">App Service プランで許可されているハイブリッド接続の最大数を取得します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-166">Get the maximum number of Hybrid Connections allowed in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="deaa1-167">App Service プランで許可されているハイブリッド接続の最大数を取得します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-167">Get the maximum number of Hybrid Connections allowed in an App Service plan.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="deaa1-168">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-168">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="deaa1-169">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-169">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="deaa1-170">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-170">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetHybridConnectionWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionInner&gt;&gt; GetHybridConnectionWithHttpMessagesAsync (string resourceGroupName, string name, string namespaceName, string relayName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionInner&gt;&gt; GetHybridConnectionWithHttpMessagesAsync(string resourceGroupName, string name, string namespaceName, string relayName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations.GetHybridConnectionWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetHybridConnectionWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionInner&gt;&gt;" Usage="iAppServicePlansOperations.GetHybridConnectionWithHttpMessagesAsync (resourceGroupName, name, namespaceName, relayName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="relayName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="deaa1-171">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-171">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="deaa1-172">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-172">Name of the App Service plan.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="deaa1-173">Service Bus 名前空間の名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-173">Name of the Service Bus namespace.</span></span>
            </param>
        <param name="relayName">
            <span data-ttu-id="deaa1-174">Service Bus リレーの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-174">Name of the Service Bus relay.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="deaa1-175">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-175">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="deaa1-176">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="deaa1-176">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="deaa1-177">App Service プラン内で使用するハイブリッド接続を取得します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-177">Retrieve a Hybrid Connection in use in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="deaa1-178">App Service プラン内で使用するハイブリッド接続を取得します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-178">Retrieve a Hybrid Connection in use in an App Service plan.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="deaa1-179">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-179">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="deaa1-180">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-180">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="deaa1-181">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-181">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetRouteForVnetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt;&gt;&gt; GetRouteForVnetWithHttpMessagesAsync (string resourceGroupName, string name, string vnetName, string routeName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt;&gt;&gt; GetRouteForVnetWithHttpMessagesAsync(string resourceGroupName, string name, string vnetName, string routeName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations.GetRouteForVnetWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetRouteForVnetWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt;&gt;&gt;" Usage="iAppServicePlansOperations.GetRouteForVnetWithHttpMessagesAsync (resourceGroupName, name, vnetName, routeName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="routeName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="deaa1-182">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-182">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="deaa1-183">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-183">Name of the App Service plan.</span></span>
            </param>
        <param name="vnetName">
            <span data-ttu-id="deaa1-184">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-184">Name of the Virtual Network.</span></span>
            </param>
        <param name="routeName">
            <span data-ttu-id="deaa1-185">仮想ネットワーク ルートの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-185">Name of the Virtual Network route.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="deaa1-186">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-186">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="deaa1-187">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="deaa1-187">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="deaa1-188">App Service プラン内の仮想ネットワーク ルートを取得します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-188">Get a Virtual Network route in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="deaa1-189">App Service プラン内の仮想ネットワーク ルートを取得します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-189">Get a Virtual Network route in an App Service plan.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="deaa1-190">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-190">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="deaa1-191">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-191">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="deaa1-192">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-192">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetVnetFromServerFarmWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner&gt;&gt; GetVnetFromServerFarmWithHttpMessagesAsync (string resourceGroupName, string name, string vnetName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner&gt;&gt; GetVnetFromServerFarmWithHttpMessagesAsync(string resourceGroupName, string name, string vnetName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations.GetVnetFromServerFarmWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetVnetFromServerFarmWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner&gt;&gt;" Usage="iAppServicePlansOperations.GetVnetFromServerFarmWithHttpMessagesAsync (resourceGroupName, name, vnetName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="deaa1-193">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-193">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="deaa1-194">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-194">Name of the App Service plan.</span></span>
            </param>
        <param name="vnetName">
            <span data-ttu-id="deaa1-195">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-195">Name of the Virtual Network.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="deaa1-196">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-196">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="deaa1-197">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="deaa1-197">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="deaa1-198">App Service プランに関連付けられている仮想ネットワークを取得します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-198">Get a Virtual Network associated with an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="deaa1-199">App Service プランに関連付けられている仮想ネットワークを取得します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-199">Get a Virtual Network associated with an App Service plan.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="deaa1-200">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-200">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="deaa1-201">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-201">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="deaa1-202">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-202">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetVnetGatewayWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetGatewayInner&gt;&gt; GetVnetGatewayWithHttpMessagesAsync (string resourceGroupName, string name, string vnetName, string gatewayName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.VnetGatewayInner&gt;&gt; GetVnetGatewayWithHttpMessagesAsync(string resourceGroupName, string name, string vnetName, string gatewayName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations.GetVnetGatewayWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetVnetGatewayWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetGatewayInner&gt;&gt;" Usage="iAppServicePlansOperations.GetVnetGatewayWithHttpMessagesAsync (resourceGroupName, name, vnetName, gatewayName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetGatewayInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="deaa1-203">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-203">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="deaa1-204">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-204">Name of the App Service plan.</span></span>
            </param>
        <param name="vnetName">
            <span data-ttu-id="deaa1-205">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-205">Name of the Virtual Network.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="deaa1-206">ゲートウェイの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-206">Name of the gateway.</span></span> <span data-ttu-id="deaa1-207">'Primary' のゲートウェイのみがサポートされています。</span><span class="sxs-lookup"><span data-stu-id="deaa1-207">Only the 'primary' gateway is supported.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="deaa1-208">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-208">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="deaa1-209">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="deaa1-209">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="deaa1-210">仮想ネットワーク ゲートウェイを取得します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-210">Get a Virtual Network gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="deaa1-211">仮想ネットワーク ゲートウェイを取得します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-211">Get a Virtual Network gateway.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="deaa1-212">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-212">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="deaa1-213">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-213">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="deaa1-214">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-214">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations.GetWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt;" Usage="iAppServicePlansOperations.GetWithHttpMessagesAsync (resourceGroupName, name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="deaa1-215">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-215">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="deaa1-216">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-216">Name of the App Service plan.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="deaa1-217">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-217">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="deaa1-218">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="deaa1-218">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="deaa1-219">App Service プランを取得します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-219">Get an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="deaa1-220">App Service プランを取得します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-220">Get an App Service plan.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="deaa1-221">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-221">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="deaa1-222">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-222">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="deaa1-223">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-223">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt;&gt; ListByResourceGroupNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt;&gt; ListByResourceGroupNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations.ListByResourceGroupNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt;&gt;" Usage="iAppServicePlansOperations.ListByResourceGroupNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="deaa1-224">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-224">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="deaa1-225">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-225">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="deaa1-226">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="deaa1-226">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="deaa1-227">リソース グループ内のすべての App Service プランを取得します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-227">Get all App Service plans in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="deaa1-228">リソース グループ内のすべての App Service プランを取得します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-228">Get all App Service plans in a resource group.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="deaa1-229">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-229">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="deaa1-230">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-230">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="deaa1-231">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-231">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync (string resourceGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync(string resourceGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations.ListByResourceGroupWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt;&gt;" Usage="iAppServicePlansOperations.ListByResourceGroupWithHttpMessagesAsync (resourceGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="deaa1-232">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-232">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="deaa1-233">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-233">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="deaa1-234">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="deaa1-234">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="deaa1-235">リソース グループ内のすべての App Service プランを取得します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-235">Get all App Service plans in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="deaa1-236">リソース グループ内のすべての App Service プランを取得します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-236">Get all App Service plans in a resource group.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="deaa1-237">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-237">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="deaa1-238">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-238">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="deaa1-239">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-239">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListCapabilitiesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CapabilityInner&gt;&gt;&gt; ListCapabilitiesWithHttpMessagesAsync (string resourceGroupName, string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.CapabilityInner&gt;&gt;&gt; ListCapabilitiesWithHttpMessagesAsync(string resourceGroupName, string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations.ListCapabilitiesWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListCapabilitiesWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CapabilityInner&gt;&gt;&gt;" Usage="iAppServicePlansOperations.ListCapabilitiesWithHttpMessagesAsync (resourceGroupName, name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CapabilityInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="deaa1-240">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-240">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="deaa1-241">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-241">Name of the App Service plan.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="deaa1-242">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-242">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="deaa1-243">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="deaa1-243">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="deaa1-244">App Service プランのすべての機能を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-244">List all capabilities of an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="deaa1-245">App Service プランのすべての機能を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-245">List all capabilities of an App Service plan.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="deaa1-246">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-246">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="deaa1-247">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-247">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="deaa1-248">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-248">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListHybridConnectionKeysWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionKeyInner&gt;&gt; ListHybridConnectionKeysWithHttpMessagesAsync (string resourceGroupName, string name, string namespaceName, string relayName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionKeyInner&gt;&gt; ListHybridConnectionKeysWithHttpMessagesAsync(string resourceGroupName, string name, string namespaceName, string relayName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations.ListHybridConnectionKeysWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListHybridConnectionKeysWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionKeyInner&gt;&gt;" Usage="iAppServicePlansOperations.ListHybridConnectionKeysWithHttpMessagesAsync (resourceGroupName, name, namespaceName, relayName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionKeyInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="relayName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="deaa1-249">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-249">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="deaa1-250">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-250">Name of the App Service plan.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="deaa1-251">Service Bus 名前空間の名前。</span><span class="sxs-lookup"><span data-stu-id="deaa1-251">The name of the Service Bus namespace.</span></span>
            </param>
        <param name="relayName">
            <span data-ttu-id="deaa1-252">Service Bus リレーの名前。</span><span class="sxs-lookup"><span data-stu-id="deaa1-252">The name of the Service Bus relay.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="deaa1-253">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-253">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="deaa1-254">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="deaa1-254">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="deaa1-255">ハイブリッド接続の値と送信のキーの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-255">Get the send key name and value of a Hybrid Connection.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="deaa1-256">ハイブリッド接続の値と送信のキーの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-256">Get the send key name and value of a Hybrid Connection.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="deaa1-257">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-257">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="deaa1-258">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-258">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="deaa1-259">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-259">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListHybridConnectionsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionInner&gt;&gt;&gt; ListHybridConnectionsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionInner&gt;&gt;&gt; ListHybridConnectionsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations.ListHybridConnectionsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListHybridConnectionsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionInner&gt;&gt;&gt;" Usage="iAppServicePlansOperations.ListHybridConnectionsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="deaa1-260">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-260">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="deaa1-261">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-261">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="deaa1-262">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="deaa1-262">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="deaa1-263">App Service プランで使用中のすべてのハイブリッド接続を取得します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-263">Retrieve all Hybrid Connections in use in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="deaa1-264">App Service プランで使用中のすべてのハイブリッド接続を取得します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-264">Retrieve all Hybrid Connections in use in an App Service plan.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="deaa1-265">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-265">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="deaa1-266">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-266">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="deaa1-267">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-267">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListHybridConnectionsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionInner&gt;&gt;&gt; ListHybridConnectionsWithHttpMessagesAsync (string resourceGroupName, string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionInner&gt;&gt;&gt; ListHybridConnectionsWithHttpMessagesAsync(string resourceGroupName, string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations.ListHybridConnectionsWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListHybridConnectionsWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionInner&gt;&gt;&gt;" Usage="iAppServicePlansOperations.ListHybridConnectionsWithHttpMessagesAsync (resourceGroupName, name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="deaa1-268">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-268">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="deaa1-269">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-269">Name of the App Service plan.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="deaa1-270">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-270">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="deaa1-271">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="deaa1-271">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="deaa1-272">App Service プランで使用中のすべてのハイブリッド接続を取得します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-272">Retrieve all Hybrid Connections in use in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="deaa1-273">App Service プランで使用中のすべてのハイブリッド接続を取得します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-273">Retrieve all Hybrid Connections in use in an App Service plan.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="deaa1-274">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-274">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="deaa1-275">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-275">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="deaa1-276">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-276">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListMetricDefintionsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;&gt; ListMetricDefintionsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;&gt; ListMetricDefintionsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations.ListMetricDefintionsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListMetricDefintionsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;&gt;" Usage="iAppServicePlansOperations.ListMetricDefintionsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricDefintionsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;&gt; ListMetricDefintionsWithHttpMessagesAsync (string resourceGroupName, string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;&gt; ListMetricDefintionsWithHttpMessagesAsync(string resourceGroupName, string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations.ListMetricDefintionsWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListMetricDefintionsWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;&gt;" Usage="iAppServicePlansOperations.ListMetricDefintionsWithHttpMessagesAsync (resourceGroupName, name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="name">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;&gt; ListMetricsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;&gt; ListMetricsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations.ListMetricsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListMetricsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;&gt;" Usage="iAppServicePlansOperations.ListMetricsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="deaa1-277">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-277">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="deaa1-278">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-278">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="deaa1-279">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="deaa1-279">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="deaa1-280">アプリ サービス プランのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-280">Get metrics for an App Serice plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="deaa1-281">アプリ サービス プランのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-281">Get metrics for an App Serice plan.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="deaa1-282">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-282">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="deaa1-283">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-283">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="deaa1-284">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-284">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListMetricsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;&gt; ListMetricsWithHttpMessagesAsync (string resourceGroupName, string name, Nullable&lt;bool&gt; details = null, string filter = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;&gt; ListMetricsWithHttpMessagesAsync(string resourceGroupName, string name, valuetype System.Nullable`1&lt;bool&gt; details, string filter, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations.ListMetricsWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Boolean},System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListMetricsWithHttpMessagesAsync : string * string * Nullable&lt;bool&gt; * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;&gt;" Usage="iAppServicePlansOperations.ListMetricsWithHttpMessagesAsync (resourceGroupName, name, details, filter, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="details" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="deaa1-285">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-285">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="deaa1-286">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-286">Name of the App Service plan.</span></span>
            </param>
        <param name="details">
            <span data-ttu-id="deaa1-287">指定&lt;コード&gt;true&lt;/code&gt;にインスタンスの詳細を含めます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-287">Specify &lt;code&gt;true&lt;/code&gt; to include instance details.</span></span>
            <span data-ttu-id="deaa1-288">既定値は&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-288">The default is &lt;code&gt;false&lt;/code&gt;.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="deaa1-289">使用状況/メトリックのみ、フィルターで指定されたを返します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-289">Return only usages/metrics specified in the filter.</span></span> <span data-ttu-id="deaa1-290">フィルターは、odata 構文に準拠します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-290">Filter conforms to odata syntax.</span></span> <span data-ttu-id="deaa1-291">例: $filter = (name.value eq 'Metric1' または name.value eq 'Metric2') と startTime eq '2014-01-01T00:00:00Z' と endTime eq' 2014-12-31T23:59:59Z' と timeGrain eq 期間 ' [時間 |分 |1 日]'。</span><span class="sxs-lookup"><span data-stu-id="deaa1-291">Example: $filter=(name.value eq 'Metric1' or name.value eq 'Metric2') and startTime eq '2014-01-01T00:00:00Z' and endTime eq '2014-12-31T23:59:59Z' and timeGrain eq duration'[Hour|Minute|Day]'.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="deaa1-292">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-292">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="deaa1-293">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="deaa1-293">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="deaa1-294">アプリ サービス プランのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-294">Get metrics for an App Serice plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="deaa1-295">アプリ サービス プランのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-295">Get metrics for an App Serice plan.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="deaa1-296">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-296">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="deaa1-297">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-297">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="deaa1-298">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-298">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations.ListNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt;&gt;" Usage="iAppServicePlansOperations.ListNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="deaa1-299">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-299">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="deaa1-300">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-300">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="deaa1-301">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="deaa1-301">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="deaa1-302">サブスクリプションのすべての App Service プランを取得します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-302">Get all App Service plans for a subcription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="deaa1-303">サブスクリプションのすべての App Service プランを取得します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-303">Get all App Service plans for a subcription.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="deaa1-304">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-304">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="deaa1-305">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-305">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="deaa1-306">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-306">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListRoutesForVnetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt;&gt;&gt; ListRoutesForVnetWithHttpMessagesAsync (string resourceGroupName, string name, string vnetName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt;&gt;&gt; ListRoutesForVnetWithHttpMessagesAsync(string resourceGroupName, string name, string vnetName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations.ListRoutesForVnetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListRoutesForVnetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt;&gt;&gt;" Usage="iAppServicePlansOperations.ListRoutesForVnetWithHttpMessagesAsync (resourceGroupName, name, vnetName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="deaa1-307">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-307">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="deaa1-308">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-308">Name of the App Service plan.</span></span>
            </param>
        <param name="vnetName">
            <span data-ttu-id="deaa1-309">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-309">Name of the Virtual Network.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="deaa1-310">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-310">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="deaa1-311">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="deaa1-311">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="deaa1-312">App Service プラン内の仮想ネットワークに関連付けられているすべてのルートを取得します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-312">Get all routes that are associated with a Virtual Network in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="deaa1-313">App Service プラン内の仮想ネットワークに関連付けられているすべてのルートを取得します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-313">Get all routes that are associated with a Virtual Network in an App Service plan.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="deaa1-314">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-314">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="deaa1-315">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-315">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="deaa1-316">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-316">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListVnetsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner&gt;&gt;&gt; ListVnetsWithHttpMessagesAsync (string resourceGroupName, string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner&gt;&gt;&gt; ListVnetsWithHttpMessagesAsync(string resourceGroupName, string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations.ListVnetsWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListVnetsWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner&gt;&gt;&gt;" Usage="iAppServicePlansOperations.ListVnetsWithHttpMessagesAsync (resourceGroupName, name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="deaa1-317">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-317">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="deaa1-318">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-318">Name of the App Service plan.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="deaa1-319">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-319">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="deaa1-320">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="deaa1-320">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="deaa1-321">App Service プランに関連付けられているすべての仮想ネットワークを取得します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-321">Get all Virtual Networks associated with an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="deaa1-322">App Service プランに関連付けられているすべての仮想ネットワークを取得します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-322">Get all Virtual Networks associated with an App Service plan.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="deaa1-323">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-323">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="deaa1-324">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-324">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="deaa1-325">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-325">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWebAppsByHybridConnectionNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;string&gt;&gt;&gt; ListWebAppsByHybridConnectionNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;string&gt;&gt;&gt; ListWebAppsByHybridConnectionNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations.ListWebAppsByHybridConnectionNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWebAppsByHybridConnectionNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;string&gt;&gt;&gt;" Usage="iAppServicePlansOperations.ListWebAppsByHybridConnectionNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;System.String&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="deaa1-326">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-326">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="deaa1-327">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-327">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="deaa1-328">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="deaa1-328">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="deaa1-329">App Service プランのハイブリッド接続を使用するすべてのアプリを取得します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-329">Get all apps that use a Hybrid Connection in an App Service Plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="deaa1-330">App Service プランのハイブリッド接続を使用するすべてのアプリを取得します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-330">Get all apps that use a Hybrid Connection in an App Service Plan.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="deaa1-331">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-331">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="deaa1-332">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-332">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="deaa1-333">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-333">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWebAppsByHybridConnectionWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;string&gt;&gt;&gt; ListWebAppsByHybridConnectionWithHttpMessagesAsync (string resourceGroupName, string name, string namespaceName, string relayName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;string&gt;&gt;&gt; ListWebAppsByHybridConnectionWithHttpMessagesAsync(string resourceGroupName, string name, string namespaceName, string relayName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations.ListWebAppsByHybridConnectionWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWebAppsByHybridConnectionWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;string&gt;&gt;&gt;" Usage="iAppServicePlansOperations.ListWebAppsByHybridConnectionWithHttpMessagesAsync (resourceGroupName, name, namespaceName, relayName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;System.String&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="relayName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="deaa1-334">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-334">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="deaa1-335">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-335">Name of the App Service plan.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="deaa1-336">ハイブリッド接続の名前空間の名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-336">Name of the Hybrid Connection namespace.</span></span>
            </param>
        <param name="relayName">
            <span data-ttu-id="deaa1-337">ハイブリッド接続リレーの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-337">Name of the Hybrid Connection relay.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="deaa1-338">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-338">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="deaa1-339">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="deaa1-339">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="deaa1-340">App Service プランのハイブリッド接続を使用するすべてのアプリを取得します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-340">Get all apps that use a Hybrid Connection in an App Service Plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="deaa1-341">App Service プランのハイブリッド接続を使用するすべてのアプリを取得します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-341">Get all apps that use a Hybrid Connection in an App Service Plan.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="deaa1-342">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-342">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="deaa1-343">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-343">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="deaa1-344">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-344">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWebAppsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;&gt; ListWebAppsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;&gt; ListWebAppsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations.ListWebAppsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWebAppsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;&gt;" Usage="iAppServicePlansOperations.ListWebAppsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="deaa1-345">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-345">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="deaa1-346">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-346">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="deaa1-347">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="deaa1-347">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="deaa1-348">App Service プランに関連付けられているすべてのアプリを取得します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-348">Get all apps associated with an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="deaa1-349">App Service プランに関連付けられているすべてのアプリを取得します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-349">Get all apps associated with an App Service plan.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="deaa1-350">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-350">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="deaa1-351">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-351">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="deaa1-352">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-352">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWebAppsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;&gt; ListWebAppsWithHttpMessagesAsync (string resourceGroupName, string name, string skipToken = null, string filter = null, string top = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;&gt; ListWebAppsWithHttpMessagesAsync(string resourceGroupName, string name, string skipToken, string filter, string top, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations.ListWebAppsWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWebAppsWithHttpMessagesAsync : string * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;&gt;" Usage="iAppServicePlansOperations.ListWebAppsWithHttpMessagesAsync (resourceGroupName, name, skipToken, filter, top, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="skipToken" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="top" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="deaa1-353">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-353">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="deaa1-354">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-354">Name of the App Service plan.</span></span>
            </param>
        <param name="skipToken">
            <span data-ttu-id="deaa1-355">App service プランに関連付けられている webapps の一覧で web アプリに進んでください。</span><span class="sxs-lookup"><span data-stu-id="deaa1-355">Skip to a web app in the list of webapps associated with app service plan.</span></span> <span data-ttu-id="deaa1-356">指定した場合、結果のリスト (など)、skipToken から web アプリが含まれます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-356">If specified, the resulting list will contain web apps starting from (including) the skipToken.</span></span> <span data-ttu-id="deaa1-357">それ以外の場合、結果のリストが一覧の先頭からの web アプリが含まれます</span><span class="sxs-lookup"><span data-stu-id="deaa1-357">Otherwise, the resulting list contains web apps from the start of the list</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="deaa1-358">サポートされているフィルター: $filter を実行している状態 eq を = です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-358">Supported filter: $filter=state eq running.</span></span> <span data-ttu-id="deaa1-359">現在実行されている web アプリのみを返します</span><span class="sxs-lookup"><span data-stu-id="deaa1-359">Returns only web apps that are currently running</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="deaa1-360">ページ サイズを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-360">List page size.</span></span> <span data-ttu-id="deaa1-361">指定すると、結果がページングされています。</span><span class="sxs-lookup"><span data-stu-id="deaa1-361">If specified, results are paged.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="deaa1-362">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-362">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="deaa1-363">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="deaa1-363">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="deaa1-364">App Service プランに関連付けられているすべてのアプリを取得します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-364">Get all apps associated with an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="deaa1-365">App Service プランに関連付けられているすべてのアプリを取得します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-365">Get all apps associated with an App Service plan.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="deaa1-366">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-366">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="deaa1-367">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-367">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="deaa1-368">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-368">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt;&gt; ListWithHttpMessagesAsync (Nullable&lt;bool&gt; detailed = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt;&gt; ListWithHttpMessagesAsync(valuetype System.Nullable`1&lt;bool&gt; detailed, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations.ListWithHttpMessagesAsync(System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt;&gt;" Usage="iAppServicePlansOperations.ListWithHttpMessagesAsync (detailed, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="detailed" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="detailed">
            <span data-ttu-id="deaa1-369">指定&lt;コード&gt;true&lt;/code&gt;をすべての App Service プランのプロパティを返します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-369">Specify &lt;code&gt;true&lt;/code&gt; to return all App Service plan properties.</span></span> <span data-ttu-id="deaa1-370">既定値は&lt;コード&gt;false&lt;/code&gt;プロパティのサブセットが返されます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-370">The default is &lt;code&gt;false&lt;/code&gt;, which returns a subset of the properties.</span></span>
            <span data-ttu-id="deaa1-371">すべてのプロパティの取得には、API の待機時間が増加します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-371">Retrieval of all properties may increase the API latency.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="deaa1-372">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-372">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="deaa1-373">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="deaa1-373">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="deaa1-374">サブスクリプションのすべての App Service プランを取得します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-374">Get all App Service plans for a subcription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="deaa1-375">サブスクリプションのすべての App Service プランを取得します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-375">Get all App Service plans for a subcription.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="deaa1-376">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-376">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="deaa1-377">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-377">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="deaa1-378">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-378">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RebootWorkerWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; RebootWorkerWithHttpMessagesAsync (string resourceGroupName, string name, string workerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; RebootWorkerWithHttpMessagesAsync(string resourceGroupName, string name, string workerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations.RebootWorkerWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RebootWorkerWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iAppServicePlansOperations.RebootWorkerWithHttpMessagesAsync (resourceGroupName, name, workerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="deaa1-379">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-379">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="deaa1-380">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-380">Name of the App Service plan.</span></span>
            </param>
        <param name="workerName">
            <span data-ttu-id="deaa1-381">通常 RD. で始まるワーカー コンピューターの名前</span><span class="sxs-lookup"><span data-stu-id="deaa1-381">Name of worker machine, which typically starts with RD.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="deaa1-382">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-382">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="deaa1-383">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="deaa1-383">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="deaa1-384">App Service プラン内のワーカーのコンピューターを再起動します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-384">Reboot a worker machine in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="deaa1-385">App Service プラン内のワーカーのコンピューターを再起動します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-385">Reboot a worker machine in an App Service plan.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="deaa1-386">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-386">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="deaa1-387">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-387">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RestartWebAppsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; RestartWebAppsWithHttpMessagesAsync (string resourceGroupName, string name, Nullable&lt;bool&gt; softRestart = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; RestartWebAppsWithHttpMessagesAsync(string resourceGroupName, string name, valuetype System.Nullable`1&lt;bool&gt; softRestart, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations.RestartWebAppsWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RestartWebAppsWithHttpMessagesAsync : string * string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iAppServicePlansOperations.RestartWebAppsWithHttpMessagesAsync (resourceGroupName, name, softRestart, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="softRestart" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="deaa1-388">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-388">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="deaa1-389">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-389">Name of the App Service plan.</span></span>
            </param>
        <param name="softRestart">
            <span data-ttu-id="deaa1-390">指定&lt;コード&gt;true&lt;/code&gt;かからず、ソフト再起動、構成設定を適用し、必要に応じて、アプリを再起動します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-390">Specify &lt;code&gt;true&lt;/code&gt; to performa a soft restart, applies the configuration settings and restarts the apps if necessary.</span></span> <span data-ttu-id="deaa1-391">既定値は&lt;コード&gt;false&lt;/code&gt;を常に再起動し、アプリを reprovisions</span><span class="sxs-lookup"><span data-stu-id="deaa1-391">The default is &lt;code&gt;false&lt;/code&gt;, which always restarts and reprovisions the apps</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="deaa1-392">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-392">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="deaa1-393">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="deaa1-393">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="deaa1-394">App Service プラン内のすべてのアプリを再起動します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-394">Restart all apps in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="deaa1-395">App Service プラン内のすべてのアプリを再起動します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-395">Restart all apps in an App Service plan.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="deaa1-396">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-396">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="deaa1-397">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-397">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateVnetGatewayWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetGatewayInner&gt;&gt; UpdateVnetGatewayWithHttpMessagesAsync (string resourceGroupName, string name, string vnetName, string gatewayName, Microsoft.Azure.Management.AppService.Fluent.Models.VnetGatewayInner connectionEnvelope, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.VnetGatewayInner&gt;&gt; UpdateVnetGatewayWithHttpMessagesAsync(string resourceGroupName, string name, string vnetName, string gatewayName, class Microsoft.Azure.Management.AppService.Fluent.Models.VnetGatewayInner connectionEnvelope, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations.UpdateVnetGatewayWithHttpMessagesAsync(System.String,System.String,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.VnetGatewayInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateVnetGatewayWithHttpMessagesAsync : string * string * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.VnetGatewayInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetGatewayInner&gt;&gt;" Usage="iAppServicePlansOperations.UpdateVnetGatewayWithHttpMessagesAsync (resourceGroupName, name, vnetName, gatewayName, connectionEnvelope, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetGatewayInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
        <Parameter Name="connectionEnvelope" Type="Microsoft.Azure.Management.AppService.Fluent.Models.VnetGatewayInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="deaa1-398">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-398">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="deaa1-399">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-399">Name of the App Service plan.</span></span>
            </param>
        <param name="vnetName">
            <span data-ttu-id="deaa1-400">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-400">Name of the Virtual Network.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="deaa1-401">ゲートウェイの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-401">Name of the gateway.</span></span> <span data-ttu-id="deaa1-402">'Primary' のゲートウェイのみがサポートされています。</span><span class="sxs-lookup"><span data-stu-id="deaa1-402">Only the 'primary' gateway is supported.</span></span>
            </param>
        <param name="connectionEnvelope">
            <span data-ttu-id="deaa1-403">ゲートウェイの定義です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-403">Definition of the gateway.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="deaa1-404">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-404">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="deaa1-405">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="deaa1-405">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="deaa1-406">仮想ネットワーク ゲートウェイを更新します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-406">Update a Virtual Network gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="deaa1-407">仮想ネットワーク ゲートウェイを更新します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-407">Update a Virtual Network gateway.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="deaa1-408">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-408">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="deaa1-409">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-409">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="deaa1-410">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-410">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateVnetRouteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt;&gt; UpdateVnetRouteWithHttpMessagesAsync (string resourceGroupName, string name, string vnetName, string routeName, Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner route, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt;&gt; UpdateVnetRouteWithHttpMessagesAsync(string resourceGroupName, string name, string vnetName, string routeName, class Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner route, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations.UpdateVnetRouteWithHttpMessagesAsync(System.String,System.String,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateVnetRouteWithHttpMessagesAsync : string * string * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt;&gt;" Usage="iAppServicePlansOperations.UpdateVnetRouteWithHttpMessagesAsync (resourceGroupName, name, vnetName, routeName, route, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="routeName" Type="System.String" />
        <Parameter Name="route" Type="Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="deaa1-411">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-411">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="deaa1-412">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-412">Name of the App Service plan.</span></span>
            </param>
        <param name="vnetName">
            <span data-ttu-id="deaa1-413">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-413">Name of the Virtual Network.</span></span>
            </param>
        <param name="routeName">
            <span data-ttu-id="deaa1-414">仮想ネットワーク ルートの名前です。</span><span class="sxs-lookup"><span data-stu-id="deaa1-414">Name of the Virtual Network route.</span></span>
            </param>
        <param name="route">
            <span data-ttu-id="deaa1-415">仮想ネットワーク ルートを定義します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-415">Definition of the Virtual Network route.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="deaa1-416">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-416">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="deaa1-417">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="deaa1-417">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="deaa1-418">作成または、App Service プラン内の仮想ネットワーク ルートを更新します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-418">Create or update a Virtual Network route in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="deaa1-419">作成または、App Service プラン内の仮想ネットワーク ルートを更新します。</span><span class="sxs-lookup"><span data-stu-id="deaa1-419">Create or update a Virtual Network route in an App Service plan.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="deaa1-420">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-420">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="deaa1-421">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-421">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="deaa1-422">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="deaa1-422">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>