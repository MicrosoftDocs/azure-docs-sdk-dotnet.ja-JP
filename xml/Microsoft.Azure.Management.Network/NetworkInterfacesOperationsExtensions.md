<Type Name="NetworkInterfacesOperationsExtensions" FullName="Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class NetworkInterfacesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit NetworkInterfacesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module NetworkInterfacesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type NetworkInterfacesOperationsExtensions = class" />
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
            <span data-ttu-id="8b00a-101">NetworkInterfacesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="8b00a-101">Extension methods for NetworkInterfacesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.NetworkInterface BeginCreateOrUpdate (this Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName, Microsoft.Azure.Management.Network.Models.NetworkInterface parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.NetworkInterface BeginCreateOrUpdate(class Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName, class Microsoft.Azure.Management.Network.Models.NetworkInterface parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Network.INetworkInterfacesOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.NetworkInterface)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As INetworkInterfacesOperations, resourceGroupName As String, networkInterfaceName As String, parameters As NetworkInterface) As NetworkInterface" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Network.INetworkInterfacesOperations * string * string * Microsoft.Azure.Management.Network.Models.NetworkInterface -&gt; Microsoft.Azure.Management.Network.Models.NetworkInterface" Usage="Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, networkInterfaceName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.NetworkInterface</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.NetworkInterface" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b00a-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8b00a-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8b00a-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-103">The name of the resource group.</span></span>
            </param>
        <param name="networkInterfaceName">
            <span data-ttu-id="8b00a-104">ネットワーク インターフェイスの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-104">The name of the network interface.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="8b00a-105">作成または更新のネットワーク インターフェイスの操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="8b00a-105">Parameters supplied to the create or update network interface operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b00a-106">作成するか、ネットワーク インターフェイスを更新します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-106">Creates or updates a network interface.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName, Microsoft.Azure.Management.Network.Models.NetworkInterface parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterface&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName, class Microsoft.Azure.Management.Network.Models.NetworkInterface parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.INetworkInterfacesOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.NetworkInterface,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.INetworkInterfacesOperations * string * string * Microsoft.Azure.Management.Network.Models.NetworkInterface * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;" Usage="Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, networkInterfaceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.NetworkInterface" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b00a-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8b00a-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8b00a-108">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-108">The name of the resource group.</span></span>
            </param>
        <param name="networkInterfaceName">
            <span data-ttu-id="8b00a-109">ネットワーク インターフェイスの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-109">The name of the network interface.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="8b00a-110">作成または更新のネットワーク インターフェイスの操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="8b00a-110">Parameters supplied to the create or update network interface operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8b00a-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8b00a-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b00a-112">作成するか、ネットワーク インターフェイスを更新します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-112">Creates or updates a network interface.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Network.INetworkInterfacesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As INetworkInterfacesOperations, resourceGroupName As String, networkInterfaceName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Network.INetworkInterfacesOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.BeginDelete (operations, resourceGroupName, networkInterfaceName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b00a-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8b00a-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8b00a-114">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-114">The name of the resource group.</span></span>
            </param>
        <param name="networkInterfaceName">
            <span data-ttu-id="8b00a-115">ネットワーク インターフェイスの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-115">The name of the network interface.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b00a-116">指定したネットワーク インターフェイスを削除します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-116">Deletes the specified network interface.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.INetworkInterfacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.INetworkInterfacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, networkInterfaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b00a-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8b00a-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8b00a-118">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-118">The name of the resource group.</span></span>
            </param>
        <param name="networkInterfaceName">
            <span data-ttu-id="8b00a-119">ネットワーク インターフェイスの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-119">The name of the network interface.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8b00a-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8b00a-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b00a-121">指定したネットワーク インターフェイスを削除します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-121">Deletes the specified network interface.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetEffectiveRouteTable">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.EffectiveRouteListResult BeginGetEffectiveRouteTable (this Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.EffectiveRouteListResult BeginGetEffectiveRouteTable(class Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.BeginGetEffectiveRouteTable(Microsoft.Azure.Management.Network.INetworkInterfacesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginGetEffectiveRouteTable (operations As INetworkInterfacesOperations, resourceGroupName As String, networkInterfaceName As String) As EffectiveRouteListResult" />
      <MemberSignature Language="F#" Value="static member BeginGetEffectiveRouteTable : Microsoft.Azure.Management.Network.INetworkInterfacesOperations * string * string -&gt; Microsoft.Azure.Management.Network.Models.EffectiveRouteListResult" Usage="Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.BeginGetEffectiveRouteTable (operations, resourceGroupName, networkInterfaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.EffectiveRouteListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b00a-122">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8b00a-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8b00a-123">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-123">The name of the resource group.</span></span>
            </param>
        <param name="networkInterfaceName">
            <span data-ttu-id="8b00a-124">ネットワーク インターフェイスの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-124">The name of the network interface.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b00a-125">ネットワーク インターフェイスに適用されるすべてのルート テーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-125">Gets all route tables applied to a network interface.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetEffectiveRouteTableAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.EffectiveRouteListResult&gt; BeginGetEffectiveRouteTableAsync (this Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.EffectiveRouteListResult&gt; BeginGetEffectiveRouteTableAsync(class Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.BeginGetEffectiveRouteTableAsync(Microsoft.Azure.Management.Network.INetworkInterfacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetEffectiveRouteTableAsync : Microsoft.Azure.Management.Network.INetworkInterfacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.EffectiveRouteListResult&gt;" Usage="Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.BeginGetEffectiveRouteTableAsync (operations, resourceGroupName, networkInterfaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions/&lt;BeginGetEffectiveRouteTableAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.EffectiveRouteListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b00a-126">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8b00a-126">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8b00a-127">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-127">The name of the resource group.</span></span>
            </param>
        <param name="networkInterfaceName">
            <span data-ttu-id="8b00a-128">ネットワーク インターフェイスの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-128">The name of the network interface.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8b00a-129">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8b00a-129">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b00a-130">ネットワーク インターフェイスに適用されるすべてのルート テーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-130">Gets all route tables applied to a network interface.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListEffectiveNetworkSecurityGroups">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroupListResult BeginListEffectiveNetworkSecurityGroups (this Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroupListResult BeginListEffectiveNetworkSecurityGroups(class Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.BeginListEffectiveNetworkSecurityGroups(Microsoft.Azure.Management.Network.INetworkInterfacesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginListEffectiveNetworkSecurityGroups (operations As INetworkInterfacesOperations, resourceGroupName As String, networkInterfaceName As String) As EffectiveNetworkSecurityGroupListResult" />
      <MemberSignature Language="F#" Value="static member BeginListEffectiveNetworkSecurityGroups : Microsoft.Azure.Management.Network.INetworkInterfacesOperations * string * string -&gt; Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroupListResult" Usage="Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.BeginListEffectiveNetworkSecurityGroups (operations, resourceGroupName, networkInterfaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroupListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b00a-131">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8b00a-131">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8b00a-132">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-132">The name of the resource group.</span></span>
            </param>
        <param name="networkInterfaceName">
            <span data-ttu-id="8b00a-133">ネットワーク インターフェイスの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-133">The name of the network interface.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b00a-134">ネットワーク インターフェイスに適用されるすべてのネットワーク セキュリティ グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-134">Gets all network security groups applied to a network interface.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListEffectiveNetworkSecurityGroupsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroupListResult&gt; BeginListEffectiveNetworkSecurityGroupsAsync (this Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroupListResult&gt; BeginListEffectiveNetworkSecurityGroupsAsync(class Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.BeginListEffectiveNetworkSecurityGroupsAsync(Microsoft.Azure.Management.Network.INetworkInterfacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginListEffectiveNetworkSecurityGroupsAsync : Microsoft.Azure.Management.Network.INetworkInterfacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroupListResult&gt;" Usage="Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.BeginListEffectiveNetworkSecurityGroupsAsync (operations, resourceGroupName, networkInterfaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions/&lt;BeginListEffectiveNetworkSecurityGroupsAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroupListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b00a-135">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8b00a-135">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8b00a-136">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-136">The name of the resource group.</span></span>
            </param>
        <param name="networkInterfaceName">
            <span data-ttu-id="8b00a-137">ネットワーク インターフェイスの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-137">The name of the network interface.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8b00a-138">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8b00a-138">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b00a-139">ネットワーク インターフェイスに適用されるすべてのネットワーク セキュリティ グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-139">Gets all network security groups applied to a network interface.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateTags">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.NetworkInterface BeginUpdateTags (this Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName, Microsoft.Azure.Management.Network.Models.TagsObject parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.NetworkInterface BeginUpdateTags(class Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.BeginUpdateTags(Microsoft.Azure.Management.Network.INetworkInterfacesOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdateTags (operations As INetworkInterfacesOperations, resourceGroupName As String, networkInterfaceName As String, parameters As TagsObject) As NetworkInterface" />
      <MemberSignature Language="F#" Value="static member BeginUpdateTags : Microsoft.Azure.Management.Network.INetworkInterfacesOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject -&gt; Microsoft.Azure.Management.Network.Models.NetworkInterface" Usage="Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.BeginUpdateTags (operations, resourceGroupName, networkInterfaceName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.NetworkInterface</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b00a-140">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8b00a-140">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8b00a-141">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-141">The name of the resource group.</span></span>
            </param>
        <param name="networkInterfaceName">
            <span data-ttu-id="8b00a-142">ネットワーク インターフェイスの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-142">The name of the network interface.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="8b00a-143">ネットワーク インターフェイスのタグを更新する指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="8b00a-143">Parameters supplied to update network interface tags.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b00a-144">ネットワーク インターフェイスのタグを更新します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-144">Updates a network interface tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateTagsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt; BeginUpdateTagsAsync (this Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName, Microsoft.Azure.Management.Network.Models.TagsObject parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterface&gt; BeginUpdateTagsAsync(class Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.BeginUpdateTagsAsync(Microsoft.Azure.Management.Network.INetworkInterfacesOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateTagsAsync : Microsoft.Azure.Management.Network.INetworkInterfacesOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;" Usage="Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.BeginUpdateTagsAsync (operations, resourceGroupName, networkInterfaceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions/&lt;BeginUpdateTagsAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b00a-145">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8b00a-145">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8b00a-146">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-146">The name of the resource group.</span></span>
            </param>
        <param name="networkInterfaceName">
            <span data-ttu-id="8b00a-147">ネットワーク インターフェイスの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-147">The name of the network interface.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="8b00a-148">ネットワーク インターフェイスのタグを更新する指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="8b00a-148">Parameters supplied to update network interface tags.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8b00a-149">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8b00a-149">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b00a-150">ネットワーク インターフェイスのタグを更新します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-150">Updates a network interface tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.NetworkInterface CreateOrUpdate (this Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName, Microsoft.Azure.Management.Network.Models.NetworkInterface parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.NetworkInterface CreateOrUpdate(class Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName, class Microsoft.Azure.Management.Network.Models.NetworkInterface parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Network.INetworkInterfacesOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.NetworkInterface)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As INetworkInterfacesOperations, resourceGroupName As String, networkInterfaceName As String, parameters As NetworkInterface) As NetworkInterface" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Network.INetworkInterfacesOperations * string * string * Microsoft.Azure.Management.Network.Models.NetworkInterface -&gt; Microsoft.Azure.Management.Network.Models.NetworkInterface" Usage="Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, networkInterfaceName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.NetworkInterface</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.NetworkInterface" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b00a-151">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8b00a-151">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8b00a-152">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-152">The name of the resource group.</span></span>
            </param>
        <param name="networkInterfaceName">
            <span data-ttu-id="8b00a-153">ネットワーク インターフェイスの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-153">The name of the network interface.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="8b00a-154">作成または更新のネットワーク インターフェイスの操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="8b00a-154">Parameters supplied to the create or update network interface operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b00a-155">作成するか、ネットワーク インターフェイスを更新します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-155">Creates or updates a network interface.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName, Microsoft.Azure.Management.Network.Models.NetworkInterface parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterface&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName, class Microsoft.Azure.Management.Network.Models.NetworkInterface parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.INetworkInterfacesOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.NetworkInterface,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.INetworkInterfacesOperations * string * string * Microsoft.Azure.Management.Network.Models.NetworkInterface * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;" Usage="Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, networkInterfaceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.NetworkInterface" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b00a-156">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8b00a-156">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8b00a-157">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-157">The name of the resource group.</span></span>
            </param>
        <param name="networkInterfaceName">
            <span data-ttu-id="8b00a-158">ネットワーク インターフェイスの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-158">The name of the network interface.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="8b00a-159">作成または更新のネットワーク インターフェイスの操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="8b00a-159">Parameters supplied to the create or update network interface operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8b00a-160">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8b00a-160">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b00a-161">作成するか、ネットワーク インターフェイスを更新します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-161">Creates or updates a network interface.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.Delete(Microsoft.Azure.Management.Network.INetworkInterfacesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As INetworkInterfacesOperations, resourceGroupName As String, networkInterfaceName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Network.INetworkInterfacesOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.Delete (operations, resourceGroupName, networkInterfaceName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b00a-162">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8b00a-162">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8b00a-163">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-163">The name of the resource group.</span></span>
            </param>
        <param name="networkInterfaceName">
            <span data-ttu-id="8b00a-164">ネットワーク インターフェイスの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-164">The name of the network interface.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b00a-165">指定したネットワーク インターフェイスを削除します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-165">Deletes the specified network interface.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.INetworkInterfacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.INetworkInterfacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.DeleteAsync (operations, resourceGroupName, networkInterfaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions/&lt;DeleteAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b00a-166">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8b00a-166">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8b00a-167">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-167">The name of the resource group.</span></span>
            </param>
        <param name="networkInterfaceName">
            <span data-ttu-id="8b00a-168">ネットワーク インターフェイスの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-168">The name of the network interface.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8b00a-169">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8b00a-169">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b00a-170">指定したネットワーク インターフェイスを削除します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-170">Deletes the specified network interface.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.NetworkInterface Get (this Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName, string expand = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.NetworkInterface Get(class Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName, string expand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.Get(Microsoft.Azure.Management.Network.INetworkInterfacesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As INetworkInterfacesOperations, resourceGroupName As String, networkInterfaceName As String, Optional expand As String = null) As NetworkInterface" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Network.INetworkInterfacesOperations * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.NetworkInterface" Usage="Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.Get (operations, resourceGroupName, networkInterfaceName, expand)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.NetworkInterface</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b00a-171">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8b00a-171">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8b00a-172">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-172">The name of the resource group.</span></span>
            </param>
        <param name="networkInterfaceName">
            <span data-ttu-id="8b00a-173">ネットワーク インターフェイスの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-173">The name of the network interface.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="8b00a-174">参照されているリソースを展開します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-174">Expands referenced resources.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b00a-175">指定したネットワーク インターフェイスに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-175">Gets information about the specified network interface.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt; GetAsync (this Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterface&gt; GetAsync(class Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.INetworkInterfacesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.INetworkInterfacesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;" Usage="Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.GetAsync (operations, resourceGroupName, networkInterfaceName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b00a-176">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8b00a-176">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8b00a-177">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-177">The name of the resource group.</span></span>
            </param>
        <param name="networkInterfaceName">
            <span data-ttu-id="8b00a-178">ネットワーク インターフェイスの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-178">The name of the network interface.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="8b00a-179">参照されているリソースを展開します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-179">Expands referenced resources.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8b00a-180">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8b00a-180">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b00a-181">指定したネットワーク インターフェイスに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-181">Gets information about the specified network interface.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEffectiveRouteTable">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.EffectiveRouteListResult GetEffectiveRouteTable (this Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.EffectiveRouteListResult GetEffectiveRouteTable(class Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.GetEffectiveRouteTable(Microsoft.Azure.Management.Network.INetworkInterfacesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetEffectiveRouteTable (operations As INetworkInterfacesOperations, resourceGroupName As String, networkInterfaceName As String) As EffectiveRouteListResult" />
      <MemberSignature Language="F#" Value="static member GetEffectiveRouteTable : Microsoft.Azure.Management.Network.INetworkInterfacesOperations * string * string -&gt; Microsoft.Azure.Management.Network.Models.EffectiveRouteListResult" Usage="Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.GetEffectiveRouteTable (operations, resourceGroupName, networkInterfaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.EffectiveRouteListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b00a-182">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8b00a-182">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8b00a-183">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-183">The name of the resource group.</span></span>
            </param>
        <param name="networkInterfaceName">
            <span data-ttu-id="8b00a-184">ネットワーク インターフェイスの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-184">The name of the network interface.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b00a-185">ネットワーク インターフェイスに適用されるすべてのルート テーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-185">Gets all route tables applied to a network interface.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEffectiveRouteTableAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.EffectiveRouteListResult&gt; GetEffectiveRouteTableAsync (this Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.EffectiveRouteListResult&gt; GetEffectiveRouteTableAsync(class Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.GetEffectiveRouteTableAsync(Microsoft.Azure.Management.Network.INetworkInterfacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetEffectiveRouteTableAsync : Microsoft.Azure.Management.Network.INetworkInterfacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.EffectiveRouteListResult&gt;" Usage="Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.GetEffectiveRouteTableAsync (operations, resourceGroupName, networkInterfaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions/&lt;GetEffectiveRouteTableAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.EffectiveRouteListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b00a-186">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8b00a-186">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8b00a-187">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-187">The name of the resource group.</span></span>
            </param>
        <param name="networkInterfaceName">
            <span data-ttu-id="8b00a-188">ネットワーク インターフェイスの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-188">The name of the network interface.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8b00a-189">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8b00a-189">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b00a-190">ネットワーク インターフェイスに適用されるすべてのルート テーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-190">Gets all route tables applied to a network interface.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVirtualMachineScaleSetIpConfiguration">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration GetVirtualMachineScaleSetIpConfiguration (this Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string virtualMachineScaleSetName, string virtualmachineIndex, string networkInterfaceName, string ipConfigurationName, string expand = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration GetVirtualMachineScaleSetIpConfiguration(class Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string virtualMachineScaleSetName, string virtualmachineIndex, string networkInterfaceName, string ipConfigurationName, string expand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.GetVirtualMachineScaleSetIpConfiguration(Microsoft.Azure.Management.Network.INetworkInterfacesOperations,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetVirtualMachineScaleSetIpConfiguration (operations As INetworkInterfacesOperations, resourceGroupName As String, virtualMachineScaleSetName As String, virtualmachineIndex As String, networkInterfaceName As String, ipConfigurationName As String, Optional expand As String = null) As NetworkInterfaceIPConfiguration" />
      <MemberSignature Language="F#" Value="static member GetVirtualMachineScaleSetIpConfiguration : Microsoft.Azure.Management.Network.INetworkInterfacesOperations * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration" Usage="Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.GetVirtualMachineScaleSetIpConfiguration (operations, resourceGroupName, virtualMachineScaleSetName, virtualmachineIndex, networkInterfaceName, ipConfigurationName, expand)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualMachineScaleSetName" Type="System.String" />
        <Parameter Name="virtualmachineIndex" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
        <Parameter Name="ipConfigurationName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b00a-191">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8b00a-191">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8b00a-192">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-192">The name of the resource group.</span></span>
            </param>
        <param name="virtualMachineScaleSetName">
            <span data-ttu-id="8b00a-193">仮想マシン スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-193">The name of the virtual machine scale set.</span></span>
            </param>
        <param name="virtualmachineIndex">
            <span data-ttu-id="8b00a-194">仮想マシンのインデックス。</span><span class="sxs-lookup"><span data-stu-id="8b00a-194">The virtual machine index.</span></span>
            </param>
        <param name="networkInterfaceName">
            <span data-ttu-id="8b00a-195">ネットワーク インターフェイスの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-195">The name of the network interface.</span></span>
            </param>
        <param name="ipConfigurationName">
            <span data-ttu-id="8b00a-196">Ip 構成の名前です。</span><span class="sxs-lookup"><span data-stu-id="8b00a-196">The name of the ip configuration.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="8b00a-197">参照されているリソースを展開します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-197">Expands referenced resources.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b00a-198">仮想マシン スケール セット内の指定したネットワーク インターフェイス ip 構成を取得します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-198">Get the specified network interface ip configuration in a virtual machine scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVirtualMachineScaleSetIpConfigurationAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt; GetVirtualMachineScaleSetIpConfigurationAsync (this Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string virtualMachineScaleSetName, string virtualmachineIndex, string networkInterfaceName, string ipConfigurationName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt; GetVirtualMachineScaleSetIpConfigurationAsync(class Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string virtualMachineScaleSetName, string virtualmachineIndex, string networkInterfaceName, string ipConfigurationName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.GetVirtualMachineScaleSetIpConfigurationAsync(Microsoft.Azure.Management.Network.INetworkInterfacesOperations,System.String,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetVirtualMachineScaleSetIpConfigurationAsync : Microsoft.Azure.Management.Network.INetworkInterfacesOperations * string * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;" Usage="Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.GetVirtualMachineScaleSetIpConfigurationAsync (operations, resourceGroupName, virtualMachineScaleSetName, virtualmachineIndex, networkInterfaceName, ipConfigurationName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions/&lt;GetVirtualMachineScaleSetIpConfigurationAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualMachineScaleSetName" Type="System.String" />
        <Parameter Name="virtualmachineIndex" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
        <Parameter Name="ipConfigurationName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b00a-199">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8b00a-199">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8b00a-200">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-200">The name of the resource group.</span></span>
            </param>
        <param name="virtualMachineScaleSetName">
            <span data-ttu-id="8b00a-201">仮想マシン スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-201">The name of the virtual machine scale set.</span></span>
            </param>
        <param name="virtualmachineIndex">
            <span data-ttu-id="8b00a-202">仮想マシンのインデックス。</span><span class="sxs-lookup"><span data-stu-id="8b00a-202">The virtual machine index.</span></span>
            </param>
        <param name="networkInterfaceName">
            <span data-ttu-id="8b00a-203">ネットワーク インターフェイスの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-203">The name of the network interface.</span></span>
            </param>
        <param name="ipConfigurationName">
            <span data-ttu-id="8b00a-204">Ip 構成の名前です。</span><span class="sxs-lookup"><span data-stu-id="8b00a-204">The name of the ip configuration.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="8b00a-205">参照されているリソースを展開します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-205">Expands referenced resources.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8b00a-206">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8b00a-206">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b00a-207">仮想マシン スケール セット内の指定したネットワーク インターフェイス ip 構成を取得します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-207">Get the specified network interface ip configuration in a virtual machine scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVirtualMachineScaleSetNetworkInterface">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.NetworkInterface GetVirtualMachineScaleSetNetworkInterface (this Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string virtualMachineScaleSetName, string virtualmachineIndex, string networkInterfaceName, string expand = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.NetworkInterface GetVirtualMachineScaleSetNetworkInterface(class Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string virtualMachineScaleSetName, string virtualmachineIndex, string networkInterfaceName, string expand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.GetVirtualMachineScaleSetNetworkInterface(Microsoft.Azure.Management.Network.INetworkInterfacesOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetVirtualMachineScaleSetNetworkInterface (operations As INetworkInterfacesOperations, resourceGroupName As String, virtualMachineScaleSetName As String, virtualmachineIndex As String, networkInterfaceName As String, Optional expand As String = null) As NetworkInterface" />
      <MemberSignature Language="F#" Value="static member GetVirtualMachineScaleSetNetworkInterface : Microsoft.Azure.Management.Network.INetworkInterfacesOperations * string * string * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.NetworkInterface" Usage="Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.GetVirtualMachineScaleSetNetworkInterface (operations, resourceGroupName, virtualMachineScaleSetName, virtualmachineIndex, networkInterfaceName, expand)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.NetworkInterface</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualMachineScaleSetName" Type="System.String" />
        <Parameter Name="virtualmachineIndex" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b00a-208">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8b00a-208">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8b00a-209">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-209">The name of the resource group.</span></span>
            </param>
        <param name="virtualMachineScaleSetName">
            <span data-ttu-id="8b00a-210">仮想マシン スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-210">The name of the virtual machine scale set.</span></span>
            </param>
        <param name="virtualmachineIndex">
            <span data-ttu-id="8b00a-211">仮想マシンのインデックス。</span><span class="sxs-lookup"><span data-stu-id="8b00a-211">The virtual machine index.</span></span>
            </param>
        <param name="networkInterfaceName">
            <span data-ttu-id="8b00a-212">ネットワーク インターフェイスの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-212">The name of the network interface.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="8b00a-213">参照されているリソースを展開します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-213">Expands referenced resources.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b00a-214">仮想マシン スケール セット内にある指定したネットワーク インターフェイスを取得します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-214">Get the specified network interface in a virtual machine scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVirtualMachineScaleSetNetworkInterfaceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt; GetVirtualMachineScaleSetNetworkInterfaceAsync (this Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string virtualMachineScaleSetName, string virtualmachineIndex, string networkInterfaceName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterface&gt; GetVirtualMachineScaleSetNetworkInterfaceAsync(class Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string virtualMachineScaleSetName, string virtualmachineIndex, string networkInterfaceName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.GetVirtualMachineScaleSetNetworkInterfaceAsync(Microsoft.Azure.Management.Network.INetworkInterfacesOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetVirtualMachineScaleSetNetworkInterfaceAsync : Microsoft.Azure.Management.Network.INetworkInterfacesOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;" Usage="Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.GetVirtualMachineScaleSetNetworkInterfaceAsync (operations, resourceGroupName, virtualMachineScaleSetName, virtualmachineIndex, networkInterfaceName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions/&lt;GetVirtualMachineScaleSetNetworkInterfaceAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualMachineScaleSetName" Type="System.String" />
        <Parameter Name="virtualmachineIndex" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b00a-215">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8b00a-215">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8b00a-216">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-216">The name of the resource group.</span></span>
            </param>
        <param name="virtualMachineScaleSetName">
            <span data-ttu-id="8b00a-217">仮想マシン スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-217">The name of the virtual machine scale set.</span></span>
            </param>
        <param name="virtualmachineIndex">
            <span data-ttu-id="8b00a-218">仮想マシンのインデックス。</span><span class="sxs-lookup"><span data-stu-id="8b00a-218">The virtual machine index.</span></span>
            </param>
        <param name="networkInterfaceName">
            <span data-ttu-id="8b00a-219">ネットワーク インターフェイスの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-219">The name of the network interface.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="8b00a-220">参照されているリソースを展開します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-220">Expands referenced resources.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8b00a-221">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8b00a-221">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b00a-222">仮想マシン スケール セット内にある指定したネットワーク インターフェイスを取得します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-222">Get the specified network interface in a virtual machine scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt; List (this Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterface&gt; List(class Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.List(Microsoft.Azure.Management.Network.INetworkInterfacesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As INetworkInterfacesOperations, resourceGroupName As String) As IPage(Of NetworkInterface)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Network.INetworkInterfacesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;" Usage="Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.List (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b00a-223">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8b00a-223">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8b00a-224">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-224">The name of the resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b00a-225">リソース グループ内のすべてのネットワーク インターフェイスを取得します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-225">Gets all network interfaces in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAll">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt; ListAll (this Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterface&gt; ListAll(class Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.ListAll(Microsoft.Azure.Management.Network.INetworkInterfacesOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAll (operations As INetworkInterfacesOperations) As IPage(Of NetworkInterface)" />
      <MemberSignature Language="F#" Value="static member ListAll : Microsoft.Azure.Management.Network.INetworkInterfacesOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;" Usage="Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.ListAll operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfacesOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b00a-226">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8b00a-226">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b00a-227">サブスクリプション内のすべてのネットワーク インターフェイスを取得します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-227">Gets all network interfaces in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;&gt; ListAllAsync (this Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;&gt; ListAllAsync(class Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.ListAllAsync(Microsoft.Azure.Management.Network.INetworkInterfacesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllAsync : Microsoft.Azure.Management.Network.INetworkInterfacesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;&gt;" Usage="Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.ListAllAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions/&lt;ListAllAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b00a-228">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8b00a-228">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8b00a-229">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8b00a-229">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b00a-230">サブスクリプション内のすべてのネットワーク インターフェイスを取得します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-230">Gets all network interfaces in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt; ListAllNext (this Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterface&gt; ListAllNext(class Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.ListAllNext(Microsoft.Azure.Management.Network.INetworkInterfacesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAllNext (operations As INetworkInterfacesOperations, nextPageLink As String) As IPage(Of NetworkInterface)" />
      <MemberSignature Language="F#" Value="static member ListAllNext : Microsoft.Azure.Management.Network.INetworkInterfacesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;" Usage="Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.ListAllNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b00a-231">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8b00a-231">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="8b00a-232">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="8b00a-232">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b00a-233">サブスクリプション内のすべてのネットワーク インターフェイスを取得します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-233">Gets all network interfaces in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;&gt; ListAllNextAsync (this Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;&gt; ListAllNextAsync(class Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.ListAllNextAsync(Microsoft.Azure.Management.Network.INetworkInterfacesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllNextAsync : Microsoft.Azure.Management.Network.INetworkInterfacesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;&gt;" Usage="Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.ListAllNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions/&lt;ListAllNextAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b00a-234">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8b00a-234">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="8b00a-235">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="8b00a-235">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8b00a-236">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8b00a-236">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b00a-237">サブスクリプション内のすべてのネットワーク インターフェイスを取得します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-237">Gets all network interfaces in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.INetworkInterfacesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.INetworkInterfacesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;&gt;" Usage="Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.ListAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions/&lt;ListAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b00a-238">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8b00a-238">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8b00a-239">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-239">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8b00a-240">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8b00a-240">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b00a-241">リソース グループ内のすべてのネットワーク インターフェイスを取得します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-241">Gets all network interfaces in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListEffectiveNetworkSecurityGroups">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroupListResult ListEffectiveNetworkSecurityGroups (this Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroupListResult ListEffectiveNetworkSecurityGroups(class Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.ListEffectiveNetworkSecurityGroups(Microsoft.Azure.Management.Network.INetworkInterfacesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListEffectiveNetworkSecurityGroups (operations As INetworkInterfacesOperations, resourceGroupName As String, networkInterfaceName As String) As EffectiveNetworkSecurityGroupListResult" />
      <MemberSignature Language="F#" Value="static member ListEffectiveNetworkSecurityGroups : Microsoft.Azure.Management.Network.INetworkInterfacesOperations * string * string -&gt; Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroupListResult" Usage="Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.ListEffectiveNetworkSecurityGroups (operations, resourceGroupName, networkInterfaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroupListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b00a-242">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8b00a-242">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8b00a-243">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-243">The name of the resource group.</span></span>
            </param>
        <param name="networkInterfaceName">
            <span data-ttu-id="8b00a-244">ネットワーク インターフェイスの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-244">The name of the network interface.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b00a-245">ネットワーク インターフェイスに適用されるすべてのネットワーク セキュリティ グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-245">Gets all network security groups applied to a network interface.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListEffectiveNetworkSecurityGroupsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroupListResult&gt; ListEffectiveNetworkSecurityGroupsAsync (this Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroupListResult&gt; ListEffectiveNetworkSecurityGroupsAsync(class Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.ListEffectiveNetworkSecurityGroupsAsync(Microsoft.Azure.Management.Network.INetworkInterfacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListEffectiveNetworkSecurityGroupsAsync : Microsoft.Azure.Management.Network.INetworkInterfacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroupListResult&gt;" Usage="Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.ListEffectiveNetworkSecurityGroupsAsync (operations, resourceGroupName, networkInterfaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions/&lt;ListEffectiveNetworkSecurityGroupsAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroupListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b00a-246">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8b00a-246">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8b00a-247">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-247">The name of the resource group.</span></span>
            </param>
        <param name="networkInterfaceName">
            <span data-ttu-id="8b00a-248">ネットワーク インターフェイスの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-248">The name of the network interface.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8b00a-249">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8b00a-249">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b00a-250">ネットワーク インターフェイスに適用されるすべてのネットワーク セキュリティ グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-250">Gets all network security groups applied to a network interface.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt; ListNext (this Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterface&gt; ListNext(class Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.ListNext(Microsoft.Azure.Management.Network.INetworkInterfacesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As INetworkInterfacesOperations, nextPageLink As String) As IPage(Of NetworkInterface)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Network.INetworkInterfacesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;" Usage="Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b00a-251">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8b00a-251">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="8b00a-252">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="8b00a-252">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b00a-253">リソース グループ内のすべてのネットワーク インターフェイスを取得します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-253">Gets all network interfaces in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.INetworkInterfacesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.INetworkInterfacesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;&gt;" Usage="Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions/&lt;ListNextAsync&gt;d__39))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b00a-254">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8b00a-254">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="8b00a-255">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="8b00a-255">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8b00a-256">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8b00a-256">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b00a-257">リソース グループ内のすべてのネットワーク インターフェイスを取得します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-257">Gets all network interfaces in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVirtualMachineScaleSetIpConfigurations">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt; ListVirtualMachineScaleSetIpConfigurations (this Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string virtualMachineScaleSetName, string virtualmachineIndex, string networkInterfaceName, string expand = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt; ListVirtualMachineScaleSetIpConfigurations(class Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string virtualMachineScaleSetName, string virtualmachineIndex, string networkInterfaceName, string expand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.ListVirtualMachineScaleSetIpConfigurations(Microsoft.Azure.Management.Network.INetworkInterfacesOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListVirtualMachineScaleSetIpConfigurations (operations As INetworkInterfacesOperations, resourceGroupName As String, virtualMachineScaleSetName As String, virtualmachineIndex As String, networkInterfaceName As String, Optional expand As String = null) As IPage(Of NetworkInterfaceIPConfiguration)" />
      <MemberSignature Language="F#" Value="static member ListVirtualMachineScaleSetIpConfigurations : Microsoft.Azure.Management.Network.INetworkInterfacesOperations * string * string * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;" Usage="Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.ListVirtualMachineScaleSetIpConfigurations (operations, resourceGroupName, virtualMachineScaleSetName, virtualmachineIndex, networkInterfaceName, expand)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualMachineScaleSetName" Type="System.String" />
        <Parameter Name="virtualmachineIndex" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b00a-258">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8b00a-258">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8b00a-259">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-259">The name of the resource group.</span></span>
            </param>
        <param name="virtualMachineScaleSetName">
            <span data-ttu-id="8b00a-260">仮想マシン スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-260">The name of the virtual machine scale set.</span></span>
            </param>
        <param name="virtualmachineIndex">
            <span data-ttu-id="8b00a-261">仮想マシンのインデックス。</span><span class="sxs-lookup"><span data-stu-id="8b00a-261">The virtual machine index.</span></span>
            </param>
        <param name="networkInterfaceName">
            <span data-ttu-id="8b00a-262">ネットワーク インターフェイスの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-262">The name of the network interface.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="8b00a-263">参照されているリソースを展開します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-263">Expands referenced resources.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b00a-264">仮想マシン スケール セット内の指定したネットワーク インターフェイス ip 構成を取得します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-264">Get the specified network interface ip configuration in a virtual machine scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVirtualMachineScaleSetIpConfigurationsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;&gt; ListVirtualMachineScaleSetIpConfigurationsAsync (this Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string virtualMachineScaleSetName, string virtualmachineIndex, string networkInterfaceName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;&gt; ListVirtualMachineScaleSetIpConfigurationsAsync(class Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string virtualMachineScaleSetName, string virtualmachineIndex, string networkInterfaceName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.ListVirtualMachineScaleSetIpConfigurationsAsync(Microsoft.Azure.Management.Network.INetworkInterfacesOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListVirtualMachineScaleSetIpConfigurationsAsync : Microsoft.Azure.Management.Network.INetworkInterfacesOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;&gt;" Usage="Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.ListVirtualMachineScaleSetIpConfigurationsAsync (operations, resourceGroupName, virtualMachineScaleSetName, virtualmachineIndex, networkInterfaceName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions/&lt;ListVirtualMachineScaleSetIpConfigurationsAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualMachineScaleSetName" Type="System.String" />
        <Parameter Name="virtualmachineIndex" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b00a-265">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8b00a-265">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8b00a-266">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-266">The name of the resource group.</span></span>
            </param>
        <param name="virtualMachineScaleSetName">
            <span data-ttu-id="8b00a-267">仮想マシン スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-267">The name of the virtual machine scale set.</span></span>
            </param>
        <param name="virtualmachineIndex">
            <span data-ttu-id="8b00a-268">仮想マシンのインデックス。</span><span class="sxs-lookup"><span data-stu-id="8b00a-268">The virtual machine index.</span></span>
            </param>
        <param name="networkInterfaceName">
            <span data-ttu-id="8b00a-269">ネットワーク インターフェイスの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-269">The name of the network interface.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="8b00a-270">参照されているリソースを展開します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-270">Expands referenced resources.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8b00a-271">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8b00a-271">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b00a-272">仮想マシン スケール セット内の指定したネットワーク インターフェイス ip 構成を取得します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-272">Get the specified network interface ip configuration in a virtual machine scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVirtualMachineScaleSetIpConfigurationsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt; ListVirtualMachineScaleSetIpConfigurationsNext (this Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt; ListVirtualMachineScaleSetIpConfigurationsNext(class Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.ListVirtualMachineScaleSetIpConfigurationsNext(Microsoft.Azure.Management.Network.INetworkInterfacesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListVirtualMachineScaleSetIpConfigurationsNext (operations As INetworkInterfacesOperations, nextPageLink As String) As IPage(Of NetworkInterfaceIPConfiguration)" />
      <MemberSignature Language="F#" Value="static member ListVirtualMachineScaleSetIpConfigurationsNext : Microsoft.Azure.Management.Network.INetworkInterfacesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;" Usage="Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.ListVirtualMachineScaleSetIpConfigurationsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b00a-273">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8b00a-273">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="8b00a-274">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="8b00a-274">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b00a-275">仮想マシン スケール セット内の指定したネットワーク インターフェイス ip 構成を取得します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-275">Get the specified network interface ip configuration in a virtual machine scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVirtualMachineScaleSetIpConfigurationsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;&gt; ListVirtualMachineScaleSetIpConfigurationsNextAsync (this Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;&gt; ListVirtualMachineScaleSetIpConfigurationsNextAsync(class Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.ListVirtualMachineScaleSetIpConfigurationsNextAsync(Microsoft.Azure.Management.Network.INetworkInterfacesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListVirtualMachineScaleSetIpConfigurationsNextAsync : Microsoft.Azure.Management.Network.INetworkInterfacesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;&gt;" Usage="Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.ListVirtualMachineScaleSetIpConfigurationsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions/&lt;ListVirtualMachineScaleSetIpConfigurationsNextAsync&gt;d__45))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b00a-276">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8b00a-276">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="8b00a-277">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="8b00a-277">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8b00a-278">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8b00a-278">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b00a-279">仮想マシン スケール セット内の指定したネットワーク インターフェイス ip 構成を取得します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-279">Get the specified network interface ip configuration in a virtual machine scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVirtualMachineScaleSetNetworkInterfaces">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt; ListVirtualMachineScaleSetNetworkInterfaces (this Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string virtualMachineScaleSetName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterface&gt; ListVirtualMachineScaleSetNetworkInterfaces(class Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string virtualMachineScaleSetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.ListVirtualMachineScaleSetNetworkInterfaces(Microsoft.Azure.Management.Network.INetworkInterfacesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListVirtualMachineScaleSetNetworkInterfaces (operations As INetworkInterfacesOperations, resourceGroupName As String, virtualMachineScaleSetName As String) As IPage(Of NetworkInterface)" />
      <MemberSignature Language="F#" Value="static member ListVirtualMachineScaleSetNetworkInterfaces : Microsoft.Azure.Management.Network.INetworkInterfacesOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;" Usage="Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.ListVirtualMachineScaleSetNetworkInterfaces (operations, resourceGroupName, virtualMachineScaleSetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualMachineScaleSetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b00a-280">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8b00a-280">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8b00a-281">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-281">The name of the resource group.</span></span>
            </param>
        <param name="virtualMachineScaleSetName">
            <span data-ttu-id="8b00a-282">仮想マシン スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-282">The name of the virtual machine scale set.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b00a-283">仮想マシン スケール セット内のすべてのネットワーク インターフェイスを取得します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-283">Gets all network interfaces in a virtual machine scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVirtualMachineScaleSetNetworkInterfacesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;&gt; ListVirtualMachineScaleSetNetworkInterfacesAsync (this Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string virtualMachineScaleSetName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;&gt; ListVirtualMachineScaleSetNetworkInterfacesAsync(class Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string virtualMachineScaleSetName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.ListVirtualMachineScaleSetNetworkInterfacesAsync(Microsoft.Azure.Management.Network.INetworkInterfacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListVirtualMachineScaleSetNetworkInterfacesAsync : Microsoft.Azure.Management.Network.INetworkInterfacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;&gt;" Usage="Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.ListVirtualMachineScaleSetNetworkInterfacesAsync (operations, resourceGroupName, virtualMachineScaleSetName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions/&lt;ListVirtualMachineScaleSetNetworkInterfacesAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualMachineScaleSetName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b00a-284">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8b00a-284">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8b00a-285">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-285">The name of the resource group.</span></span>
            </param>
        <param name="virtualMachineScaleSetName">
            <span data-ttu-id="8b00a-286">仮想マシン スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-286">The name of the virtual machine scale set.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8b00a-287">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8b00a-287">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b00a-288">仮想マシン スケール セット内のすべてのネットワーク インターフェイスを取得します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-288">Gets all network interfaces in a virtual machine scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVirtualMachineScaleSetNetworkInterfacesNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt; ListVirtualMachineScaleSetNetworkInterfacesNext (this Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterface&gt; ListVirtualMachineScaleSetNetworkInterfacesNext(class Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.ListVirtualMachineScaleSetNetworkInterfacesNext(Microsoft.Azure.Management.Network.INetworkInterfacesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListVirtualMachineScaleSetNetworkInterfacesNext (operations As INetworkInterfacesOperations, nextPageLink As String) As IPage(Of NetworkInterface)" />
      <MemberSignature Language="F#" Value="static member ListVirtualMachineScaleSetNetworkInterfacesNext : Microsoft.Azure.Management.Network.INetworkInterfacesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;" Usage="Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.ListVirtualMachineScaleSetNetworkInterfacesNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b00a-289">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8b00a-289">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="8b00a-290">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="8b00a-290">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b00a-291">仮想マシン スケール セット内のすべてのネットワーク インターフェイスを取得します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-291">Gets all network interfaces in a virtual machine scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVirtualMachineScaleSetNetworkInterfacesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;&gt; ListVirtualMachineScaleSetNetworkInterfacesNextAsync (this Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;&gt; ListVirtualMachineScaleSetNetworkInterfacesNextAsync(class Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.ListVirtualMachineScaleSetNetworkInterfacesNextAsync(Microsoft.Azure.Management.Network.INetworkInterfacesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListVirtualMachineScaleSetNetworkInterfacesNextAsync : Microsoft.Azure.Management.Network.INetworkInterfacesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;&gt;" Usage="Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.ListVirtualMachineScaleSetNetworkInterfacesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions/&lt;ListVirtualMachineScaleSetNetworkInterfacesNextAsync&gt;d__43))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b00a-292">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8b00a-292">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="8b00a-293">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="8b00a-293">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8b00a-294">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8b00a-294">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b00a-295">仮想マシン スケール セット内のすべてのネットワーク インターフェイスを取得します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-295">Gets all network interfaces in a virtual machine scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVirtualMachineScaleSetVMNetworkInterfaces">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt; ListVirtualMachineScaleSetVMNetworkInterfaces (this Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string virtualMachineScaleSetName, string virtualmachineIndex);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterface&gt; ListVirtualMachineScaleSetVMNetworkInterfaces(class Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string virtualMachineScaleSetName, string virtualmachineIndex) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.ListVirtualMachineScaleSetVMNetworkInterfaces(Microsoft.Azure.Management.Network.INetworkInterfacesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListVirtualMachineScaleSetVMNetworkInterfaces (operations As INetworkInterfacesOperations, resourceGroupName As String, virtualMachineScaleSetName As String, virtualmachineIndex As String) As IPage(Of NetworkInterface)" />
      <MemberSignature Language="F#" Value="static member ListVirtualMachineScaleSetVMNetworkInterfaces : Microsoft.Azure.Management.Network.INetworkInterfacesOperations * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;" Usage="Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.ListVirtualMachineScaleSetVMNetworkInterfaces (operations, resourceGroupName, virtualMachineScaleSetName, virtualmachineIndex)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualMachineScaleSetName" Type="System.String" />
        <Parameter Name="virtualmachineIndex" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b00a-296">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8b00a-296">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8b00a-297">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-297">The name of the resource group.</span></span>
            </param>
        <param name="virtualMachineScaleSetName">
            <span data-ttu-id="8b00a-298">仮想マシン スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-298">The name of the virtual machine scale set.</span></span>
            </param>
        <param name="virtualmachineIndex">
            <span data-ttu-id="8b00a-299">仮想マシンのインデックス。</span><span class="sxs-lookup"><span data-stu-id="8b00a-299">The virtual machine index.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b00a-300">仮想マシン スケール セット内の仮想マシン内のすべてのネットワーク インターフェイスに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-300">Gets information about all network interfaces in a virtual machine in a virtual machine scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVirtualMachineScaleSetVMNetworkInterfacesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;&gt; ListVirtualMachineScaleSetVMNetworkInterfacesAsync (this Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string virtualMachineScaleSetName, string virtualmachineIndex, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;&gt; ListVirtualMachineScaleSetVMNetworkInterfacesAsync(class Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string virtualMachineScaleSetName, string virtualmachineIndex, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.ListVirtualMachineScaleSetVMNetworkInterfacesAsync(Microsoft.Azure.Management.Network.INetworkInterfacesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListVirtualMachineScaleSetVMNetworkInterfacesAsync : Microsoft.Azure.Management.Network.INetworkInterfacesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;&gt;" Usage="Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.ListVirtualMachineScaleSetVMNetworkInterfacesAsync (operations, resourceGroupName, virtualMachineScaleSetName, virtualmachineIndex, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions/&lt;ListVirtualMachineScaleSetVMNetworkInterfacesAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualMachineScaleSetName" Type="System.String" />
        <Parameter Name="virtualmachineIndex" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b00a-301">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8b00a-301">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8b00a-302">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-302">The name of the resource group.</span></span>
            </param>
        <param name="virtualMachineScaleSetName">
            <span data-ttu-id="8b00a-303">仮想マシン スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-303">The name of the virtual machine scale set.</span></span>
            </param>
        <param name="virtualmachineIndex">
            <span data-ttu-id="8b00a-304">仮想マシンのインデックス。</span><span class="sxs-lookup"><span data-stu-id="8b00a-304">The virtual machine index.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8b00a-305">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8b00a-305">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b00a-306">仮想マシン スケール セット内の仮想マシン内のすべてのネットワーク インターフェイスに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-306">Gets information about all network interfaces in a virtual machine in a virtual machine scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVirtualMachineScaleSetVMNetworkInterfacesNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt; ListVirtualMachineScaleSetVMNetworkInterfacesNext (this Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterface&gt; ListVirtualMachineScaleSetVMNetworkInterfacesNext(class Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.ListVirtualMachineScaleSetVMNetworkInterfacesNext(Microsoft.Azure.Management.Network.INetworkInterfacesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListVirtualMachineScaleSetVMNetworkInterfacesNext (operations As INetworkInterfacesOperations, nextPageLink As String) As IPage(Of NetworkInterface)" />
      <MemberSignature Language="F#" Value="static member ListVirtualMachineScaleSetVMNetworkInterfacesNext : Microsoft.Azure.Management.Network.INetworkInterfacesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;" Usage="Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.ListVirtualMachineScaleSetVMNetworkInterfacesNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b00a-307">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8b00a-307">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="8b00a-308">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="8b00a-308">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b00a-309">仮想マシン スケール セット内の仮想マシン内のすべてのネットワーク インターフェイスに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-309">Gets information about all network interfaces in a virtual machine in a virtual machine scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVirtualMachineScaleSetVMNetworkInterfacesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;&gt; ListVirtualMachineScaleSetVMNetworkInterfacesNextAsync (this Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;&gt; ListVirtualMachineScaleSetVMNetworkInterfacesNextAsync(class Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.ListVirtualMachineScaleSetVMNetworkInterfacesNextAsync(Microsoft.Azure.Management.Network.INetworkInterfacesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListVirtualMachineScaleSetVMNetworkInterfacesNextAsync : Microsoft.Azure.Management.Network.INetworkInterfacesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;&gt;" Usage="Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.ListVirtualMachineScaleSetVMNetworkInterfacesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions/&lt;ListVirtualMachineScaleSetVMNetworkInterfacesNextAsync&gt;d__41))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b00a-310">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8b00a-310">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="8b00a-311">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="8b00a-311">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8b00a-312">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8b00a-312">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b00a-313">仮想マシン スケール セット内の仮想マシン内のすべてのネットワーク インターフェイスに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-313">Gets information about all network interfaces in a virtual machine in a virtual machine scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTags">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.NetworkInterface UpdateTags (this Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName, Microsoft.Azure.Management.Network.Models.TagsObject parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.NetworkInterface UpdateTags(class Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.UpdateTags(Microsoft.Azure.Management.Network.INetworkInterfacesOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpdateTags (operations As INetworkInterfacesOperations, resourceGroupName As String, networkInterfaceName As String, parameters As TagsObject) As NetworkInterface" />
      <MemberSignature Language="F#" Value="static member UpdateTags : Microsoft.Azure.Management.Network.INetworkInterfacesOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject -&gt; Microsoft.Azure.Management.Network.Models.NetworkInterface" Usage="Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.UpdateTags (operations, resourceGroupName, networkInterfaceName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.NetworkInterface</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b00a-314">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8b00a-314">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8b00a-315">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-315">The name of the resource group.</span></span>
            </param>
        <param name="networkInterfaceName">
            <span data-ttu-id="8b00a-316">ネットワーク インターフェイスの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-316">The name of the network interface.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="8b00a-317">ネットワーク インターフェイスのタグを更新する指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="8b00a-317">Parameters supplied to update network interface tags.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b00a-318">ネットワーク インターフェイスのタグを更新します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-318">Updates a network interface tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTagsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt; UpdateTagsAsync (this Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName, Microsoft.Azure.Management.Network.Models.TagsObject parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterface&gt; UpdateTagsAsync(class Microsoft.Azure.Management.Network.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.UpdateTagsAsync(Microsoft.Azure.Management.Network.INetworkInterfacesOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateTagsAsync : Microsoft.Azure.Management.Network.INetworkInterfacesOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;" Usage="Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions.UpdateTagsAsync (operations, resourceGroupName, networkInterfaceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkInterfacesOperationsExtensions/&lt;UpdateTagsAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b00a-319">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8b00a-319">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8b00a-320">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-320">The name of the resource group.</span></span>
            </param>
        <param name="networkInterfaceName">
            <span data-ttu-id="8b00a-321">ネットワーク インターフェイスの名前。</span><span class="sxs-lookup"><span data-stu-id="8b00a-321">The name of the network interface.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="8b00a-322">ネットワーク インターフェイスのタグを更新する指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="8b00a-322">Parameters supplied to update network interface tags.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8b00a-323">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8b00a-323">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b00a-324">ネットワーク インターフェイスのタグを更新します。</span><span class="sxs-lookup"><span data-stu-id="8b00a-324">Updates a network interface tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>