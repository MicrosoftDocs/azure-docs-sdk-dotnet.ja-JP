<Type Name="LoadBalancerProbesOperationsExtensions" FullName="Microsoft.Azure.Management.Network.LoadBalancerProbesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class LoadBalancerProbesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit LoadBalancerProbesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.LoadBalancerProbesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module LoadBalancerProbesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type LoadBalancerProbesOperationsExtensions = class" />
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
            <span data-ttu-id="a9ffe-101">LoadBalancerProbesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="a9ffe-101">Extension methods for LoadBalancerProbesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.Probe Get (this Microsoft.Azure.Management.Network.ILoadBalancerProbesOperations operations, string resourceGroupName, string loadBalancerName, string probeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.Probe Get(class Microsoft.Azure.Management.Network.ILoadBalancerProbesOperations operations, string resourceGroupName, string loadBalancerName, string probeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancerProbesOperationsExtensions.Get(Microsoft.Azure.Management.Network.ILoadBalancerProbesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ILoadBalancerProbesOperations, resourceGroupName As String, loadBalancerName As String, probeName As String) As Probe" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Network.ILoadBalancerProbesOperations * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.Probe" Usage="Microsoft.Azure.Management.Network.LoadBalancerProbesOperationsExtensions.Get (operations, resourceGroupName, loadBalancerName, probeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.Probe</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancerProbesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="probeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a9ffe-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a9ffe-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a9ffe-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a9ffe-103">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="a9ffe-104">ロード バランサーの名前。</span><span class="sxs-lookup"><span data-stu-id="a9ffe-104">The name of the load balancer.</span></span>
            </param>
        <param name="probeName">
            <span data-ttu-id="a9ffe-105">プローブの名前です。</span><span class="sxs-lookup"><span data-stu-id="a9ffe-105">The name of the probe.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a9ffe-106">取得はロード バランサー プローブです。</span><span class="sxs-lookup"><span data-stu-id="a9ffe-106">Gets load balancer probe.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.Probe&gt; GetAsync (this Microsoft.Azure.Management.Network.ILoadBalancerProbesOperations operations, string resourceGroupName, string loadBalancerName, string probeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.Probe&gt; GetAsync(class Microsoft.Azure.Management.Network.ILoadBalancerProbesOperations operations, string resourceGroupName, string loadBalancerName, string probeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancerProbesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.ILoadBalancerProbesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.ILoadBalancerProbesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.Probe&gt;" Usage="Microsoft.Azure.Management.Network.LoadBalancerProbesOperationsExtensions.GetAsync (operations, resourceGroupName, loadBalancerName, probeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LoadBalancerProbesOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.Probe&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancerProbesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="probeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a9ffe-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a9ffe-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a9ffe-108">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a9ffe-108">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="a9ffe-109">ロード バランサーの名前。</span><span class="sxs-lookup"><span data-stu-id="a9ffe-109">The name of the load balancer.</span></span>
            </param>
        <param name="probeName">
            <span data-ttu-id="a9ffe-110">プローブの名前です。</span><span class="sxs-lookup"><span data-stu-id="a9ffe-110">The name of the probe.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a9ffe-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a9ffe-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a9ffe-112">取得はロード バランサー プローブです。</span><span class="sxs-lookup"><span data-stu-id="a9ffe-112">Gets load balancer probe.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.Probe&gt; List (this Microsoft.Azure.Management.Network.ILoadBalancerProbesOperations operations, string resourceGroupName, string loadBalancerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.Probe&gt; List(class Microsoft.Azure.Management.Network.ILoadBalancerProbesOperations operations, string resourceGroupName, string loadBalancerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancerProbesOperationsExtensions.List(Microsoft.Azure.Management.Network.ILoadBalancerProbesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As ILoadBalancerProbesOperations, resourceGroupName As String, loadBalancerName As String) As IPage(Of Probe)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Network.ILoadBalancerProbesOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.Probe&gt;" Usage="Microsoft.Azure.Management.Network.LoadBalancerProbesOperationsExtensions.List (operations, resourceGroupName, loadBalancerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.Probe&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancerProbesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a9ffe-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a9ffe-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a9ffe-114">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a9ffe-114">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="a9ffe-115">ロード バランサーの名前。</span><span class="sxs-lookup"><span data-stu-id="a9ffe-115">The name of the load balancer.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a9ffe-116">すべてのロード バランサー プローブを取得します。</span><span class="sxs-lookup"><span data-stu-id="a9ffe-116">Gets all the load balancer probes.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.Probe&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.ILoadBalancerProbesOperations operations, string resourceGroupName, string loadBalancerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.Probe&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.ILoadBalancerProbesOperations operations, string resourceGroupName, string loadBalancerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancerProbesOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.ILoadBalancerProbesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.ILoadBalancerProbesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.Probe&gt;&gt;" Usage="Microsoft.Azure.Management.Network.LoadBalancerProbesOperationsExtensions.ListAsync (operations, resourceGroupName, loadBalancerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LoadBalancerProbesOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.Probe&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancerProbesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a9ffe-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a9ffe-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a9ffe-118">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a9ffe-118">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="a9ffe-119">ロード バランサーの名前。</span><span class="sxs-lookup"><span data-stu-id="a9ffe-119">The name of the load balancer.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a9ffe-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a9ffe-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a9ffe-121">すべてのロード バランサー プローブを取得します。</span><span class="sxs-lookup"><span data-stu-id="a9ffe-121">Gets all the load balancer probes.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.Probe&gt; ListNext (this Microsoft.Azure.Management.Network.ILoadBalancerProbesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.Probe&gt; ListNext(class Microsoft.Azure.Management.Network.ILoadBalancerProbesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancerProbesOperationsExtensions.ListNext(Microsoft.Azure.Management.Network.ILoadBalancerProbesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As ILoadBalancerProbesOperations, nextPageLink As String) As IPage(Of Probe)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Network.ILoadBalancerProbesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.Probe&gt;" Usage="Microsoft.Azure.Management.Network.LoadBalancerProbesOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.Probe&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancerProbesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a9ffe-122">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a9ffe-122">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="a9ffe-123">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="a9ffe-123">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a9ffe-124">すべてのロード バランサー プローブを取得します。</span><span class="sxs-lookup"><span data-stu-id="a9ffe-124">Gets all the load balancer probes.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.Probe&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.ILoadBalancerProbesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.Probe&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.ILoadBalancerProbesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancerProbesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.ILoadBalancerProbesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.ILoadBalancerProbesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.Probe&gt;&gt;" Usage="Microsoft.Azure.Management.Network.LoadBalancerProbesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LoadBalancerProbesOperationsExtensions/&lt;ListNextAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.Probe&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancerProbesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a9ffe-125">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a9ffe-125">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="a9ffe-126">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="a9ffe-126">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a9ffe-127">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a9ffe-127">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a9ffe-128">すべてのロード バランサー プローブを取得します。</span><span class="sxs-lookup"><span data-stu-id="a9ffe-128">Gets all the load balancer probes.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>