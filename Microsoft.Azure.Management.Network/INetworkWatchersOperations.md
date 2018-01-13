<Type Name="INetworkWatchersOperations" FullName="Microsoft.Azure.Management.Network.INetworkWatchersOperations">
  <TypeSignature Language="C#" Value="public interface INetworkWatchersOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract INetworkWatchersOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.INetworkWatchersOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface INetworkWatchersOperations" />
  <TypeSignature Language="F#" Value="type INetworkWatchersOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7d85e-101">NetworkWatchersOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="7d85e-101">NetworkWatchersOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCheckConnectivityWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ConnectivityInformation&gt;&gt; BeginCheckConnectivityWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.ConnectivityParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.ConnectivityInformation&gt;&gt; BeginCheckConnectivityWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.ConnectivityParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.BeginCheckConnectivityWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Models.ConnectivityParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCheckConnectivityWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Models.ConnectivityParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ConnectivityInformation&gt;&gt;" Usage="iNetworkWatchersOperations.BeginCheckConnectivityWithHttpMessagesAsync (resourceGroupName, networkWatcherName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ConnectivityInformation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.ConnectivityParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7d85e-102">ネットワーク ウォッチャー リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-102">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="7d85e-103">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-103">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7d85e-104">接続の確認を実行する方法を決定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="7d85e-104">Parameters that determine how the connectivity check will be performed.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7d85e-105">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-105">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7d85e-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7d85e-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7d85e-107">別の VM または任意のリモート サーバーを含む、指定したエンドポイントへの仮想マシンから直接 TCP 接続を設けることを確認します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-107">Verifies the possibility of establishing a direct TCP connection from a virtual machine to a given endpoint including another VM or an arbitrary remote server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7d85e-108">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-108">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7d85e-109">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-109">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7d85e-110">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-110">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.BeginDeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iNetworkWatchersOperations.BeginDeleteWithHttpMessagesAsync (resourceGroupName, networkWatcherName, customHeaders, cancellationToken)" />
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
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7d85e-111">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-111">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="7d85e-112">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-112">The name of the network watcher.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7d85e-113">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-113">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7d85e-114">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7d85e-114">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7d85e-115">指定したネットワーク監視リソースを削除します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-115">Deletes the specified network watcher resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7d85e-116">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-116">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7d85e-117">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-117">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginGetAzureReachabilityReportWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.AzureReachabilityReport&gt;&gt; BeginGetAzureReachabilityReportWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.AzureReachabilityReport&gt;&gt; BeginGetAzureReachabilityReportWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.BeginGetAzureReachabilityReportWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetAzureReachabilityReportWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.AzureReachabilityReport&gt;&gt;" Usage="iNetworkWatchersOperations.BeginGetAzureReachabilityReportWithHttpMessagesAsync (resourceGroupName, networkWatcherName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.AzureReachabilityReport&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7d85e-118">ネットワーク ウォッチャー リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-118">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="7d85e-119">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-119">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7d85e-120">Azure の到達可能性を決定するパラメーターは、構成を報告します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-120">Parameters that determine Azure reachability report configuration.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7d85e-121">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-121">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7d85e-122">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7d85e-122">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7d85e-123">スコアを取得します相対的な待機時間のインターネット サービス プロバイダー指定した場所から Azure リージョンにします。</span><span class="sxs-lookup"><span data-stu-id="7d85e-123">Gets the relative latency score for internet service providers from a specified location to Azure regions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7d85e-124">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-124">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7d85e-125">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-125">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7d85e-126">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-126">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginGetFlowLogStatusWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;&gt; BeginGetFlowLogStatusWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;&gt; BeginGetFlowLogStatusWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.BeginGetFlowLogStatusWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetFlowLogStatusWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;&gt;" Usage="iNetworkWatchersOperations.BeginGetFlowLogStatusWithHttpMessagesAsync (resourceGroupName, networkWatcherName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7d85e-127">ネットワーク ウォッチャー リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-127">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="7d85e-128">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-128">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7d85e-129">クエリのフローにリソースを定義するパラメーターはログの状態です。</span><span class="sxs-lookup"><span data-stu-id="7d85e-129">Parameters that define a resource to query flow log status.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7d85e-130">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-130">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7d85e-131">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7d85e-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7d85e-132">フローのクエリの状態は、指定されたリソースにログオンします。</span><span class="sxs-lookup"><span data-stu-id="7d85e-132">Queries status of flow log on a specified resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7d85e-133">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-133">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7d85e-134">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-134">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7d85e-135">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-135">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginGetNextHopWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.NextHopResult&gt;&gt; BeginGetNextHopWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.NextHopParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.NextHopResult&gt;&gt; BeginGetNextHopWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.NextHopParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.BeginGetNextHopWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Models.NextHopParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetNextHopWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Models.NextHopParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.NextHopResult&gt;&gt;" Usage="iNetworkWatchersOperations.BeginGetNextHopWithHttpMessagesAsync (resourceGroupName, networkWatcherName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.NextHopResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.NextHopParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7d85e-136">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-136">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="7d85e-137">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-137">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7d85e-138">送信元と送信先のエンドポイントを定義するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="7d85e-138">Parameters that define the source and destination endpoint.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7d85e-139">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-139">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7d85e-140">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7d85e-140">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7d85e-141">指定した VM から次のホップを取得します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-141">Gets the next hop from the specified VM.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7d85e-142">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-142">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7d85e-143">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-143">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7d85e-144">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-144">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginGetTroubleshootingResultWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;&gt; BeginGetTroubleshootingResultWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;&gt; BeginGetTroubleshootingResultWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.BeginGetTroubleshootingResultWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetTroubleshootingResultWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;&gt;" Usage="iNetworkWatchersOperations.BeginGetTroubleshootingResultWithHttpMessagesAsync (resourceGroupName, networkWatcherName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7d85e-145">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-145">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="7d85e-146">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-146">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7d85e-147">クエリのトラブルシューティングの結果にリソースを定義するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="7d85e-147">Parameters that define the resource to query the troubleshooting result.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7d85e-148">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-148">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7d85e-149">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7d85e-149">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7d85e-150">指定したリソースに対して最後に完了したトラブルシューティングの結果を取得します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-150">Get the last completed troubleshooting result on a specified resource</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7d85e-151">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-151">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7d85e-152">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-152">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7d85e-153">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-153">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginGetTroubleshootingWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;&gt; BeginGetTroubleshootingWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.TroubleshootingParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;&gt; BeginGetTroubleshootingWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.TroubleshootingParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.BeginGetTroubleshootingWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Models.TroubleshootingParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetTroubleshootingWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Models.TroubleshootingParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;&gt;" Usage="iNetworkWatchersOperations.BeginGetTroubleshootingWithHttpMessagesAsync (resourceGroupName, networkWatcherName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TroubleshootingParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7d85e-154">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-154">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="7d85e-155">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-155">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7d85e-156">トラブルシューティングのリソースを定義するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="7d85e-156">Parameters that define the resource to troubleshoot.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7d85e-157">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-157">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7d85e-158">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7d85e-158">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7d85e-159">指定したリソースに対するトラブルシューティングを開始します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-159">Initiate troubleshooting on a specified resource</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7d85e-160">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-160">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7d85e-161">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-161">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7d85e-162">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-162">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginGetVMSecurityRulesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult&gt;&gt; BeginGetVMSecurityRulesWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult&gt;&gt; BeginGetVMSecurityRulesWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.BeginGetVMSecurityRulesWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetVMSecurityRulesWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult&gt;&gt;" Usage="iNetworkWatchersOperations.BeginGetVMSecurityRulesWithHttpMessagesAsync (resourceGroupName, networkWatcherName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7d85e-163">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-163">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="7d85e-164">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-164">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7d85e-165">セキュリティ グループをチェックする VM を定義するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="7d85e-165">Parameters that define the VM to check security groups for.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7d85e-166">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-166">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7d85e-167">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7d85e-167">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7d85e-168">指定した VM で構成され、有効なセキュリティ グループの規則を取得します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-168">Gets the configured and effective security group rules on the specified VM.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7d85e-169">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-169">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7d85e-170">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-170">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7d85e-171">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-171">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginListAvailableProvidersWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.AvailableProvidersList&gt;&gt; BeginListAvailableProvidersWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.AvailableProvidersList&gt;&gt; BeginListAvailableProvidersWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.BeginListAvailableProvidersWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginListAvailableProvidersWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.AvailableProvidersList&gt;&gt;" Usage="iNetworkWatchersOperations.BeginListAvailableProvidersWithHttpMessagesAsync (resourceGroupName, networkWatcherName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.AvailableProvidersList&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7d85e-172">ネットワーク ウォッチャー リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-172">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="7d85e-173">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-173">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7d85e-174">使用可能なプロバイダーの一覧の範囲のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="7d85e-174">Parameters that scope the list of available providers.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7d85e-175">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-175">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7d85e-176">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7d85e-176">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7d85e-177">指定された Azure の地域の利用可能なインターネット サービス プロバイダーをすべて一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-177">Lists all available internet service providers for a specified Azure region.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7d85e-178">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-178">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7d85e-179">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-179">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7d85e-180">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-180">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginSetFlowLogConfigurationWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;&gt; BeginSetFlowLogConfigurationWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.FlowLogInformation parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;&gt; BeginSetFlowLogConfigurationWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.FlowLogInformation parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.BeginSetFlowLogConfigurationWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Models.FlowLogInformation,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginSetFlowLogConfigurationWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Models.FlowLogInformation * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;&gt;" Usage="iNetworkWatchersOperations.BeginSetFlowLogConfigurationWithHttpMessagesAsync (resourceGroupName, networkWatcherName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.FlowLogInformation" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7d85e-181">ネットワーク ウォッチャー リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-181">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="7d85e-182">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-182">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7d85e-183">フローのログの構成を定義するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="7d85e-183">Parameters that define the configuration of flow log.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7d85e-184">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-184">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7d85e-185">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7d85e-185">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7d85e-186">指定されたリソースのフローのログを構成します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-186">Configures flow log on a specified resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7d85e-187">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-187">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7d85e-188">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-188">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7d85e-189">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-189">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginVerifyIPFlowWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult&gt;&gt; BeginVerifyIPFlowWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult&gt;&gt; BeginVerifyIPFlowWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.BeginVerifyIPFlowWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginVerifyIPFlowWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult&gt;&gt;" Usage="iNetworkWatchersOperations.BeginVerifyIPFlowWithHttpMessagesAsync (resourceGroupName, networkWatcherName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7d85e-190">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-190">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="7d85e-191">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-191">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7d85e-192">検証する IP フローを定義するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="7d85e-192">Parameters that define the IP flow to be verified.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7d85e-193">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-193">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7d85e-194">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7d85e-194">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7d85e-195">現在構成されている NSG ルールを指定した位置に指定した VM から IP フローを確認します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-195">Verify IP flow from the specified VM to a location given the currently configured NSG rules.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7d85e-196">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-196">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7d85e-197">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-197">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7d85e-198">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-198">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CheckConnectivityWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ConnectivityInformation&gt;&gt; CheckConnectivityWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.ConnectivityParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.ConnectivityInformation&gt;&gt; CheckConnectivityWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.ConnectivityParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.CheckConnectivityWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Models.ConnectivityParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CheckConnectivityWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Models.ConnectivityParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ConnectivityInformation&gt;&gt;" Usage="iNetworkWatchersOperations.CheckConnectivityWithHttpMessagesAsync (resourceGroupName, networkWatcherName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ConnectivityInformation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.ConnectivityParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7d85e-199">ネットワーク ウォッチャー リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-199">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="7d85e-200">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-200">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7d85e-201">接続の確認を実行する方法を決定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="7d85e-201">Parameters that determine how the connectivity check will be performed.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7d85e-202">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-202">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7d85e-203">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7d85e-203">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7d85e-204">別の VM または任意のリモート サーバーを含む、指定したエンドポイントへの仮想マシンから直接 TCP 接続を設けることを確認します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-204">Verifies the possibility of establishing a direct TCP connection from a virtual machine to a given endpoint including another VM or an arbitrary remote server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7d85e-205">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-205">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7d85e-206">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-206">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7d85e-207">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-207">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.NetworkWatcher parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.NetworkWatcher parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Models.NetworkWatcher,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Models.NetworkWatcher * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt;" Usage="iNetworkWatchersOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, networkWatcherName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.NetworkWatcher" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7d85e-208">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-208">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="7d85e-209">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-209">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7d85e-210">ネットワーク ウォッチャー リソースを定義するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="7d85e-210">Parameters that define the network watcher resource.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7d85e-211">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-211">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7d85e-212">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7d85e-212">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7d85e-213">作成するか、指定されたリソース グループにネットワーク ウォッチャーを更新します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-213">Creates or updates a network watcher in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7d85e-214">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-214">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7d85e-215">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-215">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7d85e-216">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-216">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iNetworkWatchersOperations.DeleteWithHttpMessagesAsync (resourceGroupName, networkWatcherName, customHeaders, cancellationToken)" />
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
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7d85e-217">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-217">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="7d85e-218">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-218">The name of the network watcher.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7d85e-219">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-219">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7d85e-220">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7d85e-220">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7d85e-221">指定したネットワーク監視リソースを削除します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-221">Deletes the specified network watcher resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7d85e-222">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-222">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7d85e-223">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-223">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetAzureReachabilityReportWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.AzureReachabilityReport&gt;&gt; GetAzureReachabilityReportWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.AzureReachabilityReport&gt;&gt; GetAzureReachabilityReportWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.GetAzureReachabilityReportWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAzureReachabilityReportWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.AzureReachabilityReport&gt;&gt;" Usage="iNetworkWatchersOperations.GetAzureReachabilityReportWithHttpMessagesAsync (resourceGroupName, networkWatcherName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.AzureReachabilityReport&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7d85e-224">ネットワーク ウォッチャー リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-224">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="7d85e-225">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-225">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7d85e-226">Azure の到達可能性を決定するパラメーターは、構成を報告します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-226">Parameters that determine Azure reachability report configuration.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7d85e-227">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-227">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7d85e-228">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7d85e-228">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7d85e-229">スコアを取得します相対的な待機時間のインターネット サービス プロバイダー指定した場所から Azure リージョンにします。</span><span class="sxs-lookup"><span data-stu-id="7d85e-229">Gets the relative latency score for internet service providers from a specified location to Azure regions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7d85e-230">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-230">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7d85e-231">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-231">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7d85e-232">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-232">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetFlowLogStatusWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;&gt; GetFlowLogStatusWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;&gt; GetFlowLogStatusWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.GetFlowLogStatusWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetFlowLogStatusWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;&gt;" Usage="iNetworkWatchersOperations.GetFlowLogStatusWithHttpMessagesAsync (resourceGroupName, networkWatcherName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7d85e-233">ネットワーク ウォッチャー リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-233">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="7d85e-234">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-234">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7d85e-235">クエリのフローにリソースを定義するパラメーターはログの状態です。</span><span class="sxs-lookup"><span data-stu-id="7d85e-235">Parameters that define a resource to query flow log status.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7d85e-236">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-236">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7d85e-237">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7d85e-237">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7d85e-238">フローのクエリの状態は、指定されたリソースにログオンします。</span><span class="sxs-lookup"><span data-stu-id="7d85e-238">Queries status of flow log on a specified resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7d85e-239">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-239">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7d85e-240">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-240">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7d85e-241">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-241">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNextHopWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.NextHopResult&gt;&gt; GetNextHopWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.NextHopParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.NextHopResult&gt;&gt; GetNextHopWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.NextHopParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.GetNextHopWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Models.NextHopParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetNextHopWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Models.NextHopParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.NextHopResult&gt;&gt;" Usage="iNetworkWatchersOperations.GetNextHopWithHttpMessagesAsync (resourceGroupName, networkWatcherName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.NextHopResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.NextHopParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7d85e-242">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-242">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="7d85e-243">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-243">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7d85e-244">送信元と送信先のエンドポイントを定義するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="7d85e-244">Parameters that define the source and destination endpoint.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7d85e-245">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-245">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7d85e-246">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7d85e-246">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7d85e-247">指定した VM から次のホップを取得します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-247">Gets the next hop from the specified VM.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7d85e-248">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-248">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7d85e-249">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-249">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7d85e-250">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-250">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetTopologyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.Topology&gt;&gt; GetTopologyWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.TopologyParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.Topology&gt;&gt; GetTopologyWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.TopologyParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.GetTopologyWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Models.TopologyParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetTopologyWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Models.TopologyParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.Topology&gt;&gt;" Usage="iNetworkWatchersOperations.GetTopologyWithHttpMessagesAsync (resourceGroupName, networkWatcherName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.Topology&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TopologyParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7d85e-251">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-251">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="7d85e-252">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-252">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7d85e-253">トポロジの表現を定義するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="7d85e-253">Parameters that define the representation of topology.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7d85e-254">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-254">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7d85e-255">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7d85e-255">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7d85e-256">リソース グループによって、現在のネットワーク トポロジを取得します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-256">Gets the current network topology by resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7d85e-257">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-257">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7d85e-258">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-258">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7d85e-259">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-259">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetTroubleshootingResultWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;&gt; GetTroubleshootingResultWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;&gt; GetTroubleshootingResultWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.GetTroubleshootingResultWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetTroubleshootingResultWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;&gt;" Usage="iNetworkWatchersOperations.GetTroubleshootingResultWithHttpMessagesAsync (resourceGroupName, networkWatcherName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7d85e-260">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-260">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="7d85e-261">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-261">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7d85e-262">クエリのトラブルシューティングの結果にリソースを定義するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="7d85e-262">Parameters that define the resource to query the troubleshooting result.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7d85e-263">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-263">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7d85e-264">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7d85e-264">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7d85e-265">指定したリソースに対して最後に完了したトラブルシューティングの結果を取得します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-265">Get the last completed troubleshooting result on a specified resource</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7d85e-266">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-266">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7d85e-267">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-267">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7d85e-268">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-268">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetTroubleshootingWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;&gt; GetTroubleshootingWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.TroubleshootingParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;&gt; GetTroubleshootingWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.TroubleshootingParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.GetTroubleshootingWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Models.TroubleshootingParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetTroubleshootingWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Models.TroubleshootingParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;&gt;" Usage="iNetworkWatchersOperations.GetTroubleshootingWithHttpMessagesAsync (resourceGroupName, networkWatcherName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TroubleshootingParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7d85e-269">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-269">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="7d85e-270">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-270">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7d85e-271">トラブルシューティングのリソースを定義するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="7d85e-271">Parameters that define the resource to troubleshoot.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7d85e-272">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-272">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7d85e-273">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7d85e-273">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7d85e-274">指定したリソースに対するトラブルシューティングを開始します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-274">Initiate troubleshooting on a specified resource</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7d85e-275">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-275">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7d85e-276">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-276">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7d85e-277">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-277">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetVMSecurityRulesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult&gt;&gt; GetVMSecurityRulesWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult&gt;&gt; GetVMSecurityRulesWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.GetVMSecurityRulesWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetVMSecurityRulesWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult&gt;&gt;" Usage="iNetworkWatchersOperations.GetVMSecurityRulesWithHttpMessagesAsync (resourceGroupName, networkWatcherName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7d85e-278">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-278">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="7d85e-279">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-279">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7d85e-280">セキュリティ グループをチェックする VM を定義するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="7d85e-280">Parameters that define the VM to check security groups for.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7d85e-281">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-281">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7d85e-282">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7d85e-282">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7d85e-283">指定した VM で構成され、有効なセキュリティ グループの規則を取得します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-283">Gets the configured and effective security group rules on the specified VM.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7d85e-284">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-284">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7d85e-285">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-285">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7d85e-286">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-286">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.GetWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt;" Usage="iNetworkWatchersOperations.GetWithHttpMessagesAsync (resourceGroupName, networkWatcherName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7d85e-287">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-287">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="7d85e-288">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-288">The name of the network watcher.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7d85e-289">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-289">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7d85e-290">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7d85e-290">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7d85e-291">リソース グループによって指定されたネットワーク ウォッチャーを取得します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-291">Gets the specified network watcher by resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7d85e-292">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-292">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7d85e-293">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-293">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7d85e-294">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-294">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListAllWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt;&gt; ListAllWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt;&gt; ListAllWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.ListAllWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAllWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt;&gt;" Usage="iNetworkWatchersOperations.ListAllWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="7d85e-295">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-295">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7d85e-296">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7d85e-296">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7d85e-297">サブスクリプションによってすべてのネットワーク監視を取得します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-297">Gets all network watchers by subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7d85e-298">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-298">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7d85e-299">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-299">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7d85e-300">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-300">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListAvailableProvidersWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.AvailableProvidersList&gt;&gt; ListAvailableProvidersWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.AvailableProvidersList&gt;&gt; ListAvailableProvidersWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.ListAvailableProvidersWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAvailableProvidersWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.AvailableProvidersList&gt;&gt;" Usage="iNetworkWatchersOperations.ListAvailableProvidersWithHttpMessagesAsync (resourceGroupName, networkWatcherName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.AvailableProvidersList&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7d85e-301">ネットワーク ウォッチャー リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-301">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="7d85e-302">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-302">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7d85e-303">使用可能なプロバイダーの一覧の範囲のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="7d85e-303">Parameters that scope the list of available providers.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7d85e-304">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-304">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7d85e-305">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7d85e-305">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7d85e-306">指定された Azure の地域の利用可能なインターネット サービス プロバイダーをすべて一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-306">Lists all available internet service providers for a specified Azure region.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7d85e-307">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-307">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7d85e-308">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-308">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7d85e-309">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-309">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt;&gt; ListWithHttpMessagesAsync (string resourceGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt;&gt; ListWithHttpMessagesAsync(string resourceGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.ListWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt;&gt;" Usage="iNetworkWatchersOperations.ListWithHttpMessagesAsync (resourceGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7d85e-310">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-310">The name of the resource group.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7d85e-311">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-311">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7d85e-312">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7d85e-312">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7d85e-313">リソース グループによってすべてのネットワーク監視を取得します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-313">Gets all network watchers by resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7d85e-314">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-314">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7d85e-315">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-315">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7d85e-316">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-316">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="SetFlowLogConfigurationWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;&gt; SetFlowLogConfigurationWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.FlowLogInformation parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;&gt; SetFlowLogConfigurationWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.FlowLogInformation parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.SetFlowLogConfigurationWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Models.FlowLogInformation,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetFlowLogConfigurationWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Models.FlowLogInformation * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;&gt;" Usage="iNetworkWatchersOperations.SetFlowLogConfigurationWithHttpMessagesAsync (resourceGroupName, networkWatcherName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.FlowLogInformation" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7d85e-317">ネットワーク ウォッチャー リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-317">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="7d85e-318">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-318">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7d85e-319">フローのログの構成を定義するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="7d85e-319">Parameters that define the configuration of flow log.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7d85e-320">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-320">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7d85e-321">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7d85e-321">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7d85e-322">指定されたリソースのフローのログを構成します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-322">Configures flow log on a specified resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7d85e-323">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-323">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7d85e-324">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-324">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7d85e-325">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-325">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateTagsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt; UpdateTagsWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.TagsObject parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt; UpdateTagsWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.UpdateTagsWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateTagsWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Models.TagsObject * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt;" Usage="iNetworkWatchersOperations.UpdateTagsWithHttpMessagesAsync (resourceGroupName, networkWatcherName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7d85e-326">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-326">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="7d85e-327">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-327">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7d85e-328">ネットワーク ウォッチャー タグを更新する指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="7d85e-328">Parameters supplied to update network watcher tags.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7d85e-329">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-329">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7d85e-330">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7d85e-330">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7d85e-331">ネットワーク ウォッチャー タグを更新します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-331">Updates a network watcher tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7d85e-332">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-332">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7d85e-333">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-333">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7d85e-334">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-334">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VerifyIPFlowWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult&gt;&gt; VerifyIPFlowWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult&gt;&gt; VerifyIPFlowWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.VerifyIPFlowWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member VerifyIPFlowWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult&gt;&gt;" Usage="iNetworkWatchersOperations.VerifyIPFlowWithHttpMessagesAsync (resourceGroupName, networkWatcherName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7d85e-335">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-335">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="7d85e-336">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="7d85e-336">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7d85e-337">検証する IP フローを定義するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="7d85e-337">Parameters that define the IP flow to be verified.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7d85e-338">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-338">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7d85e-339">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7d85e-339">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7d85e-340">現在構成されている NSG ルールを指定した位置に指定した VM から IP フローを確認します。</span><span class="sxs-lookup"><span data-stu-id="7d85e-340">Verify IP flow from the specified VM to a location given the currently configured NSG rules.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7d85e-341">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-341">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7d85e-342">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-342">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7d85e-343">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d85e-343">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>