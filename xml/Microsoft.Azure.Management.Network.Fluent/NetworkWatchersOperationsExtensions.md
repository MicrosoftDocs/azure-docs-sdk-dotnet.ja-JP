<Type Name="NetworkWatchersOperationsExtensions" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class NetworkWatchersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit NetworkWatchersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module NetworkWatchersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type NetworkWatchersOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="fd270-101">NetworkWatchersOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="fd270-101">Extension methods for NetworkWatchersOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCheckConnectivityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityInformationInner&gt; BeginCheckConnectivityAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityInformationInner&gt; BeginCheckConnectivityAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginCheckConnectivityAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCheckConnectivityAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityInformationInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginCheckConnectivityAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;BeginCheckConnectivityAsync&gt;d__22))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityInformationInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="networkWatcherName">To be added.</param>
        <param name="parameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, networkWatcherName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;BeginDeleteAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fd270-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fd270-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fd270-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fd270-103">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="fd270-104">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="fd270-104">The name of the network watcher.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd270-105">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fd270-105">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd270-106">指定したネットワーク監視リソースを削除します。</span><span class="sxs-lookup"><span data-stu-id="fd270-106">Deletes the specified network watcher resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetFlowLogStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner&gt; BeginGetFlowLogStatusAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, string targetResourceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner&gt; BeginGetFlowLogStatusAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, string targetResourceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginGetFlowLogStatusAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetFlowLogStatusAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginGetFlowLogStatusAsync (operations, resourceGroupName, networkWatcherName, targetResourceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;BeginGetFlowLogStatusAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="targetResourceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fd270-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fd270-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fd270-108">ネットワーク ウォッチャー リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fd270-108">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="fd270-109">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="fd270-109">The name of the network watcher resource.</span></span>
            </param>
        <param name="targetResourceId">
            <span data-ttu-id="fd270-110">ターゲット リソースでは、フローのログ記録の状態を取得する場所です。</span><span class="sxs-lookup"><span data-stu-id="fd270-110">The target resource where getting the flow logging status.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd270-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fd270-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd270-112">フローのクエリの状態は、指定されたリソースにログオンします。</span><span class="sxs-lookup"><span data-stu-id="fd270-112">Queries status of flow log on a specified resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetNextHopAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NextHopResultInner&gt; BeginGetNextHopAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.NextHopResultInner&gt; BeginGetNextHopAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginGetNextHopAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetNextHopAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NextHopResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginGetNextHopAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;BeginGetNextHopAsync&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NextHopResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fd270-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fd270-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fd270-114">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fd270-114">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="fd270-115">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="fd270-115">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fd270-116">送信元と送信先のエンドポイントを定義するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="fd270-116">Parameters that define the source and destination endpoint.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd270-117">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fd270-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd270-118">指定した VM から次のホップを取得します。</span><span class="sxs-lookup"><span data-stu-id="fd270-118">Gets the next hop from the specified VM.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetTroubleshootingAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner&gt; BeginGetTroubleshootingAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner&gt; BeginGetTroubleshootingAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginGetTroubleshootingAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetTroubleshootingAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginGetTroubleshootingAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;BeginGetTroubleshootingAsync&gt;d__18))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fd270-119">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fd270-119">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fd270-120">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fd270-120">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="fd270-121">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="fd270-121">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fd270-122">トラブルシューティングのリソースを定義するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="fd270-122">Parameters that define the resource to troubleshoot.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd270-123">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fd270-123">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd270-124">指定したリソースに対するトラブルシューティングを開始します。</span><span class="sxs-lookup"><span data-stu-id="fd270-124">Initiate troubleshooting on a specified resource</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetTroubleshootingResultAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner&gt; BeginGetTroubleshootingResultAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, string targetResourceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner&gt; BeginGetTroubleshootingResultAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, string targetResourceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginGetTroubleshootingResultAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetTroubleshootingResultAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginGetTroubleshootingResultAsync (operations, resourceGroupName, networkWatcherName, targetResourceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;BeginGetTroubleshootingResultAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="targetResourceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fd270-125">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fd270-125">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fd270-126">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fd270-126">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="fd270-127">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="fd270-127">The name of the network watcher resource.</span></span>
            </param>
        <param name="targetResourceId">
            <span data-ttu-id="fd270-128">クエリのトラブルシューティングの結果をターゲット リソース ID です。</span><span class="sxs-lookup"><span data-stu-id="fd270-128">The target resource ID to query the troubleshooting result.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd270-129">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fd270-129">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd270-130">指定したリソースに対して最後に完了したトラブルシューティングの結果を取得します。</span><span class="sxs-lookup"><span data-stu-id="fd270-130">Get the last completed troubleshooting result on a specified resource</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetVMSecurityRulesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupViewResultInner&gt; BeginGetVMSecurityRulesAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, string targetResourceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupViewResultInner&gt; BeginGetVMSecurityRulesAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, string targetResourceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginGetVMSecurityRulesAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetVMSecurityRulesAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupViewResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginGetVMSecurityRulesAsync (operations, resourceGroupName, networkWatcherName, targetResourceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;BeginGetVMSecurityRulesAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupViewResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="targetResourceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fd270-131">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fd270-131">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fd270-132">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fd270-132">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="fd270-133">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="fd270-133">The name of the network watcher.</span></span>
            </param>
        <param name="targetResourceId">
            <span data-ttu-id="fd270-134">ターゲットの VM の ID です。</span><span class="sxs-lookup"><span data-stu-id="fd270-134">ID of the target VM.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd270-135">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fd270-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd270-136">指定した VM で構成され、有効なセキュリティ グループの規則を取得します。</span><span class="sxs-lookup"><span data-stu-id="fd270-136">Gets the configured and effective security group rules on the specified VM.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetFlowLogConfigurationAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner&gt; BeginSetFlowLogConfigurationAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner&gt; BeginSetFlowLogConfigurationAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginSetFlowLogConfigurationAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginSetFlowLogConfigurationAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginSetFlowLogConfigurationAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;BeginSetFlowLogConfigurationAsync&gt;d__20))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fd270-137">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fd270-137">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fd270-138">ネットワーク ウォッチャー リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fd270-138">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="fd270-139">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="fd270-139">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fd270-140">フローのログの構成を定義するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="fd270-140">Parameters that define the configuration of flow log.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd270-141">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fd270-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd270-142">指定されたリソースのフローのログを構成します。</span><span class="sxs-lookup"><span data-stu-id="fd270-142">Configures flow log on a specified resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginVerifyIPFlowAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowResultInner&gt; BeginVerifyIPFlowAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowResultInner&gt; BeginVerifyIPFlowAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginVerifyIPFlowAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginVerifyIPFlowAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginVerifyIPFlowAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;BeginVerifyIPFlowAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fd270-143">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fd270-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fd270-144">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fd270-144">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="fd270-145">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="fd270-145">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fd270-146">検証する IP フローを定義するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="fd270-146">Parameters that define the IP flow to be verified.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd270-147">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fd270-147">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd270-148">現在構成されている NSG ルールを指定した位置に指定した VM から IP フローを確認します。</span><span class="sxs-lookup"><span data-stu-id="fd270-148">Verify IP flow from the specified VM to a location given the currently configured NSG rules.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckConnectivityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityInformationInner&gt; CheckConnectivityAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityInformationInner&gt; CheckConnectivityAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.CheckConnectivityAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckConnectivityAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityInformationInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.CheckConnectivityAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;CheckConnectivityAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityInformationInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="networkWatcherName">To be added.</param>
        <param name="parameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fd270-149">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fd270-149">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fd270-150">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fd270-150">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="fd270-151">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="fd270-151">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fd270-152">ネットワーク ウォッチャー リソースを定義するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="fd270-152">Parameters that define the network watcher resource.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd270-153">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fd270-153">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd270-154">作成するか、指定されたリソース グループにネットワーク ウォッチャーを更新します。</span><span class="sxs-lookup"><span data-stu-id="fd270-154">Creates or updates a network watcher in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.DeleteAsync (operations, resourceGroupName, networkWatcherName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;DeleteAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fd270-155">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fd270-155">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fd270-156">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fd270-156">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="fd270-157">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="fd270-157">The name of the network watcher.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd270-158">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fd270-158">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd270-159">指定したネットワーク監視リソースを削除します。</span><span class="sxs-lookup"><span data-stu-id="fd270-159">Deletes the specified network watcher resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner&gt; GetAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner&gt; GetAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.GetAsync (operations, resourceGroupName, networkWatcherName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fd270-160">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fd270-160">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fd270-161">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fd270-161">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="fd270-162">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="fd270-162">The name of the network watcher.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd270-163">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fd270-163">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd270-164">リソース グループによって指定されたネットワーク ウォッチャーを取得します。</span><span class="sxs-lookup"><span data-stu-id="fd270-164">Gets the specified network watcher by resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFlowLogStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner&gt; GetFlowLogStatusAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, string targetResourceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner&gt; GetFlowLogStatusAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, string targetResourceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.GetFlowLogStatusAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetFlowLogStatusAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.GetFlowLogStatusAsync (operations, resourceGroupName, networkWatcherName, targetResourceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;GetFlowLogStatusAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="targetResourceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fd270-165">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fd270-165">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fd270-166">ネットワーク ウォッチャー リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fd270-166">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="fd270-167">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="fd270-167">The name of the network watcher resource.</span></span>
            </param>
        <param name="targetResourceId">
            <span data-ttu-id="fd270-168">ターゲット リソースでは、フローのログ記録の状態を取得する場所です。</span><span class="sxs-lookup"><span data-stu-id="fd270-168">The target resource where getting the flow logging status.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd270-169">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fd270-169">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd270-170">フローのクエリの状態は、指定されたリソースにログオンします。</span><span class="sxs-lookup"><span data-stu-id="fd270-170">Queries status of flow log on a specified resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNextHopAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NextHopResultInner&gt; GetNextHopAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.NextHopResultInner&gt; GetNextHopAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.GetNextHopAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetNextHopAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NextHopResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.GetNextHopAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;GetNextHopAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NextHopResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fd270-171">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fd270-171">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fd270-172">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fd270-172">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="fd270-173">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="fd270-173">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fd270-174">送信元と送信先のエンドポイントを定義するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="fd270-174">Parameters that define the source and destination endpoint.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd270-175">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fd270-175">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd270-176">指定した VM から次のホップを取得します。</span><span class="sxs-lookup"><span data-stu-id="fd270-176">Gets the next hop from the specified VM.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTopologyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.TopologyInner&gt; GetTopologyAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, string targetResourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.TopologyInner&gt; GetTopologyAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, string targetResourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.GetTopologyAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetTopologyAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.TopologyInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.GetTopologyAsync (operations, resourceGroupName, networkWatcherName, targetResourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;GetTopologyAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.TopologyInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="targetResourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fd270-177">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fd270-177">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fd270-178">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fd270-178">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="fd270-179">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="fd270-179">The name of the network watcher.</span></span>
            </param>
        <param name="targetResourceGroupName">
            <span data-ttu-id="fd270-180">トポロジを実行するターゲット リソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="fd270-180">The name of the target resource group to perform topology on.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd270-181">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fd270-181">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd270-182">リソース グループによって、現在のネットワーク トポロジを取得します。</span><span class="sxs-lookup"><span data-stu-id="fd270-182">Gets the current network topology by resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTroubleshootingAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner&gt; GetTroubleshootingAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner&gt; GetTroubleshootingAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.GetTroubleshootingAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetTroubleshootingAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.GetTroubleshootingAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;GetTroubleshootingAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fd270-183">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fd270-183">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fd270-184">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fd270-184">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="fd270-185">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="fd270-185">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fd270-186">トラブルシューティングのリソースを定義するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="fd270-186">Parameters that define the resource to troubleshoot.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd270-187">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fd270-187">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd270-188">指定したリソースに対するトラブルシューティングを開始します。</span><span class="sxs-lookup"><span data-stu-id="fd270-188">Initiate troubleshooting on a specified resource</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTroubleshootingResultAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner&gt; GetTroubleshootingResultAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, string targetResourceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner&gt; GetTroubleshootingResultAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, string targetResourceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.GetTroubleshootingResultAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetTroubleshootingResultAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.GetTroubleshootingResultAsync (operations, resourceGroupName, networkWatcherName, targetResourceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;GetTroubleshootingResultAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="targetResourceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fd270-189">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fd270-189">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fd270-190">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fd270-190">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="fd270-191">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="fd270-191">The name of the network watcher resource.</span></span>
            </param>
        <param name="targetResourceId">
            <span data-ttu-id="fd270-192">クエリのトラブルシューティングの結果をターゲット リソース ID です。</span><span class="sxs-lookup"><span data-stu-id="fd270-192">The target resource ID to query the troubleshooting result.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd270-193">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fd270-193">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd270-194">指定したリソースに対して最後に完了したトラブルシューティングの結果を取得します。</span><span class="sxs-lookup"><span data-stu-id="fd270-194">Get the last completed troubleshooting result on a specified resource</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVMSecurityRulesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupViewResultInner&gt; GetVMSecurityRulesAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, string targetResourceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupViewResultInner&gt; GetVMSecurityRulesAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, string targetResourceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.GetVMSecurityRulesAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetVMSecurityRulesAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupViewResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.GetVMSecurityRulesAsync (operations, resourceGroupName, networkWatcherName, targetResourceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;GetVMSecurityRulesAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupViewResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="targetResourceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fd270-195">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fd270-195">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fd270-196">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fd270-196">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="fd270-197">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="fd270-197">The name of the network watcher.</span></span>
            </param>
        <param name="targetResourceId">
            <span data-ttu-id="fd270-198">ターゲットの VM の ID です。</span><span class="sxs-lookup"><span data-stu-id="fd270-198">ID of the target VM.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd270-199">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fd270-199">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd270-200">指定した VM で構成され、有効なセキュリティ グループの規則を取得します。</span><span class="sxs-lookup"><span data-stu-id="fd270-200">Gets the configured and effective security group rules on the specified VM.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner&gt;&gt; ListAllAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner&gt;&gt; ListAllAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.ListAllAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.ListAllAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;ListAllAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fd270-201">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fd270-201">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd270-202">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fd270-202">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd270-203">サブスクリプションによってすべてのネットワーク監視を取得します。</span><span class="sxs-lookup"><span data-stu-id="fd270-203">Gets all network watchers by subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.ListAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;ListAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fd270-204">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fd270-204">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fd270-205">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fd270-205">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd270-206">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fd270-206">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd270-207">リソース グループによってすべてのネットワーク監視を取得します。</span><span class="sxs-lookup"><span data-stu-id="fd270-207">Gets all network watchers by resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetFlowLogConfigurationAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner&gt; SetFlowLogConfigurationAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner&gt; SetFlowLogConfigurationAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.SetFlowLogConfigurationAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SetFlowLogConfigurationAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.SetFlowLogConfigurationAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;SetFlowLogConfigurationAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fd270-208">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fd270-208">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fd270-209">ネットワーク ウォッチャー リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fd270-209">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="fd270-210">ネットワーク ウォッチャー リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="fd270-210">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fd270-211">フローのログの構成を定義するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="fd270-211">Parameters that define the configuration of flow log.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd270-212">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fd270-212">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd270-213">指定されたリソースのフローのログを構成します。</span><span class="sxs-lookup"><span data-stu-id="fd270-213">Configures flow log on a specified resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VerifyIPFlowAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowResultInner&gt; VerifyIPFlowAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowResultInner&gt; VerifyIPFlowAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.VerifyIPFlowAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member VerifyIPFlowAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.VerifyIPFlowAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;VerifyIPFlowAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fd270-214">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fd270-214">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fd270-215">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fd270-215">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="fd270-216">ネットワーク ウォッチャーの名前。</span><span class="sxs-lookup"><span data-stu-id="fd270-216">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fd270-217">検証する IP フローを定義するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="fd270-217">Parameters that define the IP flow to be verified.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd270-218">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fd270-218">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd270-219">現在構成されている NSG ルールを指定した位置に指定した VM から IP フローを確認します。</span><span class="sxs-lookup"><span data-stu-id="fd270-219">Verify IP flow from the specified VM to a location given the currently configured NSG rules.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>