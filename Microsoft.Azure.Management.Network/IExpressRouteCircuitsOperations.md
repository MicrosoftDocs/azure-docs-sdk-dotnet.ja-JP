<Type Name="IExpressRouteCircuitsOperations" FullName="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations">
  <TypeSignature Language="C#" Value="public interface IExpressRouteCircuitsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IExpressRouteCircuitsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IExpressRouteCircuitsOperations" />
  <TypeSignature Language="F#" Value="type IExpressRouteCircuitsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e7239-101">ExpressRouteCircuitsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="e7239-101">ExpressRouteCircuitsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string circuitName, Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string circuitName, class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations.BeginCreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt;" Usage="iExpressRouteCircuitsOperations.BeginCreateOrUpdateWithHttpMessagesAsync (resourceGroupName, circuitName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="e7239-102">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="e7239-102">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="e7239-103">回路の名前。</span><span class="sxs-lookup"><span data-stu-id="e7239-103">The name of the circuit.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e7239-104">作成または更新の express route 回線操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="e7239-104">Parameters supplied to the create or update express route circuit operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e7239-105">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="e7239-105">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e7239-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e7239-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e7239-107">作成するか、express route 回線を更新します。</span><span class="sxs-lookup"><span data-stu-id="e7239-107">Creates or updates an express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e7239-108">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-108">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e7239-109">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-109">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e7239-110">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-110">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync (string resourceGroupName, string circuitName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync(string resourceGroupName, string circuitName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations.BeginDeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iExpressRouteCircuitsOperations.BeginDeleteWithHttpMessagesAsync (resourceGroupName, circuitName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="e7239-111">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="e7239-111">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="e7239-112">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="e7239-112">The name of the express route circuit.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e7239-113">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="e7239-113">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e7239-114">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e7239-114">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e7239-115">指定の express route 回線を削除します。</span><span class="sxs-lookup"><span data-stu-id="e7239-115">Deletes the specified express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e7239-116">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-116">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e7239-117">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-117">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginListArpTableWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult&gt;&gt; BeginListArpTableWithHttpMessagesAsync (string resourceGroupName, string circuitName, string peeringName, string devicePath, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult&gt;&gt; BeginListArpTableWithHttpMessagesAsync(string resourceGroupName, string circuitName, string peeringName, string devicePath, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations.BeginListArpTableWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginListArpTableWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult&gt;&gt;" Usage="iExpressRouteCircuitsOperations.BeginListArpTableWithHttpMessagesAsync (resourceGroupName, circuitName, peeringName, devicePath, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult&gt;&gt;</ReturnType>
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
            <span data-ttu-id="e7239-118">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="e7239-118">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="e7239-119">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="e7239-119">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="e7239-120">ピアリングの名前。</span><span class="sxs-lookup"><span data-stu-id="e7239-120">The name of the peering.</span></span>
            </param>
        <param name="devicePath">
            <span data-ttu-id="e7239-121">デバイスのパス。</span><span class="sxs-lookup"><span data-stu-id="e7239-121">The path of the device.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e7239-122">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="e7239-122">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e7239-123">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e7239-123">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e7239-124">リソース グループ内の express route 回線に関連付けられている現在の提供の ARP テーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="e7239-124">Gets the currently advertised ARP table associated with the express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e7239-125">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-125">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e7239-126">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-126">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e7239-127">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-127">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginListRoutesTableSummaryWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult&gt;&gt; BeginListRoutesTableSummaryWithHttpMessagesAsync (string resourceGroupName, string circuitName, string peeringName, string devicePath, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult&gt;&gt; BeginListRoutesTableSummaryWithHttpMessagesAsync(string resourceGroupName, string circuitName, string peeringName, string devicePath, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations.BeginListRoutesTableSummaryWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginListRoutesTableSummaryWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult&gt;&gt;" Usage="iExpressRouteCircuitsOperations.BeginListRoutesTableSummaryWithHttpMessagesAsync (resourceGroupName, circuitName, peeringName, devicePath, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult&gt;&gt;</ReturnType>
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
            <span data-ttu-id="e7239-128">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="e7239-128">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="e7239-129">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="e7239-129">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="e7239-130">ピアリングの名前。</span><span class="sxs-lookup"><span data-stu-id="e7239-130">The name of the peering.</span></span>
            </param>
        <param name="devicePath">
            <span data-ttu-id="e7239-131">デバイスのパス。</span><span class="sxs-lookup"><span data-stu-id="e7239-131">The path of the device.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e7239-132">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="e7239-132">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e7239-133">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e7239-133">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e7239-134">リソース グループ内の express route 回線に関連付けられている概要現在アドバタイズされたルート テーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="e7239-134">Gets the currently advertised routes table summary associated with the express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e7239-135">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-135">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e7239-136">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-136">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e7239-137">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-137">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginListRoutesTableWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult&gt;&gt; BeginListRoutesTableWithHttpMessagesAsync (string resourceGroupName, string circuitName, string peeringName, string devicePath, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult&gt;&gt; BeginListRoutesTableWithHttpMessagesAsync(string resourceGroupName, string circuitName, string peeringName, string devicePath, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations.BeginListRoutesTableWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginListRoutesTableWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult&gt;&gt;" Usage="iExpressRouteCircuitsOperations.BeginListRoutesTableWithHttpMessagesAsync (resourceGroupName, circuitName, peeringName, devicePath, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult&gt;&gt;</ReturnType>
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
            <span data-ttu-id="e7239-138">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="e7239-138">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="e7239-139">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="e7239-139">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="e7239-140">ピアリングの名前。</span><span class="sxs-lookup"><span data-stu-id="e7239-140">The name of the peering.</span></span>
            </param>
        <param name="devicePath">
            <span data-ttu-id="e7239-141">デバイスのパス。</span><span class="sxs-lookup"><span data-stu-id="e7239-141">The path of the device.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e7239-142">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="e7239-142">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e7239-143">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e7239-143">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e7239-144">リソース グループ内の express route 回線に関連付けられている現在アドバタイズされたルート テーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="e7239-144">Gets the currently advertised routes table associated with the express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e7239-145">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-145">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e7239-146">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-146">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e7239-147">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-147">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateTagsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt; BeginUpdateTagsWithHttpMessagesAsync (string resourceGroupName, string circuitName, Microsoft.Azure.Management.Network.Models.TagsObject parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt; BeginUpdateTagsWithHttpMessagesAsync(string resourceGroupName, string circuitName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations.BeginUpdateTagsWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginUpdateTagsWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Models.TagsObject * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt;" Usage="iExpressRouteCircuitsOperations.BeginUpdateTagsWithHttpMessagesAsync (resourceGroupName, circuitName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="e7239-148">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="e7239-148">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="e7239-149">回路の名前。</span><span class="sxs-lookup"><span data-stu-id="e7239-149">The name of the circuit.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e7239-150">Express route 回線タグを更新する指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="e7239-150">Parameters supplied to update express route circuit tags.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e7239-151">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="e7239-151">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e7239-152">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e7239-152">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e7239-153">Express route 回線タグを更新します。</span><span class="sxs-lookup"><span data-stu-id="e7239-153">Updates an express route circuit tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e7239-154">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-154">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e7239-155">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-155">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e7239-156">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-156">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string circuitName, Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string circuitName, class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt;" Usage="iExpressRouteCircuitsOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, circuitName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="e7239-157">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="e7239-157">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="e7239-158">回路の名前。</span><span class="sxs-lookup"><span data-stu-id="e7239-158">The name of the circuit.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e7239-159">作成または更新の express route 回線操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="e7239-159">Parameters supplied to the create or update express route circuit operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e7239-160">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="e7239-160">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e7239-161">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e7239-161">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e7239-162">作成するか、express route 回線を更新します。</span><span class="sxs-lookup"><span data-stu-id="e7239-162">Creates or updates an express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e7239-163">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-163">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e7239-164">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-164">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e7239-165">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-165">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string circuitName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string circuitName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iExpressRouteCircuitsOperations.DeleteWithHttpMessagesAsync (resourceGroupName, circuitName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="e7239-166">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="e7239-166">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="e7239-167">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="e7239-167">The name of the express route circuit.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e7239-168">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="e7239-168">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e7239-169">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e7239-169">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e7239-170">指定の express route 回線を削除します。</span><span class="sxs-lookup"><span data-stu-id="e7239-170">Deletes the specified express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e7239-171">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-171">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e7239-172">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-172">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPeeringStatsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats&gt;&gt; GetPeeringStatsWithHttpMessagesAsync (string resourceGroupName, string circuitName, string peeringName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats&gt;&gt; GetPeeringStatsWithHttpMessagesAsync(string resourceGroupName, string circuitName, string peeringName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations.GetPeeringStatsWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetPeeringStatsWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats&gt;&gt;" Usage="iExpressRouteCircuitsOperations.GetPeeringStatsWithHttpMessagesAsync (resourceGroupName, circuitName, peeringName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats&gt;&gt;</ReturnType>
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
            <span data-ttu-id="e7239-173">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="e7239-173">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="e7239-174">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="e7239-174">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="e7239-175">ピアリングの名前。</span><span class="sxs-lookup"><span data-stu-id="e7239-175">The name of the peering.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e7239-176">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="e7239-176">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e7239-177">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e7239-177">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e7239-178">リソース グループで、express route 回線からすべての統計情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="e7239-178">Gets all stats from an express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e7239-179">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-179">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e7239-180">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-180">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e7239-181">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-181">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetStatsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats&gt;&gt; GetStatsWithHttpMessagesAsync (string resourceGroupName, string circuitName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats&gt;&gt; GetStatsWithHttpMessagesAsync(string resourceGroupName, string circuitName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations.GetStatsWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetStatsWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats&gt;&gt;" Usage="iExpressRouteCircuitsOperations.GetStatsWithHttpMessagesAsync (resourceGroupName, circuitName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="e7239-182">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="e7239-182">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="e7239-183">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="e7239-183">The name of the express route circuit.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e7239-184">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="e7239-184">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e7239-185">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e7239-185">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e7239-186">リソース グループで、express route 回線からすべての統計情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="e7239-186">Gets all the stats from an express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e7239-187">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-187">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e7239-188">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-188">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e7239-189">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-189">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string circuitName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string circuitName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt;" Usage="iExpressRouteCircuitsOperations.GetWithHttpMessagesAsync (resourceGroupName, circuitName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="e7239-190">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="e7239-190">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="e7239-191">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="e7239-191">The name of express route circuit.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e7239-192">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="e7239-192">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e7239-193">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e7239-193">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e7239-194">指定の express route 回線に関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="e7239-194">Gets information about the specified express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e7239-195">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-195">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e7239-196">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-196">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e7239-197">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-197">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListAllNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt;&gt; ListAllNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt;&gt; ListAllNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations.ListAllNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAllNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt;&gt;" Usage="iExpressRouteCircuitsOperations.ListAllNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="e7239-198">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="e7239-198">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e7239-199">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="e7239-199">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e7239-200">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e7239-200">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e7239-201">サブスクリプションのすべての express route 回線を取得します。</span><span class="sxs-lookup"><span data-stu-id="e7239-201">Gets all the express route circuits in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e7239-202">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-202">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e7239-203">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-203">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e7239-204">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-204">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListAllWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt;&gt; ListAllWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt;&gt; ListAllWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations.ListAllWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAllWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt;&gt;" Usage="iExpressRouteCircuitsOperations.ListAllWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="e7239-205">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="e7239-205">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e7239-206">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e7239-206">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e7239-207">サブスクリプションのすべての express route 回線を取得します。</span><span class="sxs-lookup"><span data-stu-id="e7239-207">Gets all the express route circuits in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e7239-208">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-208">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e7239-209">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-209">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e7239-210">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-210">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListArpTableWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult&gt;&gt; ListArpTableWithHttpMessagesAsync (string resourceGroupName, string circuitName, string peeringName, string devicePath, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult&gt;&gt; ListArpTableWithHttpMessagesAsync(string resourceGroupName, string circuitName, string peeringName, string devicePath, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations.ListArpTableWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListArpTableWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult&gt;&gt;" Usage="iExpressRouteCircuitsOperations.ListArpTableWithHttpMessagesAsync (resourceGroupName, circuitName, peeringName, devicePath, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult&gt;&gt;</ReturnType>
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
            <span data-ttu-id="e7239-211">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="e7239-211">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="e7239-212">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="e7239-212">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="e7239-213">ピアリングの名前。</span><span class="sxs-lookup"><span data-stu-id="e7239-213">The name of the peering.</span></span>
            </param>
        <param name="devicePath">
            <span data-ttu-id="e7239-214">デバイスのパス。</span><span class="sxs-lookup"><span data-stu-id="e7239-214">The path of the device.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e7239-215">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="e7239-215">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e7239-216">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e7239-216">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e7239-217">リソース グループ内の express route 回線に関連付けられている現在の提供の ARP テーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="e7239-217">Gets the currently advertised ARP table associated with the express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e7239-218">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-218">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e7239-219">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-219">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e7239-220">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-220">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations.ListNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt;&gt;" Usage="iExpressRouteCircuitsOperations.ListNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="e7239-221">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="e7239-221">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e7239-222">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="e7239-222">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e7239-223">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e7239-223">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e7239-224">リソース グループ内のすべての express route 回線を取得します。</span><span class="sxs-lookup"><span data-stu-id="e7239-224">Gets all the express route circuits in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e7239-225">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-225">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e7239-226">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-226">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e7239-227">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-227">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListRoutesTableSummaryWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult&gt;&gt; ListRoutesTableSummaryWithHttpMessagesAsync (string resourceGroupName, string circuitName, string peeringName, string devicePath, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult&gt;&gt; ListRoutesTableSummaryWithHttpMessagesAsync(string resourceGroupName, string circuitName, string peeringName, string devicePath, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations.ListRoutesTableSummaryWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListRoutesTableSummaryWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult&gt;&gt;" Usage="iExpressRouteCircuitsOperations.ListRoutesTableSummaryWithHttpMessagesAsync (resourceGroupName, circuitName, peeringName, devicePath, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult&gt;&gt;</ReturnType>
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
            <span data-ttu-id="e7239-228">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="e7239-228">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="e7239-229">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="e7239-229">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="e7239-230">ピアリングの名前。</span><span class="sxs-lookup"><span data-stu-id="e7239-230">The name of the peering.</span></span>
            </param>
        <param name="devicePath">
            <span data-ttu-id="e7239-231">デバイスのパス。</span><span class="sxs-lookup"><span data-stu-id="e7239-231">The path of the device.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e7239-232">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="e7239-232">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e7239-233">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e7239-233">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e7239-234">リソース グループ内の express route 回線に関連付けられている概要現在アドバタイズされたルート テーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="e7239-234">Gets the currently advertised routes table summary associated with the express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e7239-235">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-235">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e7239-236">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-236">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e7239-237">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-237">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListRoutesTableWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult&gt;&gt; ListRoutesTableWithHttpMessagesAsync (string resourceGroupName, string circuitName, string peeringName, string devicePath, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult&gt;&gt; ListRoutesTableWithHttpMessagesAsync(string resourceGroupName, string circuitName, string peeringName, string devicePath, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations.ListRoutesTableWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListRoutesTableWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult&gt;&gt;" Usage="iExpressRouteCircuitsOperations.ListRoutesTableWithHttpMessagesAsync (resourceGroupName, circuitName, peeringName, devicePath, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult&gt;&gt;</ReturnType>
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
            <span data-ttu-id="e7239-238">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="e7239-238">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="e7239-239">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="e7239-239">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="e7239-240">ピアリングの名前。</span><span class="sxs-lookup"><span data-stu-id="e7239-240">The name of the peering.</span></span>
            </param>
        <param name="devicePath">
            <span data-ttu-id="e7239-241">デバイスのパス。</span><span class="sxs-lookup"><span data-stu-id="e7239-241">The path of the device.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e7239-242">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="e7239-242">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e7239-243">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e7239-243">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e7239-244">リソース グループ内の express route 回線に関連付けられている現在アドバタイズされたルート テーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="e7239-244">Gets the currently advertised routes table associated with the express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e7239-245">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-245">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e7239-246">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-246">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e7239-247">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-247">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt;&gt; ListWithHttpMessagesAsync (string resourceGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt;&gt; ListWithHttpMessagesAsync(string resourceGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations.ListWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt;&gt;" Usage="iExpressRouteCircuitsOperations.ListWithHttpMessagesAsync (resourceGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="e7239-248">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="e7239-248">The name of the resource group.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e7239-249">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="e7239-249">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e7239-250">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e7239-250">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e7239-251">リソース グループ内のすべての express route 回線を取得します。</span><span class="sxs-lookup"><span data-stu-id="e7239-251">Gets all the express route circuits in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e7239-252">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-252">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e7239-253">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-253">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e7239-254">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-254">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateTagsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt; UpdateTagsWithHttpMessagesAsync (string resourceGroupName, string circuitName, Microsoft.Azure.Management.Network.Models.TagsObject parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt; UpdateTagsWithHttpMessagesAsync(string resourceGroupName, string circuitName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations.UpdateTagsWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateTagsWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Models.TagsObject * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt;" Usage="iExpressRouteCircuitsOperations.UpdateTagsWithHttpMessagesAsync (resourceGroupName, circuitName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="e7239-255">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="e7239-255">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="e7239-256">回路の名前。</span><span class="sxs-lookup"><span data-stu-id="e7239-256">The name of the circuit.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e7239-257">Express route 回線タグを更新する指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="e7239-257">Parameters supplied to update express route circuit tags.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e7239-258">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="e7239-258">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e7239-259">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e7239-259">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e7239-260">Express route 回線タグを更新します。</span><span class="sxs-lookup"><span data-stu-id="e7239-260">Updates an express route circuit tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e7239-261">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-261">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e7239-262">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-262">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e7239-263">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e7239-263">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>