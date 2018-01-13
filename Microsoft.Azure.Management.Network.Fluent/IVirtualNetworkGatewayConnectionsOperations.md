<Type Name="IVirtualNetworkGatewayConnectionsOperations" FullName="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations">
  <TypeSignature Language="C#" Value="public interface IVirtualNetworkGatewayConnectionsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IVirtualNetworkGatewayConnectionsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IVirtualNetworkGatewayConnectionsOperations" />
  <TypeSignature Language="F#" Value="type IVirtualNetworkGatewayConnectionsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9906e-101">VirtualNetworkGatewayConnectionsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="9906e-101">VirtualNetworkGatewayConnectionsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string virtualNetworkGatewayConnectionName, Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string virtualNetworkGatewayConnectionName, class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations.BeginCreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt;&gt;" Usage="iVirtualNetworkGatewayConnectionsOperations.BeginCreateOrUpdateWithHttpMessagesAsync (resourceGroupName, virtualNetworkGatewayConnectionName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="9906e-102">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9906e-102">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            <span data-ttu-id="9906e-103">仮想ネットワーク ゲートウェイの接続の名前。</span><span class="sxs-lookup"><span data-stu-id="9906e-103">The name of the virtual network gateway connection.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="9906e-104">パラメーターが作成または更新仮想ネットワーク ゲートウェイの接続操作を指定します。</span><span class="sxs-lookup"><span data-stu-id="9906e-104">Parameters supplied to the create or update virtual network gateway connection operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="9906e-105">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="9906e-105">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9906e-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9906e-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9906e-107">作成するか、指定されたリソース グループ内の仮想ネットワーク ゲートウェイ接続を更新します。</span><span class="sxs-lookup"><span data-stu-id="9906e-107">Creates or updates a virtual network gateway connection in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="9906e-108">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9906e-108">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="9906e-109">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9906e-109">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9906e-110">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9906e-110">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync (string resourceGroupName, string virtualNetworkGatewayConnectionName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync(string resourceGroupName, string virtualNetworkGatewayConnectionName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations.BeginDeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iVirtualNetworkGatewayConnectionsOperations.BeginDeleteWithHttpMessagesAsync (resourceGroupName, virtualNetworkGatewayConnectionName, customHeaders, cancellationToken)" />
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
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="9906e-111">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9906e-111">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            <span data-ttu-id="9906e-112">仮想ネットワーク ゲートウェイの接続の名前。</span><span class="sxs-lookup"><span data-stu-id="9906e-112">The name of the virtual network gateway connection.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="9906e-113">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="9906e-113">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9906e-114">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9906e-114">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9906e-115">指定された仮想ネットワーク ゲートウェイの接続を削除します。</span><span class="sxs-lookup"><span data-stu-id="9906e-115">Deletes the specified virtual network Gateway connection.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="9906e-116">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9906e-116">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9906e-117">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9906e-117">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginResetSharedKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectionResetSharedKeyInner&gt;&gt; BeginResetSharedKeyWithHttpMessagesAsync (string resourceGroupName, string virtualNetworkGatewayConnectionName, int keyLength, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ConnectionResetSharedKeyInner&gt;&gt; BeginResetSharedKeyWithHttpMessagesAsync(string resourceGroupName, string virtualNetworkGatewayConnectionName, int32 keyLength, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations.BeginResetSharedKeyWithHttpMessagesAsync(System.String,System.String,System.Int32,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginResetSharedKeyWithHttpMessagesAsync : string * string * int * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectionResetSharedKeyInner&gt;&gt;" Usage="iVirtualNetworkGatewayConnectionsOperations.BeginResetSharedKeyWithHttpMessagesAsync (resourceGroupName, virtualNetworkGatewayConnectionName, keyLength, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectionResetSharedKeyInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="keyLength" Type="System.Int32" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="9906e-118">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9906e-118">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            <span data-ttu-id="9906e-119">仮想ネットワーク ゲートウェイの接続は、共有キーの名前をリセットします。</span><span class="sxs-lookup"><span data-stu-id="9906e-119">The virtual network gateway connection reset shared key Name.</span></span>
            </param>
        <param name="keyLength">
            <span data-ttu-id="9906e-120">共有キーの長さをリセットする仮想ネットワーク接続は、1 と 128 の間で必要があります。</span><span class="sxs-lookup"><span data-stu-id="9906e-120">The virtual network connection reset shared key length, should between 1 and 128.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="9906e-121">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="9906e-121">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9906e-122">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9906e-122">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9906e-123">VirtualNetworkGatewayConnectionResetSharedKey 操作は、指定されたリソース グループ リソース プロバイダーのネットワーク経由で渡された仮想ネットワーク ゲートウェイの接続の仮想ネットワーク ゲートウェイ接続共有キーをリセットします。</span><span class="sxs-lookup"><span data-stu-id="9906e-123">The VirtualNetworkGatewayConnectionResetSharedKey operation resets the virtual network gateway connection shared key for passed virtual network gateway connection in the specified resource group through Network resource provider.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="9906e-124">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9906e-124">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="9906e-125">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9906e-125">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9906e-126">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9906e-126">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginSetSharedKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectionSharedKeyInner&gt;&gt; BeginSetSharedKeyWithHttpMessagesAsync (string resourceGroupName, string virtualNetworkGatewayConnectionName, string value, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ConnectionSharedKeyInner&gt;&gt; BeginSetSharedKeyWithHttpMessagesAsync(string resourceGroupName, string virtualNetworkGatewayConnectionName, string value, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations.BeginSetSharedKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginSetSharedKeyWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectionSharedKeyInner&gt;&gt;" Usage="iVirtualNetworkGatewayConnectionsOperations.BeginSetSharedKeyWithHttpMessagesAsync (resourceGroupName, virtualNetworkGatewayConnectionName, value, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectionSharedKeyInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="9906e-127">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9906e-127">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            <span data-ttu-id="9906e-128">仮想ネットワーク ゲートウェイの接続名です。</span><span class="sxs-lookup"><span data-stu-id="9906e-128">The virtual network gateway connection name.</span></span>
            </param>
        <param name="value">
            <span data-ttu-id="9906e-129">仮想ネットワーク接続では、キーの値を共有します。</span><span class="sxs-lookup"><span data-stu-id="9906e-129">The virtual network connection shared key value.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="9906e-130">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="9906e-130">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9906e-131">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9906e-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9906e-132">VirtualNetworkGatewayConnectionSharedKey の Put 操作では、指定されたリソース グループ リソース プロバイダーのネットワーク経由で渡された仮想ネットワーク ゲートウェイの接続の仮想ネットワーク ゲートウェイ接続共有キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="9906e-132">The Put VirtualNetworkGatewayConnectionSharedKey operation sets the virtual network gateway connection shared key for passed virtual network gateway connection in the specified resource group through Network resource provider.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="9906e-133">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9906e-133">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="9906e-134">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9906e-134">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9906e-135">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9906e-135">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string virtualNetworkGatewayConnectionName, Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string virtualNetworkGatewayConnectionName, class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt;&gt;" Usage="iVirtualNetworkGatewayConnectionsOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, virtualNetworkGatewayConnectionName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="9906e-136">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9906e-136">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            <span data-ttu-id="9906e-137">仮想ネットワーク ゲートウェイの接続の名前。</span><span class="sxs-lookup"><span data-stu-id="9906e-137">The name of the virtual network gateway connection.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="9906e-138">パラメーターが作成または更新仮想ネットワーク ゲートウェイの接続操作を指定します。</span><span class="sxs-lookup"><span data-stu-id="9906e-138">Parameters supplied to the create or update virtual network gateway connection operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="9906e-139">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="9906e-139">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9906e-140">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9906e-140">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9906e-141">作成するか、指定されたリソース グループ内の仮想ネットワーク ゲートウェイ接続を更新します。</span><span class="sxs-lookup"><span data-stu-id="9906e-141">Creates or updates a virtual network gateway connection in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="9906e-142">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9906e-142">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="9906e-143">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9906e-143">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9906e-144">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9906e-144">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string virtualNetworkGatewayConnectionName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string virtualNetworkGatewayConnectionName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iVirtualNetworkGatewayConnectionsOperations.DeleteWithHttpMessagesAsync (resourceGroupName, virtualNetworkGatewayConnectionName, customHeaders, cancellationToken)" />
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
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="9906e-145">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9906e-145">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            <span data-ttu-id="9906e-146">仮想ネットワーク ゲートウェイの接続の名前。</span><span class="sxs-lookup"><span data-stu-id="9906e-146">The name of the virtual network gateway connection.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="9906e-147">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="9906e-147">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9906e-148">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9906e-148">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9906e-149">指定された仮想ネットワーク ゲートウェイの接続を削除します。</span><span class="sxs-lookup"><span data-stu-id="9906e-149">Deletes the specified virtual network Gateway connection.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="9906e-150">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9906e-150">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9906e-151">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9906e-151">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetSharedKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectionSharedKeyInner&gt;&gt; GetSharedKeyWithHttpMessagesAsync (string resourceGroupName, string virtualNetworkGatewayConnectionName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ConnectionSharedKeyInner&gt;&gt; GetSharedKeyWithHttpMessagesAsync(string resourceGroupName, string virtualNetworkGatewayConnectionName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations.GetSharedKeyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSharedKeyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectionSharedKeyInner&gt;&gt;" Usage="iVirtualNetworkGatewayConnectionsOperations.GetSharedKeyWithHttpMessagesAsync (resourceGroupName, virtualNetworkGatewayConnectionName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectionSharedKeyInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="9906e-152">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9906e-152">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            <span data-ttu-id="9906e-153">仮想ネットワーク ゲートウェイの接続は、キー名を共有します。</span><span class="sxs-lookup"><span data-stu-id="9906e-153">The virtual network gateway connection shared key name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="9906e-154">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="9906e-154">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9906e-155">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9906e-155">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9906e-156">VirtualNetworkGatewayConnectionSharedKey の Get 操作では、ネットワーク リソース プロバイダーによって指定された仮想ネットワーク ゲートウェイ接続共有キーに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="9906e-156">The Get VirtualNetworkGatewayConnectionSharedKey operation retrieves information about the specified virtual network gateway connection shared key through Network resource provider.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="9906e-157">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9906e-157">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="9906e-158">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9906e-158">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9906e-159">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9906e-159">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string virtualNetworkGatewayConnectionName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string virtualNetworkGatewayConnectionName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt;&gt;" Usage="iVirtualNetworkGatewayConnectionsOperations.GetWithHttpMessagesAsync (resourceGroupName, virtualNetworkGatewayConnectionName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="9906e-160">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9906e-160">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            <span data-ttu-id="9906e-161">仮想ネットワーク ゲートウェイの接続の名前。</span><span class="sxs-lookup"><span data-stu-id="9906e-161">The name of the virtual network gateway connection.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="9906e-162">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="9906e-162">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9906e-163">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9906e-163">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9906e-164">リソース グループによって指定された仮想ネットワーク ゲートウェイの接続を取得します。</span><span class="sxs-lookup"><span data-stu-id="9906e-164">Gets the specified virtual network gateway connection by resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="9906e-165">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9906e-165">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="9906e-166">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9906e-166">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9906e-167">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9906e-167">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt;&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt;&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations.ListNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt;&gt;&gt;" Usage="iVirtualNetworkGatewayConnectionsOperations.ListNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="9906e-168">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="9906e-168">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="9906e-169">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="9906e-169">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9906e-170">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9906e-170">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9906e-171">リスト VirtualNetworkGatewayConnections 操作は、すべての仮想ネットワーク ゲートウェイ接続の作成を取得します。</span><span class="sxs-lookup"><span data-stu-id="9906e-171">The List VirtualNetworkGatewayConnections operation retrieves all the virtual network gateways connections created.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="9906e-172">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9906e-172">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="9906e-173">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9906e-173">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9906e-174">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9906e-174">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt;&gt;&gt; ListWithHttpMessagesAsync (string resourceGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt;&gt;&gt; ListWithHttpMessagesAsync(string resourceGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations.ListWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt;&gt;&gt;" Usage="iVirtualNetworkGatewayConnectionsOperations.ListWithHttpMessagesAsync (resourceGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="9906e-175">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9906e-175">The name of the resource group.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="9906e-176">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="9906e-176">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9906e-177">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9906e-177">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9906e-178">リスト VirtualNetworkGatewayConnections 操作は、すべての仮想ネットワーク ゲートウェイ接続の作成を取得します。</span><span class="sxs-lookup"><span data-stu-id="9906e-178">The List VirtualNetworkGatewayConnections operation retrieves all the virtual network gateways connections created.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="9906e-179">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9906e-179">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="9906e-180">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9906e-180">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9906e-181">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9906e-181">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ResetSharedKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectionResetSharedKeyInner&gt;&gt; ResetSharedKeyWithHttpMessagesAsync (string resourceGroupName, string virtualNetworkGatewayConnectionName, int keyLength, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ConnectionResetSharedKeyInner&gt;&gt; ResetSharedKeyWithHttpMessagesAsync(string resourceGroupName, string virtualNetworkGatewayConnectionName, int32 keyLength, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations.ResetSharedKeyWithHttpMessagesAsync(System.String,System.String,System.Int32,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ResetSharedKeyWithHttpMessagesAsync : string * string * int * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectionResetSharedKeyInner&gt;&gt;" Usage="iVirtualNetworkGatewayConnectionsOperations.ResetSharedKeyWithHttpMessagesAsync (resourceGroupName, virtualNetworkGatewayConnectionName, keyLength, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectionResetSharedKeyInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="keyLength" Type="System.Int32" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="9906e-182">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9906e-182">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            <span data-ttu-id="9906e-183">仮想ネットワーク ゲートウェイの接続は、共有キーの名前をリセットします。</span><span class="sxs-lookup"><span data-stu-id="9906e-183">The virtual network gateway connection reset shared key Name.</span></span>
            </param>
        <param name="keyLength">
            <span data-ttu-id="9906e-184">共有キーの長さをリセットする仮想ネットワーク接続は、1 と 128 の間で必要があります。</span><span class="sxs-lookup"><span data-stu-id="9906e-184">The virtual network connection reset shared key length, should between 1 and 128.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="9906e-185">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="9906e-185">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9906e-186">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9906e-186">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9906e-187">VirtualNetworkGatewayConnectionResetSharedKey 操作は、指定されたリソース グループ リソース プロバイダーのネットワーク経由で渡された仮想ネットワーク ゲートウェイの接続の仮想ネットワーク ゲートウェイ接続共有キーをリセットします。</span><span class="sxs-lookup"><span data-stu-id="9906e-187">The VirtualNetworkGatewayConnectionResetSharedKey operation resets the virtual network gateway connection shared key for passed virtual network gateway connection in the specified resource group through Network resource provider.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="9906e-188">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9906e-188">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="9906e-189">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9906e-189">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9906e-190">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9906e-190">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="SetSharedKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectionSharedKeyInner&gt;&gt; SetSharedKeyWithHttpMessagesAsync (string resourceGroupName, string virtualNetworkGatewayConnectionName, string value, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ConnectionSharedKeyInner&gt;&gt; SetSharedKeyWithHttpMessagesAsync(string resourceGroupName, string virtualNetworkGatewayConnectionName, string value, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations.SetSharedKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetSharedKeyWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectionSharedKeyInner&gt;&gt;" Usage="iVirtualNetworkGatewayConnectionsOperations.SetSharedKeyWithHttpMessagesAsync (resourceGroupName, virtualNetworkGatewayConnectionName, value, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectionSharedKeyInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="9906e-191">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9906e-191">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            <span data-ttu-id="9906e-192">仮想ネットワーク ゲートウェイの接続名です。</span><span class="sxs-lookup"><span data-stu-id="9906e-192">The virtual network gateway connection name.</span></span>
            </param>
        <param name="value">
            <span data-ttu-id="9906e-193">仮想ネットワーク接続では、キーの値を共有します。</span><span class="sxs-lookup"><span data-stu-id="9906e-193">The virtual network connection shared key value.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="9906e-194">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="9906e-194">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9906e-195">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9906e-195">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9906e-196">VirtualNetworkGatewayConnectionSharedKey の Put 操作では、指定されたリソース グループ リソース プロバイダーのネットワーク経由で渡された仮想ネットワーク ゲートウェイの接続の仮想ネットワーク ゲートウェイ接続共有キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="9906e-196">The Put VirtualNetworkGatewayConnectionSharedKey operation sets the virtual network gateway connection shared key for passed virtual network gateway connection in the specified resource group through Network resource provider.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="9906e-197">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9906e-197">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="9906e-198">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9906e-198">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9906e-199">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9906e-199">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>