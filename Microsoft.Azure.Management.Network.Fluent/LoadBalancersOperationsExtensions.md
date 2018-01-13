<Type Name="LoadBalancersOperationsExtensions" FullName="Microsoft.Azure.Management.Network.Fluent.LoadBalancersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class LoadBalancersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit LoadBalancersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.LoadBalancersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module LoadBalancersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type LoadBalancersOperationsExtensions = class" />
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
            <span data-ttu-id="03b84-101">LoadBalancersOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="03b84-101">Extension methods for LoadBalancersOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, class Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancersOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.ILoadBalancersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.ILoadBalancersOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.LoadBalancersOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, loadBalancerName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.LoadBalancersOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="03b84-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="03b84-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="03b84-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="03b84-103">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="03b84-104">ロード バランサーの名前。</span><span class="sxs-lookup"><span data-stu-id="03b84-104">The name of the load balancer.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="03b84-105">作成または更新のロード バランサーの操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="03b84-105">Parameters supplied to the create or update load balancer operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="03b84-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="03b84-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="03b84-107">作成するか、ロード バランサーを更新します。</span><span class="sxs-lookup"><span data-stu-id="03b84-107">Creates or updates a load balancer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.Fluent.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.Fluent.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancersOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.Fluent.ILoadBalancersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.Fluent.ILoadBalancersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.LoadBalancersOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, loadBalancerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.LoadBalancersOperationsExtensions/&lt;BeginDeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="03b84-108">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="03b84-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="03b84-109">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="03b84-109">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="03b84-110">ロード バランサーの名前。</span><span class="sxs-lookup"><span data-stu-id="03b84-110">The name of the load balancer.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="03b84-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="03b84-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="03b84-112">指定されたロード バランサーを削除します。</span><span class="sxs-lookup"><span data-stu-id="03b84-112">Deletes the specified load balancer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, class Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancersOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.ILoadBalancersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.ILoadBalancersOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.LoadBalancersOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, loadBalancerName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.LoadBalancersOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="03b84-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="03b84-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="03b84-114">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="03b84-114">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="03b84-115">ロード バランサーの名前。</span><span class="sxs-lookup"><span data-stu-id="03b84-115">The name of the load balancer.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="03b84-116">作成または更新のロード バランサーの操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="03b84-116">Parameters supplied to the create or update load balancer operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="03b84-117">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="03b84-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="03b84-118">作成するか、ロード バランサーを更新します。</span><span class="sxs-lookup"><span data-stu-id="03b84-118">Creates or updates a load balancer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.Fluent.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.Fluent.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancersOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.Fluent.ILoadBalancersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.Fluent.ILoadBalancersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.LoadBalancersOperationsExtensions.DeleteAsync (operations, resourceGroupName, loadBalancerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.LoadBalancersOperationsExtensions/&lt;DeleteAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="03b84-119">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="03b84-119">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="03b84-120">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="03b84-120">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="03b84-121">ロード バランサーの名前。</span><span class="sxs-lookup"><span data-stu-id="03b84-121">The name of the load balancer.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="03b84-122">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="03b84-122">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="03b84-123">指定されたロード バランサーを削除します。</span><span class="sxs-lookup"><span data-stu-id="03b84-123">Deletes the specified load balancer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner&gt; GetAsync (this Microsoft.Azure.Management.Network.Fluent.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner&gt; GetAsync(class Microsoft.Azure.Management.Network.Fluent.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancersOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.Fluent.ILoadBalancersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.Fluent.ILoadBalancersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.LoadBalancersOperationsExtensions.GetAsync (operations, resourceGroupName, loadBalancerName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.LoadBalancersOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="03b84-124">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="03b84-124">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="03b84-125">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="03b84-125">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="03b84-126">ロード バランサーの名前。</span><span class="sxs-lookup"><span data-stu-id="03b84-126">The name of the load balancer.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="03b84-127">参照されているリソースを展開します。</span><span class="sxs-lookup"><span data-stu-id="03b84-127">Expands referenced resources.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="03b84-128">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="03b84-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="03b84-129">指定されたロード バランサーを取得します。</span><span class="sxs-lookup"><span data-stu-id="03b84-129">Gets the specified load balancer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner&gt;&gt; ListAllAsync (this Microsoft.Azure.Management.Network.Fluent.ILoadBalancersOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner&gt;&gt; ListAllAsync(class Microsoft.Azure.Management.Network.Fluent.ILoadBalancersOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancersOperationsExtensions.ListAllAsync(Microsoft.Azure.Management.Network.Fluent.ILoadBalancersOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllAsync : Microsoft.Azure.Management.Network.Fluent.ILoadBalancersOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.LoadBalancersOperationsExtensions.ListAllAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.LoadBalancersOperationsExtensions/&lt;ListAllAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="03b84-130">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="03b84-130">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="03b84-131">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="03b84-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="03b84-132">サブスクリプションのすべてのロード バランサーを取得します。</span><span class="sxs-lookup"><span data-stu-id="03b84-132">Gets all the load balancers in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner&gt;&gt; ListAllNextAsync (this Microsoft.Azure.Management.Network.Fluent.ILoadBalancersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner&gt;&gt; ListAllNextAsync(class Microsoft.Azure.Management.Network.Fluent.ILoadBalancersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancersOperationsExtensions.ListAllNextAsync(Microsoft.Azure.Management.Network.Fluent.ILoadBalancersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllNextAsync : Microsoft.Azure.Management.Network.Fluent.ILoadBalancersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.LoadBalancersOperationsExtensions.ListAllNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.LoadBalancersOperationsExtensions/&lt;ListAllNextAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="03b84-133">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="03b84-133">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="03b84-134">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="03b84-134">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="03b84-135">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="03b84-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="03b84-136">サブスクリプションのすべてのロード バランサーを取得します。</span><span class="sxs-lookup"><span data-stu-id="03b84-136">Gets all the load balancers in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.Fluent.ILoadBalancersOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.Fluent.ILoadBalancersOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancersOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.Fluent.ILoadBalancersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.Fluent.ILoadBalancersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.LoadBalancersOperationsExtensions.ListAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.LoadBalancersOperationsExtensions/&lt;ListAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="03b84-137">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="03b84-137">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="03b84-138">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="03b84-138">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="03b84-139">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="03b84-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="03b84-140">リソース グループ内のすべてのロード バランサーを取得します。</span><span class="sxs-lookup"><span data-stu-id="03b84-140">Gets all the load balancers in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.Fluent.ILoadBalancersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.Fluent.ILoadBalancersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancersOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.Fluent.ILoadBalancersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.Fluent.ILoadBalancersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.LoadBalancersOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.LoadBalancersOperationsExtensions/&lt;ListNextAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="03b84-141">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="03b84-141">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="03b84-142">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="03b84-142">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="03b84-143">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="03b84-143">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="03b84-144">リソース グループ内のすべてのロード バランサーを取得します。</span><span class="sxs-lookup"><span data-stu-id="03b84-144">Gets all the load balancers in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>