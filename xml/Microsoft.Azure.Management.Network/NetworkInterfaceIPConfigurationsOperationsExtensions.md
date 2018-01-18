<Type Name="NetworkInterfaceIPConfigurationsOperationsExtensions" FullName="Microsoft.Azure.Management.Network.NetworkInterfaceIPConfigurationsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class NetworkInterfaceIPConfigurationsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit NetworkInterfaceIPConfigurationsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.NetworkInterfaceIPConfigurationsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module NetworkInterfaceIPConfigurationsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type NetworkInterfaceIPConfigurationsOperationsExtensions = class" />
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
            <span data-ttu-id="755a5-101">NetworkInterfaceIPConfigurationsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="755a5-101">Extension methods for NetworkInterfaceIPConfigurationsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration Get (this Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations operations, string resourceGroupName, string networkInterfaceName, string ipConfigurationName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration Get(class Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations operations, string resourceGroupName, string networkInterfaceName, string ipConfigurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfaceIPConfigurationsOperationsExtensions.Get(Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As INetworkInterfaceIPConfigurationsOperations, resourceGroupName As String, networkInterfaceName As String, ipConfigurationName As String) As NetworkInterfaceIPConfiguration" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration" Usage="Microsoft.Azure.Management.Network.NetworkInterfaceIPConfigurationsOperationsExtensions.Get (operations, resourceGroupName, networkInterfaceName, ipConfigurationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
        <Parameter Name="ipConfigurationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="755a5-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="755a5-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="755a5-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="755a5-103">The name of the resource group.</span></span>
            </param>
        <param name="networkInterfaceName">
            <span data-ttu-id="755a5-104">ネットワーク インターフェイスの名前。</span><span class="sxs-lookup"><span data-stu-id="755a5-104">The name of the network interface.</span></span>
            </param>
        <param name="ipConfigurationName">
            <span data-ttu-id="755a5-105">Ip 構成の名前の名前。</span><span class="sxs-lookup"><span data-stu-id="755a5-105">The name of the ip configuration name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="755a5-106">指定したネットワーク インターフェイス ip 構成を取得します。</span><span class="sxs-lookup"><span data-stu-id="755a5-106">Gets the specified network interface ip configuration.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt; GetAsync (this Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations operations, string resourceGroupName, string networkInterfaceName, string ipConfigurationName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt; GetAsync(class Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations operations, string resourceGroupName, string networkInterfaceName, string ipConfigurationName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfaceIPConfigurationsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;" Usage="Microsoft.Azure.Management.Network.NetworkInterfaceIPConfigurationsOperationsExtensions.GetAsync (operations, resourceGroupName, networkInterfaceName, ipConfigurationName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkInterfaceIPConfigurationsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
        <Parameter Name="ipConfigurationName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="755a5-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="755a5-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="755a5-108">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="755a5-108">The name of the resource group.</span></span>
            </param>
        <param name="networkInterfaceName">
            <span data-ttu-id="755a5-109">ネットワーク インターフェイスの名前。</span><span class="sxs-lookup"><span data-stu-id="755a5-109">The name of the network interface.</span></span>
            </param>
        <param name="ipConfigurationName">
            <span data-ttu-id="755a5-110">Ip 構成の名前の名前。</span><span class="sxs-lookup"><span data-stu-id="755a5-110">The name of the ip configuration name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="755a5-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="755a5-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="755a5-112">指定したネットワーク インターフェイス ip 構成を取得します。</span><span class="sxs-lookup"><span data-stu-id="755a5-112">Gets the specified network interface ip configuration.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt; List (this Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations operations, string resourceGroupName, string networkInterfaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt; List(class Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations operations, string resourceGroupName, string networkInterfaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfaceIPConfigurationsOperationsExtensions.List(Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As INetworkInterfaceIPConfigurationsOperations, resourceGroupName As String, networkInterfaceName As String) As IPage(Of NetworkInterfaceIPConfiguration)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;" Usage="Microsoft.Azure.Management.Network.NetworkInterfaceIPConfigurationsOperationsExtensions.List (operations, resourceGroupName, networkInterfaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="755a5-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="755a5-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="755a5-114">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="755a5-114">The name of the resource group.</span></span>
            </param>
        <param name="networkInterfaceName">
            <span data-ttu-id="755a5-115">ネットワーク インターフェイスの名前。</span><span class="sxs-lookup"><span data-stu-id="755a5-115">The name of the network interface.</span></span>
            </param>
        <summary>
            <span data-ttu-id="755a5-116">ネットワーク インターフェイスのすべての ip 構成を取得します。</span><span class="sxs-lookup"><span data-stu-id="755a5-116">Get all ip configurations in a network interface</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations operations, string resourceGroupName, string networkInterfaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations operations, string resourceGroupName, string networkInterfaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfaceIPConfigurationsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;&gt;" Usage="Microsoft.Azure.Management.Network.NetworkInterfaceIPConfigurationsOperationsExtensions.ListAsync (operations, resourceGroupName, networkInterfaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkInterfaceIPConfigurationsOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="755a5-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="755a5-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="755a5-118">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="755a5-118">The name of the resource group.</span></span>
            </param>
        <param name="networkInterfaceName">
            <span data-ttu-id="755a5-119">ネットワーク インターフェイスの名前。</span><span class="sxs-lookup"><span data-stu-id="755a5-119">The name of the network interface.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="755a5-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="755a5-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="755a5-121">ネットワーク インターフェイスのすべての ip 構成を取得します。</span><span class="sxs-lookup"><span data-stu-id="755a5-121">Get all ip configurations in a network interface</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt; ListNext (this Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt; ListNext(class Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfaceIPConfigurationsOperationsExtensions.ListNext(Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As INetworkInterfaceIPConfigurationsOperations, nextPageLink As String) As IPage(Of NetworkInterfaceIPConfiguration)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;" Usage="Microsoft.Azure.Management.Network.NetworkInterfaceIPConfigurationsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="755a5-122">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="755a5-122">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="755a5-123">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="755a5-123">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="755a5-124">ネットワーク インターフェイスのすべての ip 構成を取得します。</span><span class="sxs-lookup"><span data-stu-id="755a5-124">Get all ip configurations in a network interface</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfaceIPConfigurationsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;&gt;" Usage="Microsoft.Azure.Management.Network.NetworkInterfaceIPConfigurationsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkInterfaceIPConfigurationsOperationsExtensions/&lt;ListNextAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="755a5-125">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="755a5-125">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="755a5-126">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="755a5-126">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="755a5-127">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="755a5-127">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="755a5-128">ネットワーク インターフェイスのすべての ip 構成を取得します。</span><span class="sxs-lookup"><span data-stu-id="755a5-128">Get all ip configurations in a network interface</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>