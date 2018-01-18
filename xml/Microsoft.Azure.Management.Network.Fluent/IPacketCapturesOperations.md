<Type Name="IPacketCapturesOperations" FullName="Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations">
  <TypeSignature Language="C#" Value="public interface IPacketCapturesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IPacketCapturesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IPacketCapturesOperations" />
  <TypeSignature Language="F#" Value="type IPacketCapturesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="4731a-101">PacketCapturesOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="4731a-101">PacketCapturesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureResultInner&gt;&gt; BeginCreateWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, string packetCaptureName, Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureInner parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureResultInner&gt;&gt; BeginCreateWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, string packetCaptureName, class Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureInner parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations.BeginCreateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureResultInner&gt;&gt;" Usage="iPacketCapturesOperations.BeginCreateWithHttpMessagesAsync (resourceGroupName, networkWatcherName, packetCaptureName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureResultInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="packetCaptureName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="4731a-102">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4731a-102">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="4731a-103">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="4731a-103">The name of the network watcher.</span></span>
            </param>
        <param name="packetCaptureName">
            <span data-ttu-id="4731a-104">パケット キャプチャ セッションの名前。</span><span class="sxs-lookup"><span data-stu-id="4731a-104">The name of the packet capture session.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="4731a-105">作成するパケットを定義するパラメーターは、操作をキャプチャします。</span><span class="sxs-lookup"><span data-stu-id="4731a-105">Parameters that define the create packet capture operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="4731a-106">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="4731a-106">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4731a-107">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4731a-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4731a-108">作成し、指定した VM 上のパケット キャプチャを開始します。</span><span class="sxs-lookup"><span data-stu-id="4731a-108">Create and start a packet capture on the specified VM.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="4731a-109">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4731a-109">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="4731a-110">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4731a-110">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4731a-111">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4731a-111">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, string packetCaptureName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, string packetCaptureName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations.BeginDeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iPacketCapturesOperations.BeginDeleteWithHttpMessagesAsync (resourceGroupName, networkWatcherName, packetCaptureName, customHeaders, cancellationToken)" />
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
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="packetCaptureName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="4731a-112">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4731a-112">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="4731a-113">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="4731a-113">The name of the network watcher.</span></span>
            </param>
        <param name="packetCaptureName">
            <span data-ttu-id="4731a-114">パケット キャプチャ セッションの名前。</span><span class="sxs-lookup"><span data-stu-id="4731a-114">The name of the packet capture session.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="4731a-115">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="4731a-115">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4731a-116">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4731a-116">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4731a-117">指定されたパケットのキャプチャ セッションを削除します。</span><span class="sxs-lookup"><span data-stu-id="4731a-117">Deletes the specified packet capture session.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="4731a-118">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4731a-118">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4731a-119">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4731a-119">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginGetStatusWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureQueryStatusResultInner&gt;&gt; BeginGetStatusWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, string packetCaptureName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureQueryStatusResultInner&gt;&gt; BeginGetStatusWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, string packetCaptureName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations.BeginGetStatusWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetStatusWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureQueryStatusResultInner&gt;&gt;" Usage="iPacketCapturesOperations.BeginGetStatusWithHttpMessagesAsync (resourceGroupName, networkWatcherName, packetCaptureName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureQueryStatusResultInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="packetCaptureName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="4731a-120">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4731a-120">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="4731a-121">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="4731a-121">The name of the Network Watcher resource.</span></span>
            </param>
        <param name="packetCaptureName">
            <span data-ttu-id="4731a-122">パケット キャプチャ セッションに与えられた名前。</span><span class="sxs-lookup"><span data-stu-id="4731a-122">The name given to the packet capture session.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="4731a-123">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="4731a-123">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4731a-124">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4731a-124">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4731a-125">実行中のパケット キャプチャ セッションの状態を照会します。</span><span class="sxs-lookup"><span data-stu-id="4731a-125">Query the status of a running packet capture session.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="4731a-126">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4731a-126">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="4731a-127">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4731a-127">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4731a-128">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4731a-128">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginStopWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginStopWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, string packetCaptureName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginStopWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, string packetCaptureName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations.BeginStopWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginStopWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iPacketCapturesOperations.BeginStopWithHttpMessagesAsync (resourceGroupName, networkWatcherName, packetCaptureName, customHeaders, cancellationToken)" />
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
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="packetCaptureName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="4731a-129">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4731a-129">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="4731a-130">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="4731a-130">The name of the network watcher.</span></span>
            </param>
        <param name="packetCaptureName">
            <span data-ttu-id="4731a-131">パケット キャプチャ セッションの名前。</span><span class="sxs-lookup"><span data-stu-id="4731a-131">The name of the packet capture session.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="4731a-132">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="4731a-132">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4731a-133">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4731a-133">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4731a-134">停止した場合に指定されたパケットは、セッションをキャプチャします。</span><span class="sxs-lookup"><span data-stu-id="4731a-134">Stops a specified packet capture session.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="4731a-135">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4731a-135">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4731a-136">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4731a-136">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureResultInner&gt;&gt; CreateWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, string packetCaptureName, Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureInner parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureResultInner&gt;&gt; CreateWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, string packetCaptureName, class Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureInner parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations.CreateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureResultInner&gt;&gt;" Usage="iPacketCapturesOperations.CreateWithHttpMessagesAsync (resourceGroupName, networkWatcherName, packetCaptureName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureResultInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="packetCaptureName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="4731a-137">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4731a-137">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="4731a-138">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="4731a-138">The name of the network watcher.</span></span>
            </param>
        <param name="packetCaptureName">
            <span data-ttu-id="4731a-139">パケット キャプチャ セッションの名前。</span><span class="sxs-lookup"><span data-stu-id="4731a-139">The name of the packet capture session.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="4731a-140">作成するパケットを定義するパラメーターは、操作をキャプチャします。</span><span class="sxs-lookup"><span data-stu-id="4731a-140">Parameters that define the create packet capture operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="4731a-141">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="4731a-141">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4731a-142">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4731a-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4731a-143">作成し、指定した VM 上のパケット キャプチャを開始します。</span><span class="sxs-lookup"><span data-stu-id="4731a-143">Create and start a packet capture on the specified VM.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="4731a-144">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4731a-144">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="4731a-145">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4731a-145">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4731a-146">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4731a-146">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, string packetCaptureName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, string packetCaptureName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iPacketCapturesOperations.DeleteWithHttpMessagesAsync (resourceGroupName, networkWatcherName, packetCaptureName, customHeaders, cancellationToken)" />
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
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="packetCaptureName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="4731a-147">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4731a-147">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="4731a-148">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="4731a-148">The name of the network watcher.</span></span>
            </param>
        <param name="packetCaptureName">
            <span data-ttu-id="4731a-149">パケット キャプチャ セッションの名前。</span><span class="sxs-lookup"><span data-stu-id="4731a-149">The name of the packet capture session.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="4731a-150">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="4731a-150">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4731a-151">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4731a-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4731a-152">指定されたパケットのキャプチャ セッションを削除します。</span><span class="sxs-lookup"><span data-stu-id="4731a-152">Deletes the specified packet capture session.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="4731a-153">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4731a-153">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4731a-154">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4731a-154">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetStatusWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureQueryStatusResultInner&gt;&gt; GetStatusWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, string packetCaptureName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureQueryStatusResultInner&gt;&gt; GetStatusWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, string packetCaptureName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations.GetStatusWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetStatusWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureQueryStatusResultInner&gt;&gt;" Usage="iPacketCapturesOperations.GetStatusWithHttpMessagesAsync (resourceGroupName, networkWatcherName, packetCaptureName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureQueryStatusResultInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="packetCaptureName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="4731a-155">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4731a-155">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="4731a-156">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="4731a-156">The name of the Network Watcher resource.</span></span>
            </param>
        <param name="packetCaptureName">
            <span data-ttu-id="4731a-157">パケット キャプチャ セッションに与えられた名前。</span><span class="sxs-lookup"><span data-stu-id="4731a-157">The name given to the packet capture session.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="4731a-158">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="4731a-158">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4731a-159">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4731a-159">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4731a-160">実行中のパケット キャプチャ セッションの状態を照会します。</span><span class="sxs-lookup"><span data-stu-id="4731a-160">Query the status of a running packet capture session.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="4731a-161">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4731a-161">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="4731a-162">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4731a-162">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4731a-163">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4731a-163">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureResultInner&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, string packetCaptureName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureResultInner&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, string packetCaptureName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureResultInner&gt;&gt;" Usage="iPacketCapturesOperations.GetWithHttpMessagesAsync (resourceGroupName, networkWatcherName, packetCaptureName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureResultInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="packetCaptureName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="4731a-164">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4731a-164">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="4731a-165">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="4731a-165">The name of the network watcher.</span></span>
            </param>
        <param name="packetCaptureName">
            <span data-ttu-id="4731a-166">パケット キャプチャ セッションの名前。</span><span class="sxs-lookup"><span data-stu-id="4731a-166">The name of the packet capture session.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="4731a-167">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="4731a-167">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4731a-168">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4731a-168">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4731a-169">名前で、パケット キャプチャ セッションを取得します。</span><span class="sxs-lookup"><span data-stu-id="4731a-169">Gets a packet capture session by name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="4731a-170">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4731a-170">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="4731a-171">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4731a-171">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4731a-172">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4731a-172">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureResultInner&gt;&gt;&gt; ListWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureResultInner&gt;&gt;&gt; ListWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations.ListWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureResultInner&gt;&gt;&gt;" Usage="iPacketCapturesOperations.ListWithHttpMessagesAsync (resourceGroupName, networkWatcherName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureResultInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="4731a-173">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4731a-173">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="4731a-174">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="4731a-174">The name of the Network Watcher resource.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="4731a-175">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="4731a-175">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4731a-176">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4731a-176">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4731a-177">指定されたリソース グループ内のすべてのパケット キャプチャ セッションの一覧を示します。</span><span class="sxs-lookup"><span data-stu-id="4731a-177">Lists all packet capture sessions within the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="4731a-178">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4731a-178">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="4731a-179">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4731a-179">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4731a-180">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4731a-180">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="StopWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; StopWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, string packetCaptureName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; StopWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, string packetCaptureName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations.StopWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member StopWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iPacketCapturesOperations.StopWithHttpMessagesAsync (resourceGroupName, networkWatcherName, packetCaptureName, customHeaders, cancellationToken)" />
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
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="packetCaptureName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="4731a-181">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4731a-181">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="4731a-182">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="4731a-182">The name of the network watcher.</span></span>
            </param>
        <param name="packetCaptureName">
            <span data-ttu-id="4731a-183">パケット キャプチャ セッションの名前。</span><span class="sxs-lookup"><span data-stu-id="4731a-183">The name of the packet capture session.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="4731a-184">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="4731a-184">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4731a-185">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4731a-185">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4731a-186">停止した場合に指定されたパケットは、セッションをキャプチャします。</span><span class="sxs-lookup"><span data-stu-id="4731a-186">Stops a specified packet capture session.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="4731a-187">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4731a-187">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4731a-188">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4731a-188">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>