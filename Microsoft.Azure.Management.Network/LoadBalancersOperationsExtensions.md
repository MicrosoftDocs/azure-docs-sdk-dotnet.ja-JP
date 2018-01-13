<Type Name="LoadBalancersOperationsExtensions" FullName="Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class LoadBalancersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit LoadBalancersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module LoadBalancersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type LoadBalancersOperationsExtensions = class" />
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
            <span data-ttu-id="311eb-101">LoadBalancersOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="311eb-101">Extension methods for LoadBalancersOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.LoadBalancer BeginCreateOrUpdate (this Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, Microsoft.Azure.Management.Network.Models.LoadBalancer parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.LoadBalancer BeginCreateOrUpdate(class Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, class Microsoft.Azure.Management.Network.Models.LoadBalancer parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Network.ILoadBalancersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.LoadBalancer)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As ILoadBalancersOperations, resourceGroupName As String, loadBalancerName As String, parameters As LoadBalancer) As LoadBalancer" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Network.ILoadBalancersOperations * string * string * Microsoft.Azure.Management.Network.Models.LoadBalancer -&gt; Microsoft.Azure.Management.Network.Models.LoadBalancer" Usage="Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, loadBalancerName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.LoadBalancer</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.LoadBalancer" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="311eb-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="311eb-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="311eb-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="311eb-103">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="311eb-104">ロード バランサーの名前。</span><span class="sxs-lookup"><span data-stu-id="311eb-104">The name of the load balancer.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="311eb-105">作成または更新のロード バランサーの操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="311eb-105">Parameters supplied to the create or update load balancer operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="311eb-106">作成するか、ロード バランサーを更新します。</span><span class="sxs-lookup"><span data-stu-id="311eb-106">Creates or updates a load balancer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, Microsoft.Azure.Management.Network.Models.LoadBalancer parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.LoadBalancer&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, class Microsoft.Azure.Management.Network.Models.LoadBalancer parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.ILoadBalancersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.LoadBalancer,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.ILoadBalancersOperations * string * string * Microsoft.Azure.Management.Network.Models.LoadBalancer * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;" Usage="Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, loadBalancerName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.LoadBalancer" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="311eb-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="311eb-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="311eb-108">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="311eb-108">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="311eb-109">ロード バランサーの名前。</span><span class="sxs-lookup"><span data-stu-id="311eb-109">The name of the load balancer.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="311eb-110">作成または更新のロード バランサーの操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="311eb-110">Parameters supplied to the create or update load balancer operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="311eb-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="311eb-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="311eb-112">作成するか、ロード バランサーを更新します。</span><span class="sxs-lookup"><span data-stu-id="311eb-112">Creates or updates a load balancer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Network.ILoadBalancersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As ILoadBalancersOperations, resourceGroupName As String, loadBalancerName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Network.ILoadBalancersOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.BeginDelete (operations, resourceGroupName, loadBalancerName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="311eb-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="311eb-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="311eb-114">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="311eb-114">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="311eb-115">ロード バランサーの名前。</span><span class="sxs-lookup"><span data-stu-id="311eb-115">The name of the load balancer.</span></span>
            </param>
        <summary>
            <span data-ttu-id="311eb-116">指定されたロード バランサーを削除します。</span><span class="sxs-lookup"><span data-stu-id="311eb-116">Deletes the specified load balancer.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.ILoadBalancersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.ILoadBalancersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, loadBalancerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions/&lt;BeginDeleteAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="311eb-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="311eb-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="311eb-118">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="311eb-118">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="311eb-119">ロード バランサーの名前。</span><span class="sxs-lookup"><span data-stu-id="311eb-119">The name of the load balancer.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="311eb-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="311eb-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="311eb-121">指定されたロード バランサーを削除します。</span><span class="sxs-lookup"><span data-stu-id="311eb-121">Deletes the specified load balancer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateTags">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.LoadBalancer BeginUpdateTags (this Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, Microsoft.Azure.Management.Network.Models.TagsObject parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.LoadBalancer BeginUpdateTags(class Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.BeginUpdateTags(Microsoft.Azure.Management.Network.ILoadBalancersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdateTags (operations As ILoadBalancersOperations, resourceGroupName As String, loadBalancerName As String, parameters As TagsObject) As LoadBalancer" />
      <MemberSignature Language="F#" Value="static member BeginUpdateTags : Microsoft.Azure.Management.Network.ILoadBalancersOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject -&gt; Microsoft.Azure.Management.Network.Models.LoadBalancer" Usage="Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.BeginUpdateTags (operations, resourceGroupName, loadBalancerName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.LoadBalancer</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="311eb-122">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="311eb-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="311eb-123">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="311eb-123">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="311eb-124">ロード バランサーの名前。</span><span class="sxs-lookup"><span data-stu-id="311eb-124">The name of the load balancer.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="311eb-125">ロード バランサーのタグを更新する指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="311eb-125">Parameters supplied to update load balancer tags.</span></span>
            </param>
        <summary>
            <span data-ttu-id="311eb-126">ロード バランサーのタグを更新します。</span><span class="sxs-lookup"><span data-stu-id="311eb-126">Updates a load balancer tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateTagsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt; BeginUpdateTagsAsync (this Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, Microsoft.Azure.Management.Network.Models.TagsObject parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.LoadBalancer&gt; BeginUpdateTagsAsync(class Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.BeginUpdateTagsAsync(Microsoft.Azure.Management.Network.ILoadBalancersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateTagsAsync : Microsoft.Azure.Management.Network.ILoadBalancersOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;" Usage="Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.BeginUpdateTagsAsync (operations, resourceGroupName, loadBalancerName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions/&lt;BeginUpdateTagsAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="311eb-127">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="311eb-127">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="311eb-128">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="311eb-128">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="311eb-129">ロード バランサーの名前。</span><span class="sxs-lookup"><span data-stu-id="311eb-129">The name of the load balancer.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="311eb-130">ロード バランサーのタグを更新する指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="311eb-130">Parameters supplied to update load balancer tags.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="311eb-131">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="311eb-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="311eb-132">ロード バランサーのタグを更新します。</span><span class="sxs-lookup"><span data-stu-id="311eb-132">Updates a load balancer tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.LoadBalancer CreateOrUpdate (this Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, Microsoft.Azure.Management.Network.Models.LoadBalancer parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.LoadBalancer CreateOrUpdate(class Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, class Microsoft.Azure.Management.Network.Models.LoadBalancer parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Network.ILoadBalancersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.LoadBalancer)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As ILoadBalancersOperations, resourceGroupName As String, loadBalancerName As String, parameters As LoadBalancer) As LoadBalancer" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Network.ILoadBalancersOperations * string * string * Microsoft.Azure.Management.Network.Models.LoadBalancer -&gt; Microsoft.Azure.Management.Network.Models.LoadBalancer" Usage="Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, loadBalancerName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.LoadBalancer</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.LoadBalancer" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="311eb-133">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="311eb-133">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="311eb-134">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="311eb-134">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="311eb-135">ロード バランサーの名前。</span><span class="sxs-lookup"><span data-stu-id="311eb-135">The name of the load balancer.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="311eb-136">作成または更新のロード バランサーの操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="311eb-136">Parameters supplied to the create or update load balancer operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="311eb-137">作成するか、ロード バランサーを更新します。</span><span class="sxs-lookup"><span data-stu-id="311eb-137">Creates or updates a load balancer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, Microsoft.Azure.Management.Network.Models.LoadBalancer parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.LoadBalancer&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, class Microsoft.Azure.Management.Network.Models.LoadBalancer parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.ILoadBalancersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.LoadBalancer,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.ILoadBalancersOperations * string * string * Microsoft.Azure.Management.Network.Models.LoadBalancer * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;" Usage="Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, loadBalancerName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.LoadBalancer" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="311eb-138">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="311eb-138">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="311eb-139">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="311eb-139">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="311eb-140">ロード バランサーの名前。</span><span class="sxs-lookup"><span data-stu-id="311eb-140">The name of the load balancer.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="311eb-141">作成または更新のロード バランサーの操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="311eb-141">Parameters supplied to the create or update load balancer operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="311eb-142">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="311eb-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="311eb-143">作成するか、ロード バランサーを更新します。</span><span class="sxs-lookup"><span data-stu-id="311eb-143">Creates or updates a load balancer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.Delete(Microsoft.Azure.Management.Network.ILoadBalancersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As ILoadBalancersOperations, resourceGroupName As String, loadBalancerName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Network.ILoadBalancersOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.Delete (operations, resourceGroupName, loadBalancerName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="311eb-144">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="311eb-144">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="311eb-145">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="311eb-145">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="311eb-146">ロード バランサーの名前。</span><span class="sxs-lookup"><span data-stu-id="311eb-146">The name of the load balancer.</span></span>
            </param>
        <summary>
            <span data-ttu-id="311eb-147">指定されたロード バランサーを削除します。</span><span class="sxs-lookup"><span data-stu-id="311eb-147">Deletes the specified load balancer.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.ILoadBalancersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.ILoadBalancersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.DeleteAsync (operations, resourceGroupName, loadBalancerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions/&lt;DeleteAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="311eb-148">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="311eb-148">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="311eb-149">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="311eb-149">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="311eb-150">ロード バランサーの名前。</span><span class="sxs-lookup"><span data-stu-id="311eb-150">The name of the load balancer.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="311eb-151">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="311eb-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="311eb-152">指定されたロード バランサーを削除します。</span><span class="sxs-lookup"><span data-stu-id="311eb-152">Deletes the specified load balancer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.LoadBalancer Get (this Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, string expand = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.LoadBalancer Get(class Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, string expand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.Get(Microsoft.Azure.Management.Network.ILoadBalancersOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ILoadBalancersOperations, resourceGroupName As String, loadBalancerName As String, Optional expand As String = null) As LoadBalancer" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Network.ILoadBalancersOperations * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.LoadBalancer" Usage="Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.Get (operations, resourceGroupName, loadBalancerName, expand)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.LoadBalancer</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="311eb-153">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="311eb-153">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="311eb-154">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="311eb-154">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="311eb-155">ロード バランサーの名前。</span><span class="sxs-lookup"><span data-stu-id="311eb-155">The name of the load balancer.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="311eb-156">参照されているリソースを展開します。</span><span class="sxs-lookup"><span data-stu-id="311eb-156">Expands referenced resources.</span></span>
            </param>
        <summary>
            <span data-ttu-id="311eb-157">指定されたロード バランサーを取得します。</span><span class="sxs-lookup"><span data-stu-id="311eb-157">Gets the specified load balancer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt; GetAsync (this Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.LoadBalancer&gt; GetAsync(class Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.ILoadBalancersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.ILoadBalancersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;" Usage="Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.GetAsync (operations, resourceGroupName, loadBalancerName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="311eb-158">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="311eb-158">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="311eb-159">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="311eb-159">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="311eb-160">ロード バランサーの名前。</span><span class="sxs-lookup"><span data-stu-id="311eb-160">The name of the load balancer.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="311eb-161">参照されているリソースを展開します。</span><span class="sxs-lookup"><span data-stu-id="311eb-161">Expands referenced resources.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="311eb-162">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="311eb-162">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="311eb-163">指定されたロード バランサーを取得します。</span><span class="sxs-lookup"><span data-stu-id="311eb-163">Gets the specified load balancer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt; List (this Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.LoadBalancer&gt; List(class Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.List(Microsoft.Azure.Management.Network.ILoadBalancersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As ILoadBalancersOperations, resourceGroupName As String) As IPage(Of LoadBalancer)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Network.ILoadBalancersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;" Usage="Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.List (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="311eb-164">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="311eb-164">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="311eb-165">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="311eb-165">The name of the resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="311eb-166">リソース グループ内のすべてのロード バランサーを取得します。</span><span class="sxs-lookup"><span data-stu-id="311eb-166">Gets all the load balancers in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAll">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt; ListAll (this Microsoft.Azure.Management.Network.ILoadBalancersOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.LoadBalancer&gt; ListAll(class Microsoft.Azure.Management.Network.ILoadBalancersOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.ListAll(Microsoft.Azure.Management.Network.ILoadBalancersOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAll (operations As ILoadBalancersOperations) As IPage(Of LoadBalancer)" />
      <MemberSignature Language="F#" Value="static member ListAll : Microsoft.Azure.Management.Network.ILoadBalancersOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;" Usage="Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.ListAll operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancersOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="311eb-167">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="311eb-167">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="311eb-168">サブスクリプションのすべてのロード バランサーを取得します。</span><span class="sxs-lookup"><span data-stu-id="311eb-168">Gets all the load balancers in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;&gt; ListAllAsync (this Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;&gt; ListAllAsync(class Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.ListAllAsync(Microsoft.Azure.Management.Network.ILoadBalancersOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllAsync : Microsoft.Azure.Management.Network.ILoadBalancersOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;&gt;" Usage="Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.ListAllAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions/&lt;ListAllAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="311eb-169">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="311eb-169">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="311eb-170">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="311eb-170">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="311eb-171">サブスクリプションのすべてのロード バランサーを取得します。</span><span class="sxs-lookup"><span data-stu-id="311eb-171">Gets all the load balancers in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt; ListAllNext (this Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.LoadBalancer&gt; ListAllNext(class Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.ListAllNext(Microsoft.Azure.Management.Network.ILoadBalancersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAllNext (operations As ILoadBalancersOperations, nextPageLink As String) As IPage(Of LoadBalancer)" />
      <MemberSignature Language="F#" Value="static member ListAllNext : Microsoft.Azure.Management.Network.ILoadBalancersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;" Usage="Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.ListAllNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="311eb-172">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="311eb-172">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="311eb-173">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="311eb-173">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="311eb-174">サブスクリプションのすべてのロード バランサーを取得します。</span><span class="sxs-lookup"><span data-stu-id="311eb-174">Gets all the load balancers in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;&gt; ListAllNextAsync (this Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;&gt; ListAllNextAsync(class Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.ListAllNextAsync(Microsoft.Azure.Management.Network.ILoadBalancersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllNextAsync : Microsoft.Azure.Management.Network.ILoadBalancersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;&gt;" Usage="Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.ListAllNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions/&lt;ListAllNextAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="311eb-175">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="311eb-175">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="311eb-176">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="311eb-176">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="311eb-177">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="311eb-177">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="311eb-178">サブスクリプションのすべてのロード バランサーを取得します。</span><span class="sxs-lookup"><span data-stu-id="311eb-178">Gets all the load balancers in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.ILoadBalancersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.ILoadBalancersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;&gt;" Usage="Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.ListAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions/&lt;ListAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="311eb-179">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="311eb-179">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="311eb-180">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="311eb-180">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="311eb-181">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="311eb-181">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="311eb-182">リソース グループ内のすべてのロード バランサーを取得します。</span><span class="sxs-lookup"><span data-stu-id="311eb-182">Gets all the load balancers in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt; ListNext (this Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.LoadBalancer&gt; ListNext(class Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.ListNext(Microsoft.Azure.Management.Network.ILoadBalancersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As ILoadBalancersOperations, nextPageLink As String) As IPage(Of LoadBalancer)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Network.ILoadBalancersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;" Usage="Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="311eb-183">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="311eb-183">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="311eb-184">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="311eb-184">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="311eb-185">リソース グループ内のすべてのロード バランサーを取得します。</span><span class="sxs-lookup"><span data-stu-id="311eb-185">Gets all the load balancers in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.ILoadBalancersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.ILoadBalancersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;&gt;" Usage="Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions/&lt;ListNextAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="311eb-186">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="311eb-186">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="311eb-187">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="311eb-187">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="311eb-188">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="311eb-188">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="311eb-189">リソース グループ内のすべてのロード バランサーを取得します。</span><span class="sxs-lookup"><span data-stu-id="311eb-189">Gets all the load balancers in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTags">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.LoadBalancer UpdateTags (this Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, Microsoft.Azure.Management.Network.Models.TagsObject parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.LoadBalancer UpdateTags(class Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.UpdateTags(Microsoft.Azure.Management.Network.ILoadBalancersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpdateTags (operations As ILoadBalancersOperations, resourceGroupName As String, loadBalancerName As String, parameters As TagsObject) As LoadBalancer" />
      <MemberSignature Language="F#" Value="static member UpdateTags : Microsoft.Azure.Management.Network.ILoadBalancersOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject -&gt; Microsoft.Azure.Management.Network.Models.LoadBalancer" Usage="Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.UpdateTags (operations, resourceGroupName, loadBalancerName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.LoadBalancer</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="311eb-190">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="311eb-190">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="311eb-191">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="311eb-191">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="311eb-192">ロード バランサーの名前。</span><span class="sxs-lookup"><span data-stu-id="311eb-192">The name of the load balancer.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="311eb-193">ロード バランサーのタグを更新する指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="311eb-193">Parameters supplied to update load balancer tags.</span></span>
            </param>
        <summary>
            <span data-ttu-id="311eb-194">ロード バランサーのタグを更新します。</span><span class="sxs-lookup"><span data-stu-id="311eb-194">Updates a load balancer tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTagsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt; UpdateTagsAsync (this Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, Microsoft.Azure.Management.Network.Models.TagsObject parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.LoadBalancer&gt; UpdateTagsAsync(class Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.UpdateTagsAsync(Microsoft.Azure.Management.Network.ILoadBalancersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateTagsAsync : Microsoft.Azure.Management.Network.ILoadBalancersOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;" Usage="Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.UpdateTagsAsync (operations, resourceGroupName, loadBalancerName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions/&lt;UpdateTagsAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="311eb-195">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="311eb-195">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="311eb-196">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="311eb-196">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="311eb-197">ロード バランサーの名前。</span><span class="sxs-lookup"><span data-stu-id="311eb-197">The name of the load balancer.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="311eb-198">ロード バランサーのタグを更新する指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="311eb-198">Parameters supplied to update load balancer tags.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="311eb-199">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="311eb-199">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="311eb-200">ロード バランサーのタグを更新します。</span><span class="sxs-lookup"><span data-stu-id="311eb-200">Updates a load balancer tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>