<Type Name="LoadBalancerFrontendIPConfigurationsOperationsExtensions" FullName="Microsoft.Azure.Management.Network.LoadBalancerFrontendIPConfigurationsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class LoadBalancerFrontendIPConfigurationsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit LoadBalancerFrontendIPConfigurationsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.LoadBalancerFrontendIPConfigurationsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module LoadBalancerFrontendIPConfigurationsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type LoadBalancerFrontendIPConfigurationsOperationsExtensions = class" />
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
            <span data-ttu-id="f4ebe-101">LoadBalancerFrontendIPConfigurationsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="f4ebe-101">Extension methods for LoadBalancerFrontendIPConfigurationsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.FrontendIPConfiguration Get (this Microsoft.Azure.Management.Network.ILoadBalancerFrontendIPConfigurationsOperations operations, string resourceGroupName, string loadBalancerName, string frontendIPConfigurationName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.FrontendIPConfiguration Get(class Microsoft.Azure.Management.Network.ILoadBalancerFrontendIPConfigurationsOperations operations, string resourceGroupName, string loadBalancerName, string frontendIPConfigurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancerFrontendIPConfigurationsOperationsExtensions.Get(Microsoft.Azure.Management.Network.ILoadBalancerFrontendIPConfigurationsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ILoadBalancerFrontendIPConfigurationsOperations, resourceGroupName As String, loadBalancerName As String, frontendIPConfigurationName As String) As FrontendIPConfiguration" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Network.ILoadBalancerFrontendIPConfigurationsOperations * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.FrontendIPConfiguration" Usage="Microsoft.Azure.Management.Network.LoadBalancerFrontendIPConfigurationsOperationsExtensions.Get (operations, resourceGroupName, loadBalancerName, frontendIPConfigurationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.FrontendIPConfiguration</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancerFrontendIPConfigurationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="frontendIPConfigurationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f4ebe-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f4ebe-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f4ebe-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f4ebe-103">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="f4ebe-104">ロード バランサーの名前。</span><span class="sxs-lookup"><span data-stu-id="f4ebe-104">The name of the load balancer.</span></span>
            </param>
        <param name="frontendIPConfigurationName">
            <span data-ttu-id="f4ebe-105">フロント エンド IP 構成の名前。</span><span class="sxs-lookup"><span data-stu-id="f4ebe-105">The name of the frontend IP configuration.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4ebe-106">取得をロード バランサーのフロント エンド IP 構成します。</span><span class="sxs-lookup"><span data-stu-id="f4ebe-106">Gets load balancer frontend IP configuration.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.FrontendIPConfiguration&gt; GetAsync (this Microsoft.Azure.Management.Network.ILoadBalancerFrontendIPConfigurationsOperations operations, string resourceGroupName, string loadBalancerName, string frontendIPConfigurationName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.FrontendIPConfiguration&gt; GetAsync(class Microsoft.Azure.Management.Network.ILoadBalancerFrontendIPConfigurationsOperations operations, string resourceGroupName, string loadBalancerName, string frontendIPConfigurationName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancerFrontendIPConfigurationsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.ILoadBalancerFrontendIPConfigurationsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.ILoadBalancerFrontendIPConfigurationsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.FrontendIPConfiguration&gt;" Usage="Microsoft.Azure.Management.Network.LoadBalancerFrontendIPConfigurationsOperationsExtensions.GetAsync (operations, resourceGroupName, loadBalancerName, frontendIPConfigurationName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LoadBalancerFrontendIPConfigurationsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.FrontendIPConfiguration&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancerFrontendIPConfigurationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="frontendIPConfigurationName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f4ebe-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f4ebe-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f4ebe-108">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f4ebe-108">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="f4ebe-109">ロード バランサーの名前。</span><span class="sxs-lookup"><span data-stu-id="f4ebe-109">The name of the load balancer.</span></span>
            </param>
        <param name="frontendIPConfigurationName">
            <span data-ttu-id="f4ebe-110">フロント エンド IP 構成の名前。</span><span class="sxs-lookup"><span data-stu-id="f4ebe-110">The name of the frontend IP configuration.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4ebe-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f4ebe-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4ebe-112">取得をロード バランサーのフロント エンド IP 構成します。</span><span class="sxs-lookup"><span data-stu-id="f4ebe-112">Gets load balancer frontend IP configuration.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.FrontendIPConfiguration&gt; List (this Microsoft.Azure.Management.Network.ILoadBalancerFrontendIPConfigurationsOperations operations, string resourceGroupName, string loadBalancerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.FrontendIPConfiguration&gt; List(class Microsoft.Azure.Management.Network.ILoadBalancerFrontendIPConfigurationsOperations operations, string resourceGroupName, string loadBalancerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancerFrontendIPConfigurationsOperationsExtensions.List(Microsoft.Azure.Management.Network.ILoadBalancerFrontendIPConfigurationsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As ILoadBalancerFrontendIPConfigurationsOperations, resourceGroupName As String, loadBalancerName As String) As IPage(Of FrontendIPConfiguration)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Network.ILoadBalancerFrontendIPConfigurationsOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.FrontendIPConfiguration&gt;" Usage="Microsoft.Azure.Management.Network.LoadBalancerFrontendIPConfigurationsOperationsExtensions.List (operations, resourceGroupName, loadBalancerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.FrontendIPConfiguration&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancerFrontendIPConfigurationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f4ebe-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f4ebe-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f4ebe-114">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f4ebe-114">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="f4ebe-115">ロード バランサーの名前。</span><span class="sxs-lookup"><span data-stu-id="f4ebe-115">The name of the load balancer.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4ebe-116">すべてのロード バランサーのフロント エンド IP 構成を取得します。</span><span class="sxs-lookup"><span data-stu-id="f4ebe-116">Gets all the load balancer frontend IP configurations.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.FrontendIPConfiguration&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.ILoadBalancerFrontendIPConfigurationsOperations operations, string resourceGroupName, string loadBalancerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.FrontendIPConfiguration&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.ILoadBalancerFrontendIPConfigurationsOperations operations, string resourceGroupName, string loadBalancerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancerFrontendIPConfigurationsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.ILoadBalancerFrontendIPConfigurationsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.ILoadBalancerFrontendIPConfigurationsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.FrontendIPConfiguration&gt;&gt;" Usage="Microsoft.Azure.Management.Network.LoadBalancerFrontendIPConfigurationsOperationsExtensions.ListAsync (operations, resourceGroupName, loadBalancerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LoadBalancerFrontendIPConfigurationsOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.FrontendIPConfiguration&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancerFrontendIPConfigurationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f4ebe-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f4ebe-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f4ebe-118">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f4ebe-118">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="f4ebe-119">ロード バランサーの名前。</span><span class="sxs-lookup"><span data-stu-id="f4ebe-119">The name of the load balancer.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4ebe-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f4ebe-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4ebe-121">すべてのロード バランサーのフロント エンド IP 構成を取得します。</span><span class="sxs-lookup"><span data-stu-id="f4ebe-121">Gets all the load balancer frontend IP configurations.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.FrontendIPConfiguration&gt; ListNext (this Microsoft.Azure.Management.Network.ILoadBalancerFrontendIPConfigurationsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.FrontendIPConfiguration&gt; ListNext(class Microsoft.Azure.Management.Network.ILoadBalancerFrontendIPConfigurationsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancerFrontendIPConfigurationsOperationsExtensions.ListNext(Microsoft.Azure.Management.Network.ILoadBalancerFrontendIPConfigurationsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As ILoadBalancerFrontendIPConfigurationsOperations, nextPageLink As String) As IPage(Of FrontendIPConfiguration)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Network.ILoadBalancerFrontendIPConfigurationsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.FrontendIPConfiguration&gt;" Usage="Microsoft.Azure.Management.Network.LoadBalancerFrontendIPConfigurationsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.FrontendIPConfiguration&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancerFrontendIPConfigurationsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f4ebe-122">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f4ebe-122">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="f4ebe-123">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="f4ebe-123">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4ebe-124">すべてのロード バランサーのフロント エンド IP 構成を取得します。</span><span class="sxs-lookup"><span data-stu-id="f4ebe-124">Gets all the load balancer frontend IP configurations.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.FrontendIPConfiguration&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.ILoadBalancerFrontendIPConfigurationsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.FrontendIPConfiguration&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.ILoadBalancerFrontendIPConfigurationsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancerFrontendIPConfigurationsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.ILoadBalancerFrontendIPConfigurationsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.ILoadBalancerFrontendIPConfigurationsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.FrontendIPConfiguration&gt;&gt;" Usage="Microsoft.Azure.Management.Network.LoadBalancerFrontendIPConfigurationsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LoadBalancerFrontendIPConfigurationsOperationsExtensions/&lt;ListNextAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.FrontendIPConfiguration&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancerFrontendIPConfigurationsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f4ebe-125">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f4ebe-125">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="f4ebe-126">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="f4ebe-126">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4ebe-127">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f4ebe-127">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4ebe-128">すべてのロード バランサーのフロント エンド IP 構成を取得します。</span><span class="sxs-lookup"><span data-stu-id="f4ebe-128">Gets all the load balancer frontend IP configurations.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>