<Type Name="IVirtualNetworkPeeringsOperations" FullName="Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations">
  <TypeSignature Language="C#" Value="public interface IVirtualNetworkPeeringsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IVirtualNetworkPeeringsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IVirtualNetworkPeeringsOperations" />
  <TypeSignature Language="F#" Value="type IVirtualNetworkPeeringsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="76bc6-101">VirtualNetworkPeeringsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="76bc6-101">VirtualNetworkPeeringsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string virtualNetworkName, string virtualNetworkPeeringName, Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering virtualNetworkPeeringParameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string virtualNetworkName, string virtualNetworkPeeringName, class Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering virtualNetworkPeeringParameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations.BeginCreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt;&gt;" Usage="iVirtualNetworkPeeringsOperations.BeginCreateOrUpdateWithHttpMessagesAsync (resourceGroupName, virtualNetworkName, virtualNetworkPeeringName, virtualNetworkPeeringParameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="virtualNetworkPeeringName" Type="System.String" />
        <Parameter Name="virtualNetworkPeeringParameters" Type="Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="76bc6-102">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="76bc6-102">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="76bc6-103">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="76bc6-103">The name of the virtual network.</span></span>
            </param>
        <param name="virtualNetworkPeeringName">
            <span data-ttu-id="76bc6-104">ピアリングの名前。</span><span class="sxs-lookup"><span data-stu-id="76bc6-104">The name of the peering.</span></span>
            </param>
        <param name="virtualNetworkPeeringParameters">
            <span data-ttu-id="76bc6-105">作成または更新仮想ネットワークのピアリング操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="76bc6-105">Parameters supplied to the create or update virtual network peering operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="76bc6-106">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="76bc6-106">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="76bc6-107">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="76bc6-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76bc6-108">作成するか、指定された仮想ネットワークのピアリングを更新します。</span><span class="sxs-lookup"><span data-stu-id="76bc6-108">Creates or updates a peering in the specified virtual network.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="76bc6-109">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="76bc6-109">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="76bc6-110">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="76bc6-110">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="76bc6-111">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="76bc6-111">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync (string resourceGroupName, string virtualNetworkName, string virtualNetworkPeeringName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync(string resourceGroupName, string virtualNetworkName, string virtualNetworkPeeringName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations.BeginDeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iVirtualNetworkPeeringsOperations.BeginDeleteWithHttpMessagesAsync (resourceGroupName, virtualNetworkName, virtualNetworkPeeringName, customHeaders, cancellationToken)" />
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
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="virtualNetworkPeeringName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="76bc6-112">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="76bc6-112">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="76bc6-113">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="76bc6-113">The name of the virtual network.</span></span>
            </param>
        <param name="virtualNetworkPeeringName">
            <span data-ttu-id="76bc6-114">仮想ネットワークのピアリングの名前。</span><span class="sxs-lookup"><span data-stu-id="76bc6-114">The name of the virtual network peering.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="76bc6-115">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="76bc6-115">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="76bc6-116">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="76bc6-116">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76bc6-117">指定された仮想ネットワークのピアリングを削除します。</span><span class="sxs-lookup"><span data-stu-id="76bc6-117">Deletes the specified virtual network peering.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="76bc6-118">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="76bc6-118">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="76bc6-119">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="76bc6-119">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string virtualNetworkName, string virtualNetworkPeeringName, Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering virtualNetworkPeeringParameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string virtualNetworkName, string virtualNetworkPeeringName, class Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering virtualNetworkPeeringParameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt;&gt;" Usage="iVirtualNetworkPeeringsOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, virtualNetworkName, virtualNetworkPeeringName, virtualNetworkPeeringParameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="virtualNetworkPeeringName" Type="System.String" />
        <Parameter Name="virtualNetworkPeeringParameters" Type="Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="76bc6-120">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="76bc6-120">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="76bc6-121">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="76bc6-121">The name of the virtual network.</span></span>
            </param>
        <param name="virtualNetworkPeeringName">
            <span data-ttu-id="76bc6-122">ピアリングの名前。</span><span class="sxs-lookup"><span data-stu-id="76bc6-122">The name of the peering.</span></span>
            </param>
        <param name="virtualNetworkPeeringParameters">
            <span data-ttu-id="76bc6-123">作成または更新仮想ネットワークのピアリング操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="76bc6-123">Parameters supplied to the create or update virtual network peering operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="76bc6-124">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="76bc6-124">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="76bc6-125">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="76bc6-125">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76bc6-126">作成するか、指定された仮想ネットワークのピアリングを更新します。</span><span class="sxs-lookup"><span data-stu-id="76bc6-126">Creates or updates a peering in the specified virtual network.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="76bc6-127">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="76bc6-127">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="76bc6-128">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="76bc6-128">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="76bc6-129">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="76bc6-129">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string virtualNetworkName, string virtualNetworkPeeringName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string virtualNetworkName, string virtualNetworkPeeringName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iVirtualNetworkPeeringsOperations.DeleteWithHttpMessagesAsync (resourceGroupName, virtualNetworkName, virtualNetworkPeeringName, customHeaders, cancellationToken)" />
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
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="virtualNetworkPeeringName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="76bc6-130">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="76bc6-130">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="76bc6-131">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="76bc6-131">The name of the virtual network.</span></span>
            </param>
        <param name="virtualNetworkPeeringName">
            <span data-ttu-id="76bc6-132">仮想ネットワークのピアリングの名前。</span><span class="sxs-lookup"><span data-stu-id="76bc6-132">The name of the virtual network peering.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="76bc6-133">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="76bc6-133">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="76bc6-134">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="76bc6-134">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76bc6-135">指定された仮想ネットワークのピアリングを削除します。</span><span class="sxs-lookup"><span data-stu-id="76bc6-135">Deletes the specified virtual network peering.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="76bc6-136">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="76bc6-136">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="76bc6-137">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="76bc6-137">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string virtualNetworkName, string virtualNetworkPeeringName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string virtualNetworkName, string virtualNetworkPeeringName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt;&gt;" Usage="iVirtualNetworkPeeringsOperations.GetWithHttpMessagesAsync (resourceGroupName, virtualNetworkName, virtualNetworkPeeringName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="virtualNetworkPeeringName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="76bc6-138">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="76bc6-138">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="76bc6-139">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="76bc6-139">The name of the virtual network.</span></span>
            </param>
        <param name="virtualNetworkPeeringName">
            <span data-ttu-id="76bc6-140">仮想ネットワークのピアリングの名前。</span><span class="sxs-lookup"><span data-stu-id="76bc6-140">The name of the virtual network peering.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="76bc6-141">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="76bc6-141">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="76bc6-142">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="76bc6-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76bc6-143">指定された仮想ネットワークのピアリングを取得します。</span><span class="sxs-lookup"><span data-stu-id="76bc6-143">Gets the specified virtual network peering.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="76bc6-144">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="76bc6-144">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="76bc6-145">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="76bc6-145">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="76bc6-146">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="76bc6-146">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt;&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt;&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations.ListNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt;&gt;&gt;" Usage="iVirtualNetworkPeeringsOperations.ListNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="76bc6-147">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="76bc6-147">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="76bc6-148">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="76bc6-148">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="76bc6-149">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="76bc6-149">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76bc6-150">仮想ネットワーク内のすべての仮想ネットワーク ペアリングを含めるを取得します。</span><span class="sxs-lookup"><span data-stu-id="76bc6-150">Gets all virtual network peerings in a virtual network.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="76bc6-151">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="76bc6-151">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="76bc6-152">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="76bc6-152">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="76bc6-153">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="76bc6-153">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt;&gt;&gt; ListWithHttpMessagesAsync (string resourceGroupName, string virtualNetworkName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt;&gt;&gt; ListWithHttpMessagesAsync(string resourceGroupName, string virtualNetworkName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations.ListWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt;&gt;&gt;" Usage="iVirtualNetworkPeeringsOperations.ListWithHttpMessagesAsync (resourceGroupName, virtualNetworkName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="76bc6-154">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="76bc6-154">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="76bc6-155">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="76bc6-155">The name of the virtual network.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="76bc6-156">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="76bc6-156">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="76bc6-157">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="76bc6-157">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76bc6-158">仮想ネットワーク内のすべての仮想ネットワーク ペアリングを含めるを取得します。</span><span class="sxs-lookup"><span data-stu-id="76bc6-158">Gets all virtual network peerings in a virtual network.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="76bc6-159">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="76bc6-159">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="76bc6-160">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="76bc6-160">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="76bc6-161">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="76bc6-161">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>