<Type Name="NetworkWatchersOperationsExtensions" FullName="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class NetworkWatchersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit NetworkWatchersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module NetworkWatchersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type NetworkWatchersOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="de03d-101">NetworkWatchersOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="de03d-101">Extension methods for NetworkWatchersOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCheckConnectivity">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ConnectivityInformation BeginCheckConnectivity (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.ConnectivityParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ConnectivityInformation BeginCheckConnectivity(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.ConnectivityParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginCheckConnectivity(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.ConnectivityParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCheckConnectivity (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As ConnectivityParameters) As ConnectivityInformation" />
      <MemberSignature Language="F#" Value="static member BeginCheckConnectivity : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.ConnectivityParameters -&gt; Microsoft.Azure.Management.Network.Models.ConnectivityInformation" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginCheckConnectivity (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ConnectivityInformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.ConnectivityParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-103">ネットワーク ウォッチャー リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-103">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-104">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-104">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de03d-105">接続の確認を実行する方法を決定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="de03d-105">Parameters that determine how the connectivity check will be performed.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-106">別の VM または任意のリモート サーバーを含む、指定したエンドポイントへの仮想マシンから直接 TCP 接続を設けることを確認します。</span><span class="sxs-lookup"><span data-stu-id="de03d-106">Verifies the possibility of establishing a direct TCP connection from a virtual machine to a given endpoint including another VM or an arbitrary remote server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCheckConnectivityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ConnectivityInformation&gt; BeginCheckConnectivityAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.ConnectivityParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ConnectivityInformation&gt; BeginCheckConnectivityAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.ConnectivityParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginCheckConnectivityAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.ConnectivityParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCheckConnectivityAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.ConnectivityParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ConnectivityInformation&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginCheckConnectivityAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;BeginCheckConnectivityAsync&gt;d__51))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ConnectivityInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.ConnectivityParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-108">ネットワーク ウォッチャー リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-108">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-109">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-109">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de03d-110">接続の確認を実行する方法を決定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="de03d-110">Parameters that determine how the connectivity check will be performed.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="de03d-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="de03d-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-112">別の VM または任意のリモート サーバーを含む、指定したエンドポイントへの仮想マシンから直接 TCP 接続を設けることを確認します。</span><span class="sxs-lookup"><span data-stu-id="de03d-112">Verifies the possibility of establishing a direct TCP connection from a virtual machine to a given endpoint including another VM or an arbitrary remote server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginDelete (operations, resourceGroupName, networkWatcherName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-114">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-114">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-115">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-115">The name of the network watcher.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-116">指定したネットワーク監視リソースを削除します。</span><span class="sxs-lookup"><span data-stu-id="de03d-116">Deletes the specified network watcher resource.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, networkWatcherName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;BeginDeleteAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-118">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-118">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-119">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-119">The name of the network watcher.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="de03d-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="de03d-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-121">指定したネットワーク監視リソースを削除します。</span><span class="sxs-lookup"><span data-stu-id="de03d-121">Deletes the specified network watcher resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetAzureReachabilityReport">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.AzureReachabilityReport BeginGetAzureReachabilityReport (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.AzureReachabilityReport BeginGetAzureReachabilityReport(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetAzureReachabilityReport(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginGetAzureReachabilityReport (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As AzureReachabilityReportParameters) As AzureReachabilityReport" />
      <MemberSignature Language="F#" Value="static member BeginGetAzureReachabilityReport : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters -&gt; Microsoft.Azure.Management.Network.Models.AzureReachabilityReport" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetAzureReachabilityReport (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.AzureReachabilityReport</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-122">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-123">ネットワーク ウォッチャー リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-123">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-124">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-124">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de03d-125">Azure の到達可能性を決定するパラメーターは、構成を報告します。</span><span class="sxs-lookup"><span data-stu-id="de03d-125">Parameters that determine Azure reachability report configuration.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-126">スコアを取得します相対的な待機時間のインターネット サービス プロバイダー指定した場所から Azure リージョンにします。</span><span class="sxs-lookup"><span data-stu-id="de03d-126">Gets the relative latency score for internet service providers from a specified location to Azure regions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetAzureReachabilityReportAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.AzureReachabilityReport&gt; BeginGetAzureReachabilityReportAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.AzureReachabilityReport&gt; BeginGetAzureReachabilityReportAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetAzureReachabilityReportAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetAzureReachabilityReportAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.AzureReachabilityReport&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetAzureReachabilityReportAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;BeginGetAzureReachabilityReportAsync&gt;d__53))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.AzureReachabilityReport&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-127">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-127">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-128">ネットワーク ウォッチャー リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-128">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-129">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-129">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de03d-130">Azure の到達可能性を決定するパラメーターは、構成を報告します。</span><span class="sxs-lookup"><span data-stu-id="de03d-130">Parameters that determine Azure reachability report configuration.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="de03d-131">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="de03d-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-132">スコアを取得します相対的な待機時間のインターネット サービス プロバイダー指定した場所から Azure リージョンにします。</span><span class="sxs-lookup"><span data-stu-id="de03d-132">Gets the relative latency score for internet service providers from a specified location to Azure regions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetFlowLogStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.FlowLogInformation BeginGetFlowLogStatus (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.FlowLogInformation BeginGetFlowLogStatus(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetFlowLogStatus(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginGetFlowLogStatus (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As FlowLogStatusParameters) As FlowLogInformation" />
      <MemberSignature Language="F#" Value="static member BeginGetFlowLogStatus : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters -&gt; Microsoft.Azure.Management.Network.Models.FlowLogInformation" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetFlowLogStatus (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.FlowLogInformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-133">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-133">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-134">ネットワーク ウォッチャー リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-134">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-135">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-135">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de03d-136">クエリのフローにリソースを定義するパラメーターはログの状態です。</span><span class="sxs-lookup"><span data-stu-id="de03d-136">Parameters that define a resource to query flow log status.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-137">フローのクエリの状態は、指定されたリソースにログオンします。</span><span class="sxs-lookup"><span data-stu-id="de03d-137">Queries status of flow log on a specified resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetFlowLogStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt; BeginGetFlowLogStatusAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt; BeginGetFlowLogStatusAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetFlowLogStatusAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetFlowLogStatusAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetFlowLogStatusAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;BeginGetFlowLogStatusAsync&gt;d__49))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-138">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-138">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-139">ネットワーク ウォッチャー リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-139">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-140">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-140">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de03d-141">クエリのフローにリソースを定義するパラメーターはログの状態です。</span><span class="sxs-lookup"><span data-stu-id="de03d-141">Parameters that define a resource to query flow log status.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="de03d-142">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="de03d-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-143">フローのクエリの状態は、指定されたリソースにログオンします。</span><span class="sxs-lookup"><span data-stu-id="de03d-143">Queries status of flow log on a specified resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetNextHop">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.NextHopResult BeginGetNextHop (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.NextHopParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.NextHopResult BeginGetNextHop(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.NextHopParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetNextHop(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.NextHopParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginGetNextHop (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As NextHopParameters) As NextHopResult" />
      <MemberSignature Language="F#" Value="static member BeginGetNextHop : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.NextHopParameters -&gt; Microsoft.Azure.Management.Network.Models.NextHopResult" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetNextHop (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.NextHopResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.NextHopParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-144">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-144">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-145">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-145">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-146">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-146">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de03d-147">送信元と送信先のエンドポイントを定義するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="de03d-147">Parameters that define the source and destination endpoint.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-148">指定した VM から次のホップを取得します。</span><span class="sxs-lookup"><span data-stu-id="de03d-148">Gets the next hop from the specified VM.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetNextHopAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NextHopResult&gt; BeginGetNextHopAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.NextHopParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.NextHopResult&gt; BeginGetNextHopAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.NextHopParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetNextHopAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.NextHopParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetNextHopAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.NextHopParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NextHopResult&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetNextHopAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;BeginGetNextHopAsync&gt;d__39))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NextHopResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.NextHopParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-149">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-149">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-150">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-150">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-151">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-151">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de03d-152">送信元と送信先のエンドポイントを定義するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="de03d-152">Parameters that define the source and destination endpoint.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="de03d-153">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="de03d-153">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-154">指定した VM から次のホップを取得します。</span><span class="sxs-lookup"><span data-stu-id="de03d-154">Gets the next hop from the specified VM.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetTroubleshooting">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.TroubleshootingResult BeginGetTroubleshooting (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.TroubleshootingParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.TroubleshootingResult BeginGetTroubleshooting(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.TroubleshootingParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetTroubleshooting(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TroubleshootingParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginGetTroubleshooting (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As TroubleshootingParameters) As TroubleshootingResult" />
      <MemberSignature Language="F#" Value="static member BeginGetTroubleshooting : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.TroubleshootingParameters -&gt; Microsoft.Azure.Management.Network.Models.TroubleshootingResult" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetTroubleshooting (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.TroubleshootingResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TroubleshootingParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-155">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-155">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-156">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-156">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-157">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-157">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de03d-158">トラブルシューティングのリソースを定義するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="de03d-158">Parameters that define the resource to troubleshoot.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-159">指定したリソースに対するトラブルシューティングを開始します。</span><span class="sxs-lookup"><span data-stu-id="de03d-159">Initiate troubleshooting on a specified resource</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetTroubleshootingAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt; BeginGetTroubleshootingAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.TroubleshootingParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt; BeginGetTroubleshootingAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.TroubleshootingParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetTroubleshootingAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TroubleshootingParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetTroubleshootingAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.TroubleshootingParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetTroubleshootingAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;BeginGetTroubleshootingAsync&gt;d__43))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TroubleshootingParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-160">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-160">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-161">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-161">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-162">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-162">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de03d-163">トラブルシューティングのリソースを定義するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="de03d-163">Parameters that define the resource to troubleshoot.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="de03d-164">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="de03d-164">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-165">指定したリソースに対するトラブルシューティングを開始します。</span><span class="sxs-lookup"><span data-stu-id="de03d-165">Initiate troubleshooting on a specified resource</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetTroubleshootingResult">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.TroubleshootingResult BeginGetTroubleshootingResult (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.TroubleshootingResult BeginGetTroubleshootingResult(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetTroubleshootingResult(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginGetTroubleshootingResult (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As QueryTroubleshootingParameters) As TroubleshootingResult" />
      <MemberSignature Language="F#" Value="static member BeginGetTroubleshootingResult : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters -&gt; Microsoft.Azure.Management.Network.Models.TroubleshootingResult" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetTroubleshootingResult (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.TroubleshootingResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-166">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-166">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-167">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-167">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-168">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-168">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de03d-169">クエリのトラブルシューティングの結果にリソースを定義するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="de03d-169">Parameters that define the resource to query the troubleshooting result.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-170">指定したリソースに対して最後に完了したトラブルシューティングの結果を取得します。</span><span class="sxs-lookup"><span data-stu-id="de03d-170">Get the last completed troubleshooting result on a specified resource</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetTroubleshootingResultAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt; BeginGetTroubleshootingResultAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt; BeginGetTroubleshootingResultAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetTroubleshootingResultAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetTroubleshootingResultAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetTroubleshootingResultAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;BeginGetTroubleshootingResultAsync&gt;d__45))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-171">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-171">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-172">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-172">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-173">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-173">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de03d-174">クエリのトラブルシューティングの結果にリソースを定義するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="de03d-174">Parameters that define the resource to query the troubleshooting result.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="de03d-175">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="de03d-175">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-176">指定したリソースに対して最後に完了したトラブルシューティングの結果を取得します。</span><span class="sxs-lookup"><span data-stu-id="de03d-176">Get the last completed troubleshooting result on a specified resource</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetVMSecurityRules">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult BeginGetVMSecurityRules (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult BeginGetVMSecurityRules(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetVMSecurityRules(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginGetVMSecurityRules (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As SecurityGroupViewParameters) As SecurityGroupViewResult" />
      <MemberSignature Language="F#" Value="static member BeginGetVMSecurityRules : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters -&gt; Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetVMSecurityRules (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-177">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-177">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-178">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-178">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-179">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-179">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de03d-180">セキュリティ グループをチェックする VM を定義するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="de03d-180">Parameters that define the VM to check security groups for.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-181">指定した VM で構成され、有効なセキュリティ グループの規則を取得します。</span><span class="sxs-lookup"><span data-stu-id="de03d-181">Gets the configured and effective security group rules on the specified VM.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetVMSecurityRulesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult&gt; BeginGetVMSecurityRulesAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult&gt; BeginGetVMSecurityRulesAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetVMSecurityRulesAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetVMSecurityRulesAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetVMSecurityRulesAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;BeginGetVMSecurityRulesAsync&gt;d__41))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-182">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-182">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-183">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-183">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-184">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-184">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de03d-185">セキュリティ グループをチェックする VM を定義するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="de03d-185">Parameters that define the VM to check security groups for.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="de03d-186">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="de03d-186">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-187">指定した VM で構成され、有効なセキュリティ グループの規則を取得します。</span><span class="sxs-lookup"><span data-stu-id="de03d-187">Gets the configured and effective security group rules on the specified VM.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListAvailableProviders">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.AvailableProvidersList BeginListAvailableProviders (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.AvailableProvidersList BeginListAvailableProviders(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginListAvailableProviders(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginListAvailableProviders (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As AvailableProvidersListParameters) As AvailableProvidersList" />
      <MemberSignature Language="F#" Value="static member BeginListAvailableProviders : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters -&gt; Microsoft.Azure.Management.Network.Models.AvailableProvidersList" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginListAvailableProviders (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.AvailableProvidersList</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-188">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-188">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-189">ネットワーク ウォッチャー リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-189">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-190">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-190">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de03d-191">使用可能なプロバイダーの一覧の範囲のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="de03d-191">Parameters that scope the list of available providers.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-192">指定された Azure の地域の利用可能なインターネット サービス プロバイダーをすべて一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="de03d-192">Lists all available internet service providers for a specified Azure region.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListAvailableProvidersAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.AvailableProvidersList&gt; BeginListAvailableProvidersAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.AvailableProvidersList&gt; BeginListAvailableProvidersAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginListAvailableProvidersAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginListAvailableProvidersAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.AvailableProvidersList&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginListAvailableProvidersAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;BeginListAvailableProvidersAsync&gt;d__55))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.AvailableProvidersList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-193">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-193">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-194">ネットワーク ウォッチャー リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-194">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-195">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-195">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de03d-196">使用可能なプロバイダーの一覧の範囲のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="de03d-196">Parameters that scope the list of available providers.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="de03d-197">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="de03d-197">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-198">指定された Azure の地域の利用可能なインターネット サービス プロバイダーをすべて一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="de03d-198">Lists all available internet service providers for a specified Azure region.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetFlowLogConfiguration">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.FlowLogInformation BeginSetFlowLogConfiguration (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.FlowLogInformation parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.FlowLogInformation BeginSetFlowLogConfiguration(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.FlowLogInformation parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginSetFlowLogConfiguration(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.FlowLogInformation)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginSetFlowLogConfiguration (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As FlowLogInformation) As FlowLogInformation" />
      <MemberSignature Language="F#" Value="static member BeginSetFlowLogConfiguration : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.FlowLogInformation -&gt; Microsoft.Azure.Management.Network.Models.FlowLogInformation" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginSetFlowLogConfiguration (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.FlowLogInformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.FlowLogInformation" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-199">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-199">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-200">ネットワーク ウォッチャー リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-200">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-201">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-201">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de03d-202">フローのログの構成を定義するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="de03d-202">Parameters that define the configuration of flow log.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-203">指定されたリソースのフローのログを構成します。</span><span class="sxs-lookup"><span data-stu-id="de03d-203">Configures flow log on a specified resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetFlowLogConfigurationAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt; BeginSetFlowLogConfigurationAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.FlowLogInformation parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt; BeginSetFlowLogConfigurationAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.FlowLogInformation parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginSetFlowLogConfigurationAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.FlowLogInformation,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginSetFlowLogConfigurationAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.FlowLogInformation * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginSetFlowLogConfigurationAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;BeginSetFlowLogConfigurationAsync&gt;d__47))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.FlowLogInformation" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-204">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-204">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-205">ネットワーク ウォッチャー リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-205">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-206">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-206">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de03d-207">フローのログの構成を定義するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="de03d-207">Parameters that define the configuration of flow log.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="de03d-208">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="de03d-208">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-209">指定されたリソースのフローのログを構成します。</span><span class="sxs-lookup"><span data-stu-id="de03d-209">Configures flow log on a specified resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginVerifyIPFlow">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult BeginVerifyIPFlow (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult BeginVerifyIPFlow(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginVerifyIPFlow(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginVerifyIPFlow (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As VerificationIPFlowParameters) As VerificationIPFlowResult" />
      <MemberSignature Language="F#" Value="static member BeginVerifyIPFlow : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters -&gt; Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginVerifyIPFlow (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-210">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-210">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-211">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-211">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-212">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-212">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de03d-213">検証する IP フローを定義するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="de03d-213">Parameters that define the IP flow to be verified.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-214">現在構成されている NSG ルールを指定した位置に指定した VM から IP フローを確認します。</span><span class="sxs-lookup"><span data-stu-id="de03d-214">Verify IP flow from the specified VM to a location given the currently configured NSG rules.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginVerifyIPFlowAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult&gt; BeginVerifyIPFlowAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult&gt; BeginVerifyIPFlowAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginVerifyIPFlowAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginVerifyIPFlowAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginVerifyIPFlowAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;BeginVerifyIPFlowAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-215">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-215">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-216">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-216">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-217">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-217">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de03d-218">検証する IP フローを定義するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="de03d-218">Parameters that define the IP flow to be verified.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="de03d-219">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="de03d-219">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-220">現在構成されている NSG ルールを指定した位置に指定した VM から IP フローを確認します。</span><span class="sxs-lookup"><span data-stu-id="de03d-220">Verify IP flow from the specified VM to a location given the currently configured NSG rules.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckConnectivity">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ConnectivityInformation CheckConnectivity (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.ConnectivityParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ConnectivityInformation CheckConnectivity(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.ConnectivityParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.CheckConnectivity(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.ConnectivityParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CheckConnectivity (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As ConnectivityParameters) As ConnectivityInformation" />
      <MemberSignature Language="F#" Value="static member CheckConnectivity : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.ConnectivityParameters -&gt; Microsoft.Azure.Management.Network.Models.ConnectivityInformation" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.CheckConnectivity (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ConnectivityInformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.ConnectivityParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-221">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-221">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-222">ネットワーク ウォッチャー リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-222">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-223">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-223">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de03d-224">接続の確認を実行する方法を決定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="de03d-224">Parameters that determine how the connectivity check will be performed.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-225">別の VM または任意のリモート サーバーを含む、指定したエンドポイントへの仮想マシンから直接 TCP 接続を設けることを確認します。</span><span class="sxs-lookup"><span data-stu-id="de03d-225">Verifies the possibility of establishing a direct TCP connection from a virtual machine to a given endpoint including another VM or an arbitrary remote server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckConnectivityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ConnectivityInformation&gt; CheckConnectivityAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.ConnectivityParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ConnectivityInformation&gt; CheckConnectivityAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.ConnectivityParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.CheckConnectivityAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.ConnectivityParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckConnectivityAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.ConnectivityParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ConnectivityInformation&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.CheckConnectivityAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;CheckConnectivityAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ConnectivityInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.ConnectivityParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-226">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-226">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-227">ネットワーク ウォッチャー リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-227">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-228">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-228">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de03d-229">接続の確認を実行する方法を決定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="de03d-229">Parameters that determine how the connectivity check will be performed.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="de03d-230">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="de03d-230">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-231">別の VM または任意のリモート サーバーを含む、指定したエンドポイントへの仮想マシンから直接 TCP 接続を設けることを確認します。</span><span class="sxs-lookup"><span data-stu-id="de03d-231">Verifies the possibility of establishing a direct TCP connection from a virtual machine to a given endpoint including another VM or an arbitrary remote server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.NetworkWatcher CreateOrUpdate (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.NetworkWatcher parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.NetworkWatcher CreateOrUpdate(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.NetworkWatcher parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.NetworkWatcher)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As NetworkWatcher) As NetworkWatcher" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.NetworkWatcher -&gt; Microsoft.Azure.Management.Network.Models.NetworkWatcher" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.NetworkWatcher</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.NetworkWatcher" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-232">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-232">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-233">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-233">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-234">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-234">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de03d-235">ネットワーク ウォッチャー リソースを定義するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="de03d-235">Parameters that define the network watcher resource.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-236">作成するか、指定されたリソース グループにネットワーク ウォッチャーを更新します。</span><span class="sxs-lookup"><span data-stu-id="de03d-236">Creates or updates a network watcher in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.NetworkWatcher parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.NetworkWatcher parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.NetworkWatcher,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.NetworkWatcher * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.NetworkWatcher" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-237">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-237">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-238">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-238">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-239">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-239">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de03d-240">ネットワーク ウォッチャー リソースを定義するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="de03d-240">Parameters that define the network watcher resource.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="de03d-241">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="de03d-241">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-242">作成するか、指定されたリソース グループにネットワーク ウォッチャーを更新します。</span><span class="sxs-lookup"><span data-stu-id="de03d-242">Creates or updates a network watcher in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.Delete(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.Delete (operations, resourceGroupName, networkWatcherName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-243">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-243">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-244">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-244">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-245">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-245">The name of the network watcher.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-246">指定したネットワーク監視リソースを削除します。</span><span class="sxs-lookup"><span data-stu-id="de03d-246">Deletes the specified network watcher resource.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.DeleteAsync (operations, resourceGroupName, networkWatcherName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-247">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-247">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-248">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-248">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-249">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-249">The name of the network watcher.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="de03d-250">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="de03d-250">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-251">指定したネットワーク監視リソースを削除します。</span><span class="sxs-lookup"><span data-stu-id="de03d-251">Deletes the specified network watcher resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.NetworkWatcher Get (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.NetworkWatcher Get(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.Get(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String) As NetworkWatcher" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string -&gt; Microsoft.Azure.Management.Network.Models.NetworkWatcher" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.Get (operations, resourceGroupName, networkWatcherName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.NetworkWatcher</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-252">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-252">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-253">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-253">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-254">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-254">The name of the network watcher.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-255">リソース グループによって指定されたネットワーク ウォッチャーを取得します。</span><span class="sxs-lookup"><span data-stu-id="de03d-255">Gets the specified network watcher by resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt; GetAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt; GetAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetAsync (operations, resourceGroupName, networkWatcherName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-256">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-256">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-257">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-257">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-258">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-258">The name of the network watcher.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="de03d-259">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="de03d-259">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-260">リソース グループによって指定されたネットワーク ウォッチャーを取得します。</span><span class="sxs-lookup"><span data-stu-id="de03d-260">Gets the specified network watcher by resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAzureReachabilityReport">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.AzureReachabilityReport GetAzureReachabilityReport (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.AzureReachabilityReport GetAzureReachabilityReport(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetAzureReachabilityReport(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAzureReachabilityReport (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As AzureReachabilityReportParameters) As AzureReachabilityReport" />
      <MemberSignature Language="F#" Value="static member GetAzureReachabilityReport : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters -&gt; Microsoft.Azure.Management.Network.Models.AzureReachabilityReport" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetAzureReachabilityReport (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.AzureReachabilityReport</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-261">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-261">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-262">ネットワーク ウォッチャー リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-262">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-263">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-263">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de03d-264">Azure の到達可能性を決定するパラメーターは、構成を報告します。</span><span class="sxs-lookup"><span data-stu-id="de03d-264">Parameters that determine Azure reachability report configuration.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-265">スコアを取得します相対的な待機時間のインターネット サービス プロバイダー指定した場所から Azure リージョンにします。</span><span class="sxs-lookup"><span data-stu-id="de03d-265">Gets the relative latency score for internet service providers from a specified location to Azure regions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAzureReachabilityReportAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.AzureReachabilityReport&gt; GetAzureReachabilityReportAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.AzureReachabilityReport&gt; GetAzureReachabilityReportAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetAzureReachabilityReportAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAzureReachabilityReportAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.AzureReachabilityReport&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetAzureReachabilityReportAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;GetAzureReachabilityReportAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.AzureReachabilityReport&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-266">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-266">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-267">ネットワーク ウォッチャー リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-267">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-268">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-268">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de03d-269">Azure の到達可能性を決定するパラメーターは、構成を報告します。</span><span class="sxs-lookup"><span data-stu-id="de03d-269">Parameters that determine Azure reachability report configuration.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="de03d-270">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="de03d-270">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-271">スコアを取得します相対的な待機時間のインターネット サービス プロバイダー指定した場所から Azure リージョンにします。</span><span class="sxs-lookup"><span data-stu-id="de03d-271">Gets the relative latency score for internet service providers from a specified location to Azure regions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFlowLogStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.FlowLogInformation GetFlowLogStatus (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.FlowLogInformation GetFlowLogStatus(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetFlowLogStatus(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetFlowLogStatus (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As FlowLogStatusParameters) As FlowLogInformation" />
      <MemberSignature Language="F#" Value="static member GetFlowLogStatus : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters -&gt; Microsoft.Azure.Management.Network.Models.FlowLogInformation" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetFlowLogStatus (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.FlowLogInformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-272">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-272">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-273">ネットワーク ウォッチャー リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-273">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-274">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-274">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de03d-275">クエリのフローにリソースを定義するパラメーターはログの状態です。</span><span class="sxs-lookup"><span data-stu-id="de03d-275">Parameters that define a resource to query flow log status.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-276">フローのクエリの状態は、指定されたリソースにログオンします。</span><span class="sxs-lookup"><span data-stu-id="de03d-276">Queries status of flow log on a specified resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFlowLogStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt; GetFlowLogStatusAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt; GetFlowLogStatusAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetFlowLogStatusAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetFlowLogStatusAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetFlowLogStatusAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;GetFlowLogStatusAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-277">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-277">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-278">ネットワーク ウォッチャー リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-278">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-279">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-279">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de03d-280">クエリのフローにリソースを定義するパラメーターはログの状態です。</span><span class="sxs-lookup"><span data-stu-id="de03d-280">Parameters that define a resource to query flow log status.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="de03d-281">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="de03d-281">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-282">フローのクエリの状態は、指定されたリソースにログオンします。</span><span class="sxs-lookup"><span data-stu-id="de03d-282">Queries status of flow log on a specified resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNextHop">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.NextHopResult GetNextHop (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.NextHopParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.NextHopResult GetNextHop(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.NextHopParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetNextHop(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.NextHopParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetNextHop (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As NextHopParameters) As NextHopResult" />
      <MemberSignature Language="F#" Value="static member GetNextHop : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.NextHopParameters -&gt; Microsoft.Azure.Management.Network.Models.NextHopResult" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetNextHop (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.NextHopResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.NextHopParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-283">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-283">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-284">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-284">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-285">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-285">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de03d-286">送信元と送信先のエンドポイントを定義するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="de03d-286">Parameters that define the source and destination endpoint.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-287">指定した VM から次のホップを取得します。</span><span class="sxs-lookup"><span data-stu-id="de03d-287">Gets the next hop from the specified VM.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNextHopAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NextHopResult&gt; GetNextHopAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.NextHopParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.NextHopResult&gt; GetNextHopAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.NextHopParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetNextHopAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.NextHopParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetNextHopAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.NextHopParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NextHopResult&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetNextHopAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;GetNextHopAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NextHopResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.NextHopParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-288">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-288">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-289">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-289">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-290">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-290">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de03d-291">送信元と送信先のエンドポイントを定義するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="de03d-291">Parameters that define the source and destination endpoint.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="de03d-292">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="de03d-292">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-293">指定した VM から次のホップを取得します。</span><span class="sxs-lookup"><span data-stu-id="de03d-293">Gets the next hop from the specified VM.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTopology">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.Topology GetTopology (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.TopologyParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.Topology GetTopology(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.TopologyParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetTopology(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TopologyParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetTopology (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As TopologyParameters) As Topology" />
      <MemberSignature Language="F#" Value="static member GetTopology : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.TopologyParameters -&gt; Microsoft.Azure.Management.Network.Models.Topology" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetTopology (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.Topology</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TopologyParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-294">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-294">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-295">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-295">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-296">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-296">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de03d-297">トポロジの表現を定義するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="de03d-297">Parameters that define the representation of topology.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-298">リソース グループによって、現在のネットワーク トポロジを取得します。</span><span class="sxs-lookup"><span data-stu-id="de03d-298">Gets the current network topology by resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTopologyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.Topology&gt; GetTopologyAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.TopologyParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.Topology&gt; GetTopologyAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.TopologyParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetTopologyAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TopologyParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetTopologyAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.TopologyParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.Topology&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetTopologyAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;GetTopologyAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.Topology&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TopologyParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-299">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-299">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-300">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-300">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-301">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-301">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de03d-302">トポロジの表現を定義するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="de03d-302">Parameters that define the representation of topology.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="de03d-303">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="de03d-303">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-304">リソース グループによって、現在のネットワーク トポロジを取得します。</span><span class="sxs-lookup"><span data-stu-id="de03d-304">Gets the current network topology by resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTroubleshooting">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.TroubleshootingResult GetTroubleshooting (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.TroubleshootingParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.TroubleshootingResult GetTroubleshooting(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.TroubleshootingParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetTroubleshooting(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TroubleshootingParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetTroubleshooting (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As TroubleshootingParameters) As TroubleshootingResult" />
      <MemberSignature Language="F#" Value="static member GetTroubleshooting : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.TroubleshootingParameters -&gt; Microsoft.Azure.Management.Network.Models.TroubleshootingResult" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetTroubleshooting (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.TroubleshootingResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TroubleshootingParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-305">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-305">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-306">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-306">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-307">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-307">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de03d-308">トラブルシューティングのリソースを定義するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="de03d-308">Parameters that define the resource to troubleshoot.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-309">指定したリソースに対するトラブルシューティングを開始します。</span><span class="sxs-lookup"><span data-stu-id="de03d-309">Initiate troubleshooting on a specified resource</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTroubleshootingAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt; GetTroubleshootingAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.TroubleshootingParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt; GetTroubleshootingAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.TroubleshootingParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetTroubleshootingAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TroubleshootingParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetTroubleshootingAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.TroubleshootingParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetTroubleshootingAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;GetTroubleshootingAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TroubleshootingParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-310">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-310">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-311">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-311">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-312">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-312">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de03d-313">トラブルシューティングのリソースを定義するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="de03d-313">Parameters that define the resource to troubleshoot.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="de03d-314">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="de03d-314">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-315">指定したリソースに対するトラブルシューティングを開始します。</span><span class="sxs-lookup"><span data-stu-id="de03d-315">Initiate troubleshooting on a specified resource</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTroubleshootingResult">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.TroubleshootingResult GetTroubleshootingResult (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.TroubleshootingResult GetTroubleshootingResult(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetTroubleshootingResult(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetTroubleshootingResult (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As QueryTroubleshootingParameters) As TroubleshootingResult" />
      <MemberSignature Language="F#" Value="static member GetTroubleshootingResult : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters -&gt; Microsoft.Azure.Management.Network.Models.TroubleshootingResult" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetTroubleshootingResult (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.TroubleshootingResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-316">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-316">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-317">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-317">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-318">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-318">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de03d-319">クエリのトラブルシューティングの結果にリソースを定義するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="de03d-319">Parameters that define the resource to query the troubleshooting result.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-320">指定したリソースに対して最後に完了したトラブルシューティングの結果を取得します。</span><span class="sxs-lookup"><span data-stu-id="de03d-320">Get the last completed troubleshooting result on a specified resource</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTroubleshootingResultAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt; GetTroubleshootingResultAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt; GetTroubleshootingResultAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetTroubleshootingResultAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetTroubleshootingResultAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetTroubleshootingResultAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;GetTroubleshootingResultAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-321">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-321">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-322">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-322">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-323">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-323">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de03d-324">クエリのトラブルシューティングの結果にリソースを定義するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="de03d-324">Parameters that define the resource to query the troubleshooting result.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="de03d-325">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="de03d-325">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-326">指定したリソースに対して最後に完了したトラブルシューティングの結果を取得します。</span><span class="sxs-lookup"><span data-stu-id="de03d-326">Get the last completed troubleshooting result on a specified resource</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVMSecurityRules">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult GetVMSecurityRules (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult GetVMSecurityRules(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetVMSecurityRules(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetVMSecurityRules (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As SecurityGroupViewParameters) As SecurityGroupViewResult" />
      <MemberSignature Language="F#" Value="static member GetVMSecurityRules : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters -&gt; Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetVMSecurityRules (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-327">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-327">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-328">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-328">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-329">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-329">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de03d-330">セキュリティ グループをチェックする VM を定義するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="de03d-330">Parameters that define the VM to check security groups for.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-331">指定した VM で構成され、有効なセキュリティ グループの規則を取得します。</span><span class="sxs-lookup"><span data-stu-id="de03d-331">Gets the configured and effective security group rules on the specified VM.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVMSecurityRulesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult&gt; GetVMSecurityRulesAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult&gt; GetVMSecurityRulesAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetVMSecurityRulesAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetVMSecurityRulesAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetVMSecurityRulesAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;GetVMSecurityRulesAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-332">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-332">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-333">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-333">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-334">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-334">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de03d-335">セキュリティ グループをチェックする VM を定義するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="de03d-335">Parameters that define the VM to check security groups for.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="de03d-336">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="de03d-336">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-337">指定した VM で構成され、有効なセキュリティ グループの規則を取得します。</span><span class="sxs-lookup"><span data-stu-id="de03d-337">Gets the configured and effective security group rules on the specified VM.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt; List (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt; List(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.List(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As INetworkWatchersOperations, resourceGroupName As String) As IEnumerable(Of NetworkWatcher)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string -&gt; seq&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.List (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-338">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-338">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-339">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-339">The name of the resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-340">リソース グループによってすべてのネットワーク監視を取得します。</span><span class="sxs-lookup"><span data-stu-id="de03d-340">Gets all network watchers by resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAll">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt; ListAll (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt; ListAll(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.ListAll(Microsoft.Azure.Management.Network.INetworkWatchersOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAll (operations As INetworkWatchersOperations) As IEnumerable(Of NetworkWatcher)" />
      <MemberSignature Language="F#" Value="static member ListAll : Microsoft.Azure.Management.Network.INetworkWatchersOperations -&gt; seq&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.ListAll operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-341">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-341">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-342">サブスクリプションによってすべてのネットワーク監視を取得します。</span><span class="sxs-lookup"><span data-stu-id="de03d-342">Gets all network watchers by subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt; ListAllAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt; ListAllAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.ListAllAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.ListAllAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;ListAllAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-343">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-343">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="de03d-344">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="de03d-344">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-345">サブスクリプションによってすべてのネットワーク監視を取得します。</span><span class="sxs-lookup"><span data-stu-id="de03d-345">Gets all network watchers by subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.ListAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;ListAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-346">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-346">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-347">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-347">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="de03d-348">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="de03d-348">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-349">リソース グループによってすべてのネットワーク監視を取得します。</span><span class="sxs-lookup"><span data-stu-id="de03d-349">Gets all network watchers by resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAvailableProviders">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.AvailableProvidersList ListAvailableProviders (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.AvailableProvidersList ListAvailableProviders(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.ListAvailableProviders(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAvailableProviders (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As AvailableProvidersListParameters) As AvailableProvidersList" />
      <MemberSignature Language="F#" Value="static member ListAvailableProviders : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters -&gt; Microsoft.Azure.Management.Network.Models.AvailableProvidersList" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.ListAvailableProviders (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.AvailableProvidersList</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-350">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-350">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-351">ネットワーク ウォッチャー リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-351">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-352">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-352">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de03d-353">使用可能なプロバイダーの一覧の範囲のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="de03d-353">Parameters that scope the list of available providers.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-354">指定された Azure の地域の利用可能なインターネット サービス プロバイダーをすべて一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="de03d-354">Lists all available internet service providers for a specified Azure region.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAvailableProvidersAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.AvailableProvidersList&gt; ListAvailableProvidersAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.AvailableProvidersList&gt; ListAvailableProvidersAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.ListAvailableProvidersAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAvailableProvidersAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.AvailableProvidersList&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.ListAvailableProvidersAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;ListAvailableProvidersAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.AvailableProvidersList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-355">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-355">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-356">ネットワーク ウォッチャー リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-356">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-357">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-357">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de03d-358">使用可能なプロバイダーの一覧の範囲のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="de03d-358">Parameters that scope the list of available providers.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="de03d-359">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="de03d-359">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-360">指定された Azure の地域の利用可能なインターネット サービス プロバイダーをすべて一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="de03d-360">Lists all available internet service providers for a specified Azure region.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetFlowLogConfiguration">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.FlowLogInformation SetFlowLogConfiguration (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.FlowLogInformation parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.FlowLogInformation SetFlowLogConfiguration(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.FlowLogInformation parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.SetFlowLogConfiguration(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.FlowLogInformation)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SetFlowLogConfiguration (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As FlowLogInformation) As FlowLogInformation" />
      <MemberSignature Language="F#" Value="static member SetFlowLogConfiguration : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.FlowLogInformation -&gt; Microsoft.Azure.Management.Network.Models.FlowLogInformation" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.SetFlowLogConfiguration (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.FlowLogInformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.FlowLogInformation" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-361">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-361">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-362">ネットワーク ウォッチャー リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-362">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-363">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-363">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de03d-364">フローのログの構成を定義するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="de03d-364">Parameters that define the configuration of flow log.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-365">指定されたリソースのフローのログを構成します。</span><span class="sxs-lookup"><span data-stu-id="de03d-365">Configures flow log on a specified resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetFlowLogConfigurationAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt; SetFlowLogConfigurationAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.FlowLogInformation parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt; SetFlowLogConfigurationAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.FlowLogInformation parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.SetFlowLogConfigurationAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.FlowLogInformation,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SetFlowLogConfigurationAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.FlowLogInformation * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.SetFlowLogConfigurationAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;SetFlowLogConfigurationAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.FlowLogInformation" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-366">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-366">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-367">ネットワーク ウォッチャー リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-367">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-368">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-368">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de03d-369">フローのログの構成を定義するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="de03d-369">Parameters that define the configuration of flow log.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="de03d-370">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="de03d-370">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-371">指定されたリソースのフローのログを構成します。</span><span class="sxs-lookup"><span data-stu-id="de03d-371">Configures flow log on a specified resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTags">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.NetworkWatcher UpdateTags (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.TagsObject parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.NetworkWatcher UpdateTags(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.UpdateTags(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpdateTags (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As TagsObject) As NetworkWatcher" />
      <MemberSignature Language="F#" Value="static member UpdateTags : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject -&gt; Microsoft.Azure.Management.Network.Models.NetworkWatcher" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.UpdateTags (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.NetworkWatcher</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-372">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-372">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-373">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-373">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-374">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-374">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de03d-375">ネットワーク ウォッチャー タグを更新する指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="de03d-375">Parameters supplied to update network watcher tags.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-376">ネットワーク ウォッチャー タグを更新します。</span><span class="sxs-lookup"><span data-stu-id="de03d-376">Updates a network watcher tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTagsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt; UpdateTagsAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.TagsObject parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt; UpdateTagsAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.UpdateTagsAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateTagsAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.UpdateTagsAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;UpdateTagsAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-377">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-377">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-378">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-378">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-379">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-379">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de03d-380">ネットワーク ウォッチャー タグを更新する指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="de03d-380">Parameters supplied to update network watcher tags.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="de03d-381">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="de03d-381">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-382">ネットワーク ウォッチャー タグを更新します。</span><span class="sxs-lookup"><span data-stu-id="de03d-382">Updates a network watcher tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VerifyIPFlow">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult VerifyIPFlow (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult VerifyIPFlow(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.VerifyIPFlow(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function VerifyIPFlow (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As VerificationIPFlowParameters) As VerificationIPFlowResult" />
      <MemberSignature Language="F#" Value="static member VerifyIPFlow : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters -&gt; Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.VerifyIPFlow (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-383">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-383">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-384">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-384">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-385">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-385">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de03d-386">検証する IP フローを定義するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="de03d-386">Parameters that define the IP flow to be verified.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-387">現在構成されている NSG ルールを指定した位置に指定した VM から IP フローを確認します。</span><span class="sxs-lookup"><span data-stu-id="de03d-387">Verify IP flow from the specified VM to a location given the currently configured NSG rules.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VerifyIPFlowAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult&gt; VerifyIPFlowAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult&gt; VerifyIPFlowAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.VerifyIPFlowAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member VerifyIPFlowAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.VerifyIPFlowAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;VerifyIPFlowAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de03d-388">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de03d-388">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de03d-389">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-389">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="de03d-390">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="de03d-390">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de03d-391">検証する IP フローを定義するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="de03d-391">Parameters that define the IP flow to be verified.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="de03d-392">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="de03d-392">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de03d-393">現在構成されている NSG ルールを指定した位置に指定した VM から IP フローを確認します。</span><span class="sxs-lookup"><span data-stu-id="de03d-393">Verify IP flow from the specified VM to a location given the currently configured NSG rules.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>