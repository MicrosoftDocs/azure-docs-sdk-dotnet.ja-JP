<Type Name="LoadBalancerNetworkInterfacesOperationsExtensions" FullName="Microsoft.Azure.Management.Network.LoadBalancerNetworkInterfacesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class LoadBalancerNetworkInterfacesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit LoadBalancerNetworkInterfacesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.LoadBalancerNetworkInterfacesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module LoadBalancerNetworkInterfacesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type LoadBalancerNetworkInterfacesOperationsExtensions = class" />
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
            <span data-ttu-id="174c2-101">LoadBalancerNetworkInterfacesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="174c2-101">Extension methods for LoadBalancerNetworkInterfacesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt; List (this Microsoft.Azure.Management.Network.ILoadBalancerNetworkInterfacesOperations operations, string resourceGroupName, string loadBalancerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterface&gt; List(class Microsoft.Azure.Management.Network.ILoadBalancerNetworkInterfacesOperations operations, string resourceGroupName, string loadBalancerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancerNetworkInterfacesOperationsExtensions.List(Microsoft.Azure.Management.Network.ILoadBalancerNetworkInterfacesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As ILoadBalancerNetworkInterfacesOperations, resourceGroupName As String, loadBalancerName As String) As IPage(Of NetworkInterface)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Network.ILoadBalancerNetworkInterfacesOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;" Usage="Microsoft.Azure.Management.Network.LoadBalancerNetworkInterfacesOperationsExtensions.List (operations, resourceGroupName, loadBalancerName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancerNetworkInterfacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="174c2-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="174c2-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="174c2-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="174c2-103">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="174c2-104">ロード バランサーの名前。</span><span class="sxs-lookup"><span data-stu-id="174c2-104">The name of the load balancer.</span></span>
            </param>
        <summary>
            <span data-ttu-id="174c2-105">取得には、ロード バランサーのネットワーク インターフェイスが関連付けられています。</span><span class="sxs-lookup"><span data-stu-id="174c2-105">Gets associated load balancer network interfaces.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.ILoadBalancerNetworkInterfacesOperations operations, string resourceGroupName, string loadBalancerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.ILoadBalancerNetworkInterfacesOperations operations, string resourceGroupName, string loadBalancerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancerNetworkInterfacesOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.ILoadBalancerNetworkInterfacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.ILoadBalancerNetworkInterfacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;&gt;" Usage="Microsoft.Azure.Management.Network.LoadBalancerNetworkInterfacesOperationsExtensions.ListAsync (operations, resourceGroupName, loadBalancerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LoadBalancerNetworkInterfacesOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancerNetworkInterfacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="174c2-106">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="174c2-106">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="174c2-107">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="174c2-107">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="174c2-108">ロード バランサーの名前。</span><span class="sxs-lookup"><span data-stu-id="174c2-108">The name of the load balancer.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="174c2-109">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="174c2-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="174c2-110">取得には、ロード バランサーのネットワーク インターフェイスが関連付けられています。</span><span class="sxs-lookup"><span data-stu-id="174c2-110">Gets associated load balancer network interfaces.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt; ListNext (this Microsoft.Azure.Management.Network.ILoadBalancerNetworkInterfacesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterface&gt; ListNext(class Microsoft.Azure.Management.Network.ILoadBalancerNetworkInterfacesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancerNetworkInterfacesOperationsExtensions.ListNext(Microsoft.Azure.Management.Network.ILoadBalancerNetworkInterfacesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As ILoadBalancerNetworkInterfacesOperations, nextPageLink As String) As IPage(Of NetworkInterface)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Network.ILoadBalancerNetworkInterfacesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;" Usage="Microsoft.Azure.Management.Network.LoadBalancerNetworkInterfacesOperationsExtensions.ListNext (operations, nextPageLink)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancerNetworkInterfacesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="174c2-111">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="174c2-111">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="174c2-112">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="174c2-112">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="174c2-113">取得には、ロード バランサーのネットワーク インターフェイスが関連付けられています。</span><span class="sxs-lookup"><span data-stu-id="174c2-113">Gets associated load balancer network interfaces.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.ILoadBalancerNetworkInterfacesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.ILoadBalancerNetworkInterfacesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancerNetworkInterfacesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.ILoadBalancerNetworkInterfacesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.ILoadBalancerNetworkInterfacesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;&gt;" Usage="Microsoft.Azure.Management.Network.LoadBalancerNetworkInterfacesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LoadBalancerNetworkInterfacesOperationsExtensions/&lt;ListNextAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancerNetworkInterfacesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="174c2-114">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="174c2-114">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="174c2-115">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="174c2-115">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="174c2-116">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="174c2-116">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="174c2-117">取得には、ロード バランサーのネットワーク インターフェイスが関連付けられています。</span><span class="sxs-lookup"><span data-stu-id="174c2-117">Gets associated load balancer network interfaces.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>