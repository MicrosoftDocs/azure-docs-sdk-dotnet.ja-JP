<Type Name="IExpressRouteCircuitsOperations" FullName="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations">
  <TypeSignature Language="C#" Value="public interface IExpressRouteCircuitsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IExpressRouteCircuitsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IExpressRouteCircuitsOperations" />
  <TypeSignature Language="F#" Value="type IExpressRouteCircuitsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="fed60-101">ExpressRouteCircuitsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="fed60-101">ExpressRouteCircuitsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string circuitName, Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string circuitName, class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations.BeginCreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt;" Usage="iExpressRouteCircuitsOperations.BeginCreateOrUpdateWithHttpMessagesAsync (resourceGroupName, circuitName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fed60-102">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fed60-102">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="fed60-103">回路の名前。</span><span class="sxs-lookup"><span data-stu-id="fed60-103">The name of the circuit.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fed60-104">作成または更新の express route 回線操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="fed60-104">Parameters supplied to the create or update express route circuit operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fed60-105">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="fed60-105">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fed60-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fed60-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fed60-107">作成するか、express route 回線を更新します。</span><span class="sxs-lookup"><span data-stu-id="fed60-107">Creates or updates an express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fed60-108">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fed60-108">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="fed60-109">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fed60-109">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fed60-110">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fed60-110">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync (string resourceGroupName, string circuitName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync(string resourceGroupName, string circuitName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations.BeginDeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iExpressRouteCircuitsOperations.BeginDeleteWithHttpMessagesAsync (resourceGroupName, circuitName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fed60-111">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fed60-111">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="fed60-112">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="fed60-112">The name of the express route circuit.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fed60-113">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="fed60-113">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fed60-114">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fed60-114">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fed60-115">指定の express route 回線を削除します。</span><span class="sxs-lookup"><span data-stu-id="fed60-115">Deletes the specified express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fed60-116">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fed60-116">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fed60-117">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fed60-117">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginListArpTableWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsArpTableListResultInner&gt;&gt; BeginListArpTableWithHttpMessagesAsync (string resourceGroupName, string circuitName, string peeringName, string devicePath, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsArpTableListResultInner&gt;&gt; BeginListArpTableWithHttpMessagesAsync(string resourceGroupName, string circuitName, string peeringName, string devicePath, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations.BeginListArpTableWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginListArpTableWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsArpTableListResultInner&gt;&gt;" Usage="iExpressRouteCircuitsOperations.BeginListArpTableWithHttpMessagesAsync (resourceGroupName, circuitName, peeringName, devicePath, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsArpTableListResultInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="devicePath" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fed60-118">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fed60-118">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="fed60-119">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="fed60-119">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="fed60-120">ピアリングの名前。</span><span class="sxs-lookup"><span data-stu-id="fed60-120">The name of the peering.</span></span>
            </param>
        <param name="devicePath">
            <span data-ttu-id="fed60-121">デバイスのパス。</span><span class="sxs-lookup"><span data-stu-id="fed60-121">The path of the device.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fed60-122">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="fed60-122">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fed60-123">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fed60-123">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fed60-124">リソース グループ内の express route 回線に関連付けられている現在の提供の ARP テーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="fed60-124">Gets the currently advertised ARP table associated with the express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fed60-125">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fed60-125">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="fed60-126">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fed60-126">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fed60-127">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fed60-127">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginListRoutesTableSummaryWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsRoutesTableSummaryListResultInner&gt;&gt; BeginListRoutesTableSummaryWithHttpMessagesAsync (string resourceGroupName, string circuitName, string peeringName, string devicePath, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsRoutesTableSummaryListResultInner&gt;&gt; BeginListRoutesTableSummaryWithHttpMessagesAsync(string resourceGroupName, string circuitName, string peeringName, string devicePath, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations.BeginListRoutesTableSummaryWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginListRoutesTableSummaryWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsRoutesTableSummaryListResultInner&gt;&gt;" Usage="iExpressRouteCircuitsOperations.BeginListRoutesTableSummaryWithHttpMessagesAsync (resourceGroupName, circuitName, peeringName, devicePath, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsRoutesTableSummaryListResultInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="devicePath" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fed60-128">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fed60-128">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="fed60-129">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="fed60-129">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="fed60-130">ピアリングの名前。</span><span class="sxs-lookup"><span data-stu-id="fed60-130">The name of the peering.</span></span>
            </param>
        <param name="devicePath">
            <span data-ttu-id="fed60-131">デバイスのパス。</span><span class="sxs-lookup"><span data-stu-id="fed60-131">The path of the device.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fed60-132">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="fed60-132">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fed60-133">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fed60-133">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fed60-134">リソース グループ内の express route 回線に関連付けられている概要現在アドバタイズされたルート テーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="fed60-134">Gets the currently advertised routes table summary associated with the express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fed60-135">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fed60-135">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="fed60-136">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fed60-136">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fed60-137">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fed60-137">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginListRoutesTableWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsRoutesTableListResultInner&gt;&gt; BeginListRoutesTableWithHttpMessagesAsync (string resourceGroupName, string circuitName, string peeringName, string devicePath, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsRoutesTableListResultInner&gt;&gt; BeginListRoutesTableWithHttpMessagesAsync(string resourceGroupName, string circuitName, string peeringName, string devicePath, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations.BeginListRoutesTableWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginListRoutesTableWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsRoutesTableListResultInner&gt;&gt;" Usage="iExpressRouteCircuitsOperations.BeginListRoutesTableWithHttpMessagesAsync (resourceGroupName, circuitName, peeringName, devicePath, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsRoutesTableListResultInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="devicePath" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fed60-138">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fed60-138">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="fed60-139">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="fed60-139">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="fed60-140">ピアリングの名前。</span><span class="sxs-lookup"><span data-stu-id="fed60-140">The name of the peering.</span></span>
            </param>
        <param name="devicePath">
            <span data-ttu-id="fed60-141">デバイスのパス。</span><span class="sxs-lookup"><span data-stu-id="fed60-141">The path of the device.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fed60-142">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="fed60-142">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fed60-143">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fed60-143">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fed60-144">リソース グループ内の express route 回線に関連付けられている現在アドバタイズされたルート テーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="fed60-144">Gets the currently advertised routes table associated with the express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fed60-145">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fed60-145">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="fed60-146">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fed60-146">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fed60-147">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fed60-147">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string circuitName, Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string circuitName, class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt;" Usage="iExpressRouteCircuitsOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, circuitName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fed60-148">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fed60-148">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="fed60-149">回路の名前。</span><span class="sxs-lookup"><span data-stu-id="fed60-149">The name of the circuit.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fed60-150">作成または更新の express route 回線操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="fed60-150">Parameters supplied to the create or update express route circuit operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fed60-151">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="fed60-151">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fed60-152">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fed60-152">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fed60-153">作成するか、express route 回線を更新します。</span><span class="sxs-lookup"><span data-stu-id="fed60-153">Creates or updates an express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fed60-154">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fed60-154">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="fed60-155">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fed60-155">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fed60-156">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fed60-156">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string circuitName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string circuitName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iExpressRouteCircuitsOperations.DeleteWithHttpMessagesAsync (resourceGroupName, circuitName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fed60-157">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fed60-157">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="fed60-158">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="fed60-158">The name of the express route circuit.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fed60-159">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="fed60-159">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fed60-160">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fed60-160">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fed60-161">指定の express route 回線を削除します。</span><span class="sxs-lookup"><span data-stu-id="fed60-161">Deletes the specified express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fed60-162">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fed60-162">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fed60-163">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fed60-163">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPeeringStatsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitStatsInner&gt;&gt; GetPeeringStatsWithHttpMessagesAsync (string resourceGroupName, string circuitName, string peeringName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitStatsInner&gt;&gt; GetPeeringStatsWithHttpMessagesAsync(string resourceGroupName, string circuitName, string peeringName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations.GetPeeringStatsWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetPeeringStatsWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitStatsInner&gt;&gt;" Usage="iExpressRouteCircuitsOperations.GetPeeringStatsWithHttpMessagesAsync (resourceGroupName, circuitName, peeringName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitStatsInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fed60-164">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fed60-164">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="fed60-165">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="fed60-165">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="fed60-166">ピアリングの名前。</span><span class="sxs-lookup"><span data-stu-id="fed60-166">The name of the peering.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fed60-167">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="fed60-167">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fed60-168">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fed60-168">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fed60-169">リソース グループで、express route 回線からすべての統計情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="fed60-169">Gets all stats from an express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fed60-170">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fed60-170">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="fed60-171">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fed60-171">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fed60-172">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fed60-172">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetStatsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitStatsInner&gt;&gt; GetStatsWithHttpMessagesAsync (string resourceGroupName, string circuitName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitStatsInner&gt;&gt; GetStatsWithHttpMessagesAsync(string resourceGroupName, string circuitName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations.GetStatsWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetStatsWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitStatsInner&gt;&gt;" Usage="iExpressRouteCircuitsOperations.GetStatsWithHttpMessagesAsync (resourceGroupName, circuitName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitStatsInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fed60-173">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fed60-173">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="fed60-174">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="fed60-174">The name of the express route circuit.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fed60-175">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="fed60-175">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fed60-176">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fed60-176">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fed60-177">リソース グループで、express route 回線からすべての統計情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="fed60-177">Gets all the stats from an express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fed60-178">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fed60-178">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="fed60-179">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fed60-179">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fed60-180">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fed60-180">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string circuitName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string circuitName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt;" Usage="iExpressRouteCircuitsOperations.GetWithHttpMessagesAsync (resourceGroupName, circuitName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fed60-181">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fed60-181">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="fed60-182">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="fed60-182">The name of express route circuit.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fed60-183">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="fed60-183">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fed60-184">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fed60-184">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fed60-185">指定の express route 回線に関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="fed60-185">Gets information about the specified express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fed60-186">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fed60-186">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="fed60-187">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fed60-187">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fed60-188">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fed60-188">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListAllNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt;&gt; ListAllNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt;&gt; ListAllNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations.ListAllNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAllNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt;&gt;" Usage="iExpressRouteCircuitsOperations.ListAllNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="fed60-189">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="fed60-189">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fed60-190">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="fed60-190">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fed60-191">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fed60-191">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fed60-192">サブスクリプションのすべての express route 回線を取得します。</span><span class="sxs-lookup"><span data-stu-id="fed60-192">Gets all the express route circuits in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fed60-193">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fed60-193">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="fed60-194">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fed60-194">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fed60-195">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fed60-195">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListAllWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt;&gt; ListAllWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt;&gt; ListAllWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations.ListAllWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAllWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt;&gt;" Usage="iExpressRouteCircuitsOperations.ListAllWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="fed60-196">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="fed60-196">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fed60-197">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fed60-197">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fed60-198">サブスクリプションのすべての express route 回線を取得します。</span><span class="sxs-lookup"><span data-stu-id="fed60-198">Gets all the express route circuits in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fed60-199">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fed60-199">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="fed60-200">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fed60-200">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fed60-201">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fed60-201">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListArpTableWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsArpTableListResultInner&gt;&gt; ListArpTableWithHttpMessagesAsync (string resourceGroupName, string circuitName, string peeringName, string devicePath, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsArpTableListResultInner&gt;&gt; ListArpTableWithHttpMessagesAsync(string resourceGroupName, string circuitName, string peeringName, string devicePath, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations.ListArpTableWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListArpTableWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsArpTableListResultInner&gt;&gt;" Usage="iExpressRouteCircuitsOperations.ListArpTableWithHttpMessagesAsync (resourceGroupName, circuitName, peeringName, devicePath, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsArpTableListResultInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="devicePath" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fed60-202">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fed60-202">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="fed60-203">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="fed60-203">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="fed60-204">ピアリングの名前。</span><span class="sxs-lookup"><span data-stu-id="fed60-204">The name of the peering.</span></span>
            </param>
        <param name="devicePath">
            <span data-ttu-id="fed60-205">デバイスのパス。</span><span class="sxs-lookup"><span data-stu-id="fed60-205">The path of the device.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fed60-206">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="fed60-206">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fed60-207">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fed60-207">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fed60-208">リソース グループ内の express route 回線に関連付けられている現在の提供の ARP テーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="fed60-208">Gets the currently advertised ARP table associated with the express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fed60-209">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fed60-209">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="fed60-210">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fed60-210">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fed60-211">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fed60-211">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations.ListNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt;&gt;" Usage="iExpressRouteCircuitsOperations.ListNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="fed60-212">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="fed60-212">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fed60-213">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="fed60-213">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fed60-214">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fed60-214">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fed60-215">リソース グループ内のすべての express route 回線を取得します。</span><span class="sxs-lookup"><span data-stu-id="fed60-215">Gets all the express route circuits in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fed60-216">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fed60-216">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="fed60-217">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fed60-217">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fed60-218">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fed60-218">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListRoutesTableSummaryWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsRoutesTableSummaryListResultInner&gt;&gt; ListRoutesTableSummaryWithHttpMessagesAsync (string resourceGroupName, string circuitName, string peeringName, string devicePath, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsRoutesTableSummaryListResultInner&gt;&gt; ListRoutesTableSummaryWithHttpMessagesAsync(string resourceGroupName, string circuitName, string peeringName, string devicePath, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations.ListRoutesTableSummaryWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListRoutesTableSummaryWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsRoutesTableSummaryListResultInner&gt;&gt;" Usage="iExpressRouteCircuitsOperations.ListRoutesTableSummaryWithHttpMessagesAsync (resourceGroupName, circuitName, peeringName, devicePath, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsRoutesTableSummaryListResultInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="devicePath" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fed60-219">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fed60-219">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="fed60-220">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="fed60-220">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="fed60-221">ピアリングの名前。</span><span class="sxs-lookup"><span data-stu-id="fed60-221">The name of the peering.</span></span>
            </param>
        <param name="devicePath">
            <span data-ttu-id="fed60-222">デバイスのパス。</span><span class="sxs-lookup"><span data-stu-id="fed60-222">The path of the device.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fed60-223">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="fed60-223">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fed60-224">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fed60-224">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fed60-225">リソース グループ内の express route 回線に関連付けられている概要現在アドバタイズされたルート テーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="fed60-225">Gets the currently advertised routes table summary associated with the express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fed60-226">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fed60-226">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="fed60-227">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fed60-227">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fed60-228">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fed60-228">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListRoutesTableWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsRoutesTableListResultInner&gt;&gt; ListRoutesTableWithHttpMessagesAsync (string resourceGroupName, string circuitName, string peeringName, string devicePath, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsRoutesTableListResultInner&gt;&gt; ListRoutesTableWithHttpMessagesAsync(string resourceGroupName, string circuitName, string peeringName, string devicePath, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations.ListRoutesTableWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListRoutesTableWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsRoutesTableListResultInner&gt;&gt;" Usage="iExpressRouteCircuitsOperations.ListRoutesTableWithHttpMessagesAsync (resourceGroupName, circuitName, peeringName, devicePath, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsRoutesTableListResultInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="devicePath" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fed60-229">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fed60-229">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="fed60-230">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="fed60-230">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="fed60-231">ピアリングの名前。</span><span class="sxs-lookup"><span data-stu-id="fed60-231">The name of the peering.</span></span>
            </param>
        <param name="devicePath">
            <span data-ttu-id="fed60-232">デバイスのパス。</span><span class="sxs-lookup"><span data-stu-id="fed60-232">The path of the device.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fed60-233">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="fed60-233">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fed60-234">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fed60-234">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fed60-235">リソース グループ内の express route 回線に関連付けられている現在アドバタイズされたルート テーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="fed60-235">Gets the currently advertised routes table associated with the express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fed60-236">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fed60-236">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="fed60-237">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fed60-237">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fed60-238">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fed60-238">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt;&gt; ListWithHttpMessagesAsync (string resourceGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt;&gt; ListWithHttpMessagesAsync(string resourceGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations.ListWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt;&gt;" Usage="iExpressRouteCircuitsOperations.ListWithHttpMessagesAsync (resourceGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fed60-239">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fed60-239">The name of the resource group.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fed60-240">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="fed60-240">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fed60-241">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fed60-241">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fed60-242">リソース グループ内のすべての express route 回線を取得します。</span><span class="sxs-lookup"><span data-stu-id="fed60-242">Gets all the express route circuits in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fed60-243">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fed60-243">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="fed60-244">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fed60-244">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fed60-245">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fed60-245">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>