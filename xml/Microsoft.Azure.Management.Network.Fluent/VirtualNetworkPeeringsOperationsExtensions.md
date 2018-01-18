<Type Name="VirtualNetworkPeeringsOperationsExtensions" FullName="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkPeeringsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VirtualNetworkPeeringsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VirtualNetworkPeeringsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkPeeringsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VirtualNetworkPeeringsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VirtualNetworkPeeringsOperationsExtensions = class" />
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
            <span data-ttu-id="ad6bb-101">VirtualNetworkPeeringsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="ad6bb-101">Extension methods for VirtualNetworkPeeringsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations operations, string resourceGroupName, string virtualNetworkName, string virtualNetworkPeeringName, Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner virtualNetworkPeeringParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations operations, string resourceGroupName, string virtualNetworkName, string virtualNetworkPeeringName, class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner virtualNetworkPeeringParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkPeeringsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations * string * string * string * Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkPeeringsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, virtualNetworkName, virtualNetworkPeeringName, virtualNetworkPeeringParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkPeeringsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="virtualNetworkPeeringName" Type="System.String" />
        <Parameter Name="virtualNetworkPeeringParameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ad6bb-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ad6bb-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ad6bb-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="ad6bb-103">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="ad6bb-104">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="ad6bb-104">The name of the virtual network.</span></span>
            </param>
        <param name="virtualNetworkPeeringName">
            <span data-ttu-id="ad6bb-105">ピアリングの名前。</span><span class="sxs-lookup"><span data-stu-id="ad6bb-105">The name of the peering.</span></span>
            </param>
        <param name="virtualNetworkPeeringParameters">
            <span data-ttu-id="ad6bb-106">作成または更新仮想ネットワークのピアリング操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="ad6bb-106">Parameters supplied to the create or update virtual network peering operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ad6bb-107">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ad6bb-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ad6bb-108">作成するか、指定された仮想ネットワークのピアリングを更新します。</span><span class="sxs-lookup"><span data-stu-id="ad6bb-108">Creates or updates a peering in the specified virtual network.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations operations, string resourceGroupName, string virtualNetworkName, string virtualNetworkPeeringName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations operations, string resourceGroupName, string virtualNetworkName, string virtualNetworkPeeringName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkPeeringsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkPeeringsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, virtualNetworkName, virtualNetworkPeeringName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkPeeringsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="virtualNetworkPeeringName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ad6bb-109">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ad6bb-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ad6bb-110">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="ad6bb-110">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="ad6bb-111">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="ad6bb-111">The name of the virtual network.</span></span>
            </param>
        <param name="virtualNetworkPeeringName">
            <span data-ttu-id="ad6bb-112">仮想ネットワークのピアリングの名前。</span><span class="sxs-lookup"><span data-stu-id="ad6bb-112">The name of the virtual network peering.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ad6bb-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ad6bb-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ad6bb-114">指定された仮想ネットワークのピアリングを削除します。</span><span class="sxs-lookup"><span data-stu-id="ad6bb-114">Deletes the specified virtual network peering.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations operations, string resourceGroupName, string virtualNetworkName, string virtualNetworkPeeringName, Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner virtualNetworkPeeringParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations operations, string resourceGroupName, string virtualNetworkName, string virtualNetworkPeeringName, class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner virtualNetworkPeeringParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkPeeringsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations * string * string * string * Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkPeeringsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, virtualNetworkName, virtualNetworkPeeringName, virtualNetworkPeeringParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkPeeringsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="virtualNetworkPeeringName" Type="System.String" />
        <Parameter Name="virtualNetworkPeeringParameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ad6bb-115">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ad6bb-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ad6bb-116">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="ad6bb-116">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="ad6bb-117">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="ad6bb-117">The name of the virtual network.</span></span>
            </param>
        <param name="virtualNetworkPeeringName">
            <span data-ttu-id="ad6bb-118">ピアリングの名前。</span><span class="sxs-lookup"><span data-stu-id="ad6bb-118">The name of the peering.</span></span>
            </param>
        <param name="virtualNetworkPeeringParameters">
            <span data-ttu-id="ad6bb-119">作成または更新仮想ネットワークのピアリング操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="ad6bb-119">Parameters supplied to the create or update virtual network peering operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ad6bb-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ad6bb-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ad6bb-121">作成するか、指定された仮想ネットワークのピアリングを更新します。</span><span class="sxs-lookup"><span data-stu-id="ad6bb-121">Creates or updates a peering in the specified virtual network.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations operations, string resourceGroupName, string virtualNetworkName, string virtualNetworkPeeringName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations operations, string resourceGroupName, string virtualNetworkName, string virtualNetworkPeeringName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkPeeringsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkPeeringsOperationsExtensions.DeleteAsync (operations, resourceGroupName, virtualNetworkName, virtualNetworkPeeringName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkPeeringsOperationsExtensions/&lt;DeleteAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="virtualNetworkPeeringName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ad6bb-122">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ad6bb-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ad6bb-123">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="ad6bb-123">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="ad6bb-124">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="ad6bb-124">The name of the virtual network.</span></span>
            </param>
        <param name="virtualNetworkPeeringName">
            <span data-ttu-id="ad6bb-125">仮想ネットワークのピアリングの名前。</span><span class="sxs-lookup"><span data-stu-id="ad6bb-125">The name of the virtual network peering.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ad6bb-126">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ad6bb-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ad6bb-127">指定された仮想ネットワークのピアリングを削除します。</span><span class="sxs-lookup"><span data-stu-id="ad6bb-127">Deletes the specified virtual network peering.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt; GetAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations operations, string resourceGroupName, string virtualNetworkName, string virtualNetworkPeeringName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt; GetAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations operations, string resourceGroupName, string virtualNetworkName, string virtualNetworkPeeringName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkPeeringsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkPeeringsOperationsExtensions.GetAsync (operations, resourceGroupName, virtualNetworkName, virtualNetworkPeeringName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkPeeringsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="virtualNetworkPeeringName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ad6bb-128">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ad6bb-128">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ad6bb-129">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="ad6bb-129">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="ad6bb-130">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="ad6bb-130">The name of the virtual network.</span></span>
            </param>
        <param name="virtualNetworkPeeringName">
            <span data-ttu-id="ad6bb-131">仮想ネットワークのピアリングの名前。</span><span class="sxs-lookup"><span data-stu-id="ad6bb-131">The name of the virtual network peering.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ad6bb-132">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ad6bb-132">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ad6bb-133">指定された仮想ネットワークのピアリングを取得します。</span><span class="sxs-lookup"><span data-stu-id="ad6bb-133">Gets the specified virtual network peering.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations operations, string resourceGroupName, string virtualNetworkName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations operations, string resourceGroupName, string virtualNetworkName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkPeeringsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkPeeringsOperationsExtensions.ListAsync (operations, resourceGroupName, virtualNetworkName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkPeeringsOperationsExtensions/&lt;ListAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ad6bb-134">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ad6bb-134">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ad6bb-135">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="ad6bb-135">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="ad6bb-136">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="ad6bb-136">The name of the virtual network.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ad6bb-137">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ad6bb-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ad6bb-138">仮想ネットワーク内のすべての仮想ネットワーク ペアリングを含めるを取得します。</span><span class="sxs-lookup"><span data-stu-id="ad6bb-138">Gets all virtual network peerings in a virtual network.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkPeeringsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkPeeringsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkPeeringsOperationsExtensions/&lt;ListNextAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkPeeringsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ad6bb-139">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ad6bb-139">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="ad6bb-140">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="ad6bb-140">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ad6bb-141">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ad6bb-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ad6bb-142">仮想ネットワーク内のすべての仮想ネットワーク ペアリングを含めるを取得します。</span><span class="sxs-lookup"><span data-stu-id="ad6bb-142">Gets all virtual network peerings in a virtual network.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>