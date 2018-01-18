<Type Name="IVirtualNetworkGatewaysOperations" FullName="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations">
  <TypeSignature Language="C#" Value="public interface IVirtualNetworkGatewaysOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IVirtualNetworkGatewaysOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IVirtualNetworkGatewaysOperations" />
  <TypeSignature Language="F#" Value="type IVirtualNetworkGatewaysOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8f567-101">VirtualNetworkGatewaysOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="8f567-101">VirtualNetworkGatewaysOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations.BeginCreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;&gt;" Usage="iVirtualNetworkGatewaysOperations.BeginCreateOrUpdateWithHttpMessagesAsync (resourceGroupName, virtualNetworkGatewayName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="8f567-102">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8f567-102">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="8f567-103">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="8f567-103">The name of the virtual network gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="8f567-104">作成または更新の各仮想ネットワーク ゲートウェイの操作に渡されるパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="8f567-104">Parameters supplied to create or update virtual network gateway operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8f567-105">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8f567-105">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8f567-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8f567-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8f567-107">作成するか、指定されたリソース グループに仮想ネットワーク ゲートウェイを更新します。</span><span class="sxs-lookup"><span data-stu-id="8f567-107">Creates or updates a virtual network gateway in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="8f567-108">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8f567-108">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="8f567-109">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8f567-109">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8f567-110">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8f567-110">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync (string resourceGroupName, string virtualNetworkGatewayName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync(string resourceGroupName, string virtualNetworkGatewayName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations.BeginDeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iVirtualNetworkGatewaysOperations.BeginDeleteWithHttpMessagesAsync (resourceGroupName, virtualNetworkGatewayName, customHeaders, cancellationToken)" />
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
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="8f567-111">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8f567-111">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="8f567-112">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="8f567-112">The name of the virtual network gateway.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8f567-113">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8f567-113">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8f567-114">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8f567-114">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8f567-115">指定された仮想ネットワーク ゲートウェイを削除します。</span><span class="sxs-lookup"><span data-stu-id="8f567-115">Deletes the specified virtual network gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="8f567-116">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8f567-116">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8f567-117">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8f567-117">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginGeneratevpnclientpackageWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;string&gt;&gt; BeginGeneratevpnclientpackageWithHttpMessagesAsync (string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;string&gt;&gt; BeginGeneratevpnclientpackageWithHttpMessagesAsync(string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations.BeginGeneratevpnclientpackageWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginGeneratevpnclientpackageWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;string&gt;&gt;" Usage="iVirtualNetworkGatewaysOperations.BeginGeneratevpnclientpackageWithHttpMessagesAsync (resourceGroupName, virtualNetworkGatewayName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="virtualNetworkGatewayName">To be added.</param>
        <param name="parameters">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGenerateVpnProfileWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;string&gt;&gt; BeginGenerateVpnProfileWithHttpMessagesAsync (string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;string&gt;&gt; BeginGenerateVpnProfileWithHttpMessagesAsync(string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations.BeginGenerateVpnProfileWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginGenerateVpnProfileWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;string&gt;&gt;" Usage="iVirtualNetworkGatewaysOperations.BeginGenerateVpnProfileWithHttpMessagesAsync (resourceGroupName, virtualNetworkGatewayName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="virtualNetworkGatewayName">To be added.</param>
        <param name="parameters">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetAdvertisedRoutesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.GatewayRouteListResultInner&gt;&gt; BeginGetAdvertisedRoutesWithHttpMessagesAsync (string resourceGroupName, string virtualNetworkGatewayName, string peer, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.GatewayRouteListResultInner&gt;&gt; BeginGetAdvertisedRoutesWithHttpMessagesAsync(string resourceGroupName, string virtualNetworkGatewayName, string peer, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations.BeginGetAdvertisedRoutesWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetAdvertisedRoutesWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.GatewayRouteListResultInner&gt;&gt;" Usage="iVirtualNetworkGatewaysOperations.BeginGetAdvertisedRoutesWithHttpMessagesAsync (resourceGroupName, virtualNetworkGatewayName, peer, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.GatewayRouteListResultInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="peer" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="8f567-118">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8f567-118">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="8f567-119">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="8f567-119">The name of the virtual network gateway.</span></span>
            </param>
        <param name="peer">
            <span data-ttu-id="8f567-120">ピアの IP アドレス</span><span class="sxs-lookup"><span data-stu-id="8f567-120">The IP address of the peer</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8f567-121">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8f567-121">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8f567-122">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8f567-122">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8f567-123">この操作は、仮想ネットワーク ゲートウェイが、指定したピアにアドバタイズするルートの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="8f567-123">This operation retrieves a list of routes the virtual network gateway is advertising to the specified peer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="8f567-124">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8f567-124">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="8f567-125">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8f567-125">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8f567-126">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8f567-126">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginGetBgpPeerStatusWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.BgpPeerStatusListResultInner&gt;&gt; BeginGetBgpPeerStatusWithHttpMessagesAsync (string resourceGroupName, string virtualNetworkGatewayName, string peer = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.BgpPeerStatusListResultInner&gt;&gt; BeginGetBgpPeerStatusWithHttpMessagesAsync(string resourceGroupName, string virtualNetworkGatewayName, string peer, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations.BeginGetBgpPeerStatusWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetBgpPeerStatusWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.BgpPeerStatusListResultInner&gt;&gt;" Usage="iVirtualNetworkGatewaysOperations.BeginGetBgpPeerStatusWithHttpMessagesAsync (resourceGroupName, virtualNetworkGatewayName, peer, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.BgpPeerStatusListResultInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="peer" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="8f567-127">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8f567-127">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="8f567-128">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="8f567-128">The name of the virtual network gateway.</span></span>
            </param>
        <param name="peer">
            <span data-ttu-id="8f567-129">状態を取得するピアの IP アドレス。</span><span class="sxs-lookup"><span data-stu-id="8f567-129">The IP address of the peer to retrieve the status of.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8f567-130">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8f567-130">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8f567-131">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8f567-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8f567-132">GetBgpPeerStatus 操作では、すべての BGP ピアの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="8f567-132">The GetBgpPeerStatus operation retrieves the status of all BGP peers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="8f567-133">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8f567-133">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="8f567-134">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8f567-134">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8f567-135">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8f567-135">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginGetLearnedRoutesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.GatewayRouteListResultInner&gt;&gt; BeginGetLearnedRoutesWithHttpMessagesAsync (string resourceGroupName, string virtualNetworkGatewayName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.GatewayRouteListResultInner&gt;&gt; BeginGetLearnedRoutesWithHttpMessagesAsync(string resourceGroupName, string virtualNetworkGatewayName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations.BeginGetLearnedRoutesWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetLearnedRoutesWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.GatewayRouteListResultInner&gt;&gt;" Usage="iVirtualNetworkGatewaysOperations.BeginGetLearnedRoutesWithHttpMessagesAsync (resourceGroupName, virtualNetworkGatewayName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.GatewayRouteListResultInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="8f567-136">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8f567-136">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="8f567-137">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="8f567-137">The name of the virtual network gateway.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8f567-138">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8f567-138">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8f567-139">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8f567-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8f567-140">この操作では、仮想ネットワーク ゲートウェイが学習したルートの一覧を取得は、BGP ピアから学習したルートを含むです。</span><span class="sxs-lookup"><span data-stu-id="8f567-140">This operation retrieves a list of routes the virtual network gateway has learned, including routes learned from BGP peers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="8f567-141">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8f567-141">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="8f567-142">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8f567-142">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8f567-143">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8f567-143">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginResetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;&gt; BeginResetWithHttpMessagesAsync (string resourceGroupName, string virtualNetworkGatewayName, string gatewayVip = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;&gt; BeginResetWithHttpMessagesAsync(string resourceGroupName, string virtualNetworkGatewayName, string gatewayVip, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations.BeginResetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginResetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;&gt;" Usage="iVirtualNetworkGatewaysOperations.BeginResetWithHttpMessagesAsync (resourceGroupName, virtualNetworkGatewayName, gatewayVip, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="gatewayVip" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="8f567-144">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8f567-144">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="8f567-145">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="8f567-145">The name of the virtual network gateway.</span></span>
            </param>
        <param name="gatewayVip">
            <span data-ttu-id="8f567-146">仮想ネットワーク ゲートウェイの vip アドレスがアクティブ/アクティブ機能を有効にしているゲートウェイの開始のリセットを提供します。</span><span class="sxs-lookup"><span data-stu-id="8f567-146">Virtual network gateway vip address supplied to the begin reset of the active-active feature enabled gateway.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8f567-147">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8f567-147">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8f567-148">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8f567-148">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8f567-149">指定されたリソース グループ内の仮想ネットワーク ゲートウェイのプライマリをリセットします。</span><span class="sxs-lookup"><span data-stu-id="8f567-149">Resets the primary of the virtual network gateway in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="8f567-150">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8f567-150">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="8f567-151">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8f567-151">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8f567-152">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8f567-152">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;&gt;" Usage="iVirtualNetworkGatewaysOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, virtualNetworkGatewayName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="8f567-153">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8f567-153">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="8f567-154">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="8f567-154">The name of the virtual network gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="8f567-155">作成または更新の各仮想ネットワーク ゲートウェイの操作に渡されるパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="8f567-155">Parameters supplied to create or update virtual network gateway operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8f567-156">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8f567-156">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8f567-157">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8f567-157">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8f567-158">作成するか、指定されたリソース グループに仮想ネットワーク ゲートウェイを更新します。</span><span class="sxs-lookup"><span data-stu-id="8f567-158">Creates or updates a virtual network gateway in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="8f567-159">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8f567-159">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="8f567-160">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8f567-160">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8f567-161">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8f567-161">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string virtualNetworkGatewayName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string virtualNetworkGatewayName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iVirtualNetworkGatewaysOperations.DeleteWithHttpMessagesAsync (resourceGroupName, virtualNetworkGatewayName, customHeaders, cancellationToken)" />
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
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="8f567-162">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8f567-162">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="8f567-163">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="8f567-163">The name of the virtual network gateway.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8f567-164">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8f567-164">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8f567-165">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8f567-165">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8f567-166">指定された仮想ネットワーク ゲートウェイを削除します。</span><span class="sxs-lookup"><span data-stu-id="8f567-166">Deletes the specified virtual network gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="8f567-167">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8f567-167">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8f567-168">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8f567-168">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GeneratevpnclientpackageWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;string&gt;&gt; GeneratevpnclientpackageWithHttpMessagesAsync (string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;string&gt;&gt; GeneratevpnclientpackageWithHttpMessagesAsync(string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations.GeneratevpnclientpackageWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GeneratevpnclientpackageWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;string&gt;&gt;" Usage="iVirtualNetworkGatewaysOperations.GeneratevpnclientpackageWithHttpMessagesAsync (resourceGroupName, virtualNetworkGatewayName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="virtualNetworkGatewayName">To be added.</param>
        <param name="parameters">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateVpnProfileWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;string&gt;&gt; GenerateVpnProfileWithHttpMessagesAsync (string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;string&gt;&gt; GenerateVpnProfileWithHttpMessagesAsync(string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations.GenerateVpnProfileWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GenerateVpnProfileWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;string&gt;&gt;" Usage="iVirtualNetworkGatewaysOperations.GenerateVpnProfileWithHttpMessagesAsync (resourceGroupName, virtualNetworkGatewayName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="virtualNetworkGatewayName">To be added.</param>
        <param name="parameters">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAdvertisedRoutesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.GatewayRouteListResultInner&gt;&gt; GetAdvertisedRoutesWithHttpMessagesAsync (string resourceGroupName, string virtualNetworkGatewayName, string peer, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.GatewayRouteListResultInner&gt;&gt; GetAdvertisedRoutesWithHttpMessagesAsync(string resourceGroupName, string virtualNetworkGatewayName, string peer, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations.GetAdvertisedRoutesWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAdvertisedRoutesWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.GatewayRouteListResultInner&gt;&gt;" Usage="iVirtualNetworkGatewaysOperations.GetAdvertisedRoutesWithHttpMessagesAsync (resourceGroupName, virtualNetworkGatewayName, peer, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.GatewayRouteListResultInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="peer" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="8f567-169">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8f567-169">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="8f567-170">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="8f567-170">The name of the virtual network gateway.</span></span>
            </param>
        <param name="peer">
            <span data-ttu-id="8f567-171">ピアの IP アドレス</span><span class="sxs-lookup"><span data-stu-id="8f567-171">The IP address of the peer</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8f567-172">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8f567-172">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8f567-173">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8f567-173">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8f567-174">この操作は、仮想ネットワーク ゲートウェイが、指定したピアにアドバタイズするルートの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="8f567-174">This operation retrieves a list of routes the virtual network gateway is advertising to the specified peer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="8f567-175">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8f567-175">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="8f567-176">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8f567-176">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8f567-177">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8f567-177">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetBgpPeerStatusWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.BgpPeerStatusListResultInner&gt;&gt; GetBgpPeerStatusWithHttpMessagesAsync (string resourceGroupName, string virtualNetworkGatewayName, string peer = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.BgpPeerStatusListResultInner&gt;&gt; GetBgpPeerStatusWithHttpMessagesAsync(string resourceGroupName, string virtualNetworkGatewayName, string peer, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations.GetBgpPeerStatusWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetBgpPeerStatusWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.BgpPeerStatusListResultInner&gt;&gt;" Usage="iVirtualNetworkGatewaysOperations.GetBgpPeerStatusWithHttpMessagesAsync (resourceGroupName, virtualNetworkGatewayName, peer, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.BgpPeerStatusListResultInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="peer" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="8f567-178">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8f567-178">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="8f567-179">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="8f567-179">The name of the virtual network gateway.</span></span>
            </param>
        <param name="peer">
            <span data-ttu-id="8f567-180">状態を取得するピアの IP アドレス。</span><span class="sxs-lookup"><span data-stu-id="8f567-180">The IP address of the peer to retrieve the status of.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8f567-181">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8f567-181">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8f567-182">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8f567-182">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8f567-183">GetBgpPeerStatus 操作では、すべての BGP ピアの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="8f567-183">The GetBgpPeerStatus operation retrieves the status of all BGP peers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="8f567-184">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8f567-184">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="8f567-185">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8f567-185">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8f567-186">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8f567-186">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetLearnedRoutesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.GatewayRouteListResultInner&gt;&gt; GetLearnedRoutesWithHttpMessagesAsync (string resourceGroupName, string virtualNetworkGatewayName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.GatewayRouteListResultInner&gt;&gt; GetLearnedRoutesWithHttpMessagesAsync(string resourceGroupName, string virtualNetworkGatewayName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations.GetLearnedRoutesWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetLearnedRoutesWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.GatewayRouteListResultInner&gt;&gt;" Usage="iVirtualNetworkGatewaysOperations.GetLearnedRoutesWithHttpMessagesAsync (resourceGroupName, virtualNetworkGatewayName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.GatewayRouteListResultInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="8f567-187">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8f567-187">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="8f567-188">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="8f567-188">The name of the virtual network gateway.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8f567-189">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8f567-189">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8f567-190">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8f567-190">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8f567-191">この操作では、仮想ネットワーク ゲートウェイが学習したルートの一覧を取得は、BGP ピアから学習したルートを含むです。</span><span class="sxs-lookup"><span data-stu-id="8f567-191">This operation retrieves a list of routes the virtual network gateway has learned, including routes learned from BGP peers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="8f567-192">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8f567-192">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="8f567-193">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8f567-193">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8f567-194">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8f567-194">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string virtualNetworkGatewayName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string virtualNetworkGatewayName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations.GetWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;&gt;" Usage="iVirtualNetworkGatewaysOperations.GetWithHttpMessagesAsync (resourceGroupName, virtualNetworkGatewayName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="8f567-195">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8f567-195">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="8f567-196">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="8f567-196">The name of the virtual network gateway.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8f567-197">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8f567-197">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8f567-198">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8f567-198">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8f567-199">リソース グループによって指定された仮想ネットワーク ゲートウェイを取得します。</span><span class="sxs-lookup"><span data-stu-id="8f567-199">Gets the specified virtual network gateway by resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="8f567-200">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8f567-200">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="8f567-201">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8f567-201">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8f567-202">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8f567-202">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListConnectionsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionListEntityInner&gt;&gt;&gt; ListConnectionsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionListEntityInner&gt;&gt;&gt; ListConnectionsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations.ListConnectionsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListConnectionsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionListEntityInner&gt;&gt;&gt;" Usage="iVirtualNetworkGatewaysOperations.ListConnectionsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionListEntityInner&gt;&gt;&gt;</ReturnType>
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
    <Member MemberName="ListConnectionsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionListEntityInner&gt;&gt;&gt; ListConnectionsWithHttpMessagesAsync (string resourceGroupName, string virtualNetworkGatewayName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionListEntityInner&gt;&gt;&gt; ListConnectionsWithHttpMessagesAsync(string resourceGroupName, string virtualNetworkGatewayName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations.ListConnectionsWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListConnectionsWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionListEntityInner&gt;&gt;&gt;" Usage="iVirtualNetworkGatewaysOperations.ListConnectionsWithHttpMessagesAsync (resourceGroupName, virtualNetworkGatewayName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionListEntityInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="virtualNetworkGatewayName">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations.ListNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;&gt;&gt;" Usage="iVirtualNetworkGatewaysOperations.ListNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="8f567-203">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="8f567-203">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8f567-204">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8f567-204">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8f567-205">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8f567-205">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8f567-206">リソース グループによってすべての仮想ネットワーク ゲートウェイを取得します。</span><span class="sxs-lookup"><span data-stu-id="8f567-206">Gets all virtual network gateways by resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="8f567-207">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8f567-207">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="8f567-208">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8f567-208">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8f567-209">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8f567-209">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;&gt;&gt; ListWithHttpMessagesAsync (string resourceGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;&gt;&gt; ListWithHttpMessagesAsync(string resourceGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations.ListWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;&gt;&gt;" Usage="iVirtualNetworkGatewaysOperations.ListWithHttpMessagesAsync (resourceGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="8f567-210">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8f567-210">The name of the resource group.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8f567-211">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8f567-211">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8f567-212">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8f567-212">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8f567-213">リソース グループによってすべての仮想ネットワーク ゲートウェイを取得します。</span><span class="sxs-lookup"><span data-stu-id="8f567-213">Gets all virtual network gateways by resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="8f567-214">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8f567-214">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="8f567-215">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8f567-215">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8f567-216">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8f567-216">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ResetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;&gt; ResetWithHttpMessagesAsync (string resourceGroupName, string virtualNetworkGatewayName, string gatewayVip = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;&gt; ResetWithHttpMessagesAsync(string resourceGroupName, string virtualNetworkGatewayName, string gatewayVip, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations.ResetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ResetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;&gt;" Usage="iVirtualNetworkGatewaysOperations.ResetWithHttpMessagesAsync (resourceGroupName, virtualNetworkGatewayName, gatewayVip, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="gatewayVip" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="8f567-217">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8f567-217">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="8f567-218">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="8f567-218">The name of the virtual network gateway.</span></span>
            </param>
        <param name="gatewayVip">
            <span data-ttu-id="8f567-219">仮想ネットワーク ゲートウェイの vip アドレスがアクティブ/アクティブ機能を有効にしているゲートウェイの開始のリセットを提供します。</span><span class="sxs-lookup"><span data-stu-id="8f567-219">Virtual network gateway vip address supplied to the begin reset of the active-active feature enabled gateway.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8f567-220">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8f567-220">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8f567-221">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8f567-221">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8f567-222">指定されたリソース グループ内の仮想ネットワーク ゲートウェイのプライマリをリセットします。</span><span class="sxs-lookup"><span data-stu-id="8f567-222">Resets the primary of the virtual network gateway in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="8f567-223">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8f567-223">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="8f567-224">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8f567-224">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8f567-225">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8f567-225">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>