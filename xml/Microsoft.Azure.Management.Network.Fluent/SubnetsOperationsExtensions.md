<Type Name="SubnetsOperationsExtensions" FullName="Microsoft.Azure.Management.Network.Fluent.SubnetsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class SubnetsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit SubnetsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.SubnetsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module SubnetsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type SubnetsOperationsExtensions = class" />
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
            <span data-ttu-id="fcf59-101">SubnetsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="fcf59-101">Extension methods for SubnetsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, string subnetName, Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner subnetParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, string subnetName, class Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner subnetParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.SubnetsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.ISubnetsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.ISubnetsOperations * string * string * string * Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.SubnetsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, virtualNetworkName, subnetName, subnetParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.SubnetsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.ISubnetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="subnetName" Type="System.String" />
        <Parameter Name="subnetParameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fcf59-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fcf59-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fcf59-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fcf59-103">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="fcf59-104">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="fcf59-104">The name of the virtual network.</span></span>
            </param>
        <param name="subnetName">
            <span data-ttu-id="fcf59-105">サブネットの名前。</span><span class="sxs-lookup"><span data-stu-id="fcf59-105">The name of the subnet.</span></span>
            </param>
        <param name="subnetParameters">
            <span data-ttu-id="fcf59-106">作成または更新サブネット操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="fcf59-106">Parameters supplied to the create or update subnet operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fcf59-107">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fcf59-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fcf59-108">作成するか、指定された仮想ネットワークのサブネットを更新します。</span><span class="sxs-lookup"><span data-stu-id="fcf59-108">Creates or updates a subnet in the specified virtual network.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.Fluent.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, string subnetName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.Fluent.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, string subnetName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.SubnetsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.Fluent.ISubnetsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.Fluent.ISubnetsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.SubnetsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, virtualNetworkName, subnetName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.SubnetsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.ISubnetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="subnetName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fcf59-109">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fcf59-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fcf59-110">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fcf59-110">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="fcf59-111">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="fcf59-111">The name of the virtual network.</span></span>
            </param>
        <param name="subnetName">
            <span data-ttu-id="fcf59-112">サブネットの名前。</span><span class="sxs-lookup"><span data-stu-id="fcf59-112">The name of the subnet.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fcf59-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fcf59-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fcf59-114">指定したサブネットを削除します。</span><span class="sxs-lookup"><span data-stu-id="fcf59-114">Deletes the specified subnet.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, string subnetName, Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner subnetParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, string subnetName, class Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner subnetParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.SubnetsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.ISubnetsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.ISubnetsOperations * string * string * string * Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.SubnetsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, virtualNetworkName, subnetName, subnetParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.SubnetsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.ISubnetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="subnetName" Type="System.String" />
        <Parameter Name="subnetParameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fcf59-115">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fcf59-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fcf59-116">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fcf59-116">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="fcf59-117">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="fcf59-117">The name of the virtual network.</span></span>
            </param>
        <param name="subnetName">
            <span data-ttu-id="fcf59-118">サブネットの名前。</span><span class="sxs-lookup"><span data-stu-id="fcf59-118">The name of the subnet.</span></span>
            </param>
        <param name="subnetParameters">
            <span data-ttu-id="fcf59-119">作成または更新サブネット操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="fcf59-119">Parameters supplied to the create or update subnet operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fcf59-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fcf59-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fcf59-121">作成するか、指定された仮想ネットワークのサブネットを更新します。</span><span class="sxs-lookup"><span data-stu-id="fcf59-121">Creates or updates a subnet in the specified virtual network.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.Fluent.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, string subnetName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.Fluent.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, string subnetName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.SubnetsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.Fluent.ISubnetsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.Fluent.ISubnetsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.SubnetsOperationsExtensions.DeleteAsync (operations, resourceGroupName, virtualNetworkName, subnetName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.SubnetsOperationsExtensions/&lt;DeleteAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.ISubnetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="subnetName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fcf59-122">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fcf59-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fcf59-123">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fcf59-123">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="fcf59-124">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="fcf59-124">The name of the virtual network.</span></span>
            </param>
        <param name="subnetName">
            <span data-ttu-id="fcf59-125">サブネットの名前。</span><span class="sxs-lookup"><span data-stu-id="fcf59-125">The name of the subnet.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fcf59-126">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fcf59-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fcf59-127">指定したサブネットを削除します。</span><span class="sxs-lookup"><span data-stu-id="fcf59-127">Deletes the specified subnet.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner&gt; GetAsync (this Microsoft.Azure.Management.Network.Fluent.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, string subnetName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner&gt; GetAsync(class Microsoft.Azure.Management.Network.Fluent.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, string subnetName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.SubnetsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.Fluent.ISubnetsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.Fluent.ISubnetsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.SubnetsOperationsExtensions.GetAsync (operations, resourceGroupName, virtualNetworkName, subnetName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.SubnetsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.ISubnetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="subnetName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fcf59-128">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fcf59-128">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fcf59-129">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fcf59-129">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="fcf59-130">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="fcf59-130">The name of the virtual network.</span></span>
            </param>
        <param name="subnetName">
            <span data-ttu-id="fcf59-131">サブネットの名前。</span><span class="sxs-lookup"><span data-stu-id="fcf59-131">The name of the subnet.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="fcf59-132">参照されているリソースを展開します。</span><span class="sxs-lookup"><span data-stu-id="fcf59-132">Expands referenced resources.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fcf59-133">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fcf59-133">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fcf59-134">仮想ネットワークおよびリソース グループによって指定されたサブネットを取得します。</span><span class="sxs-lookup"><span data-stu-id="fcf59-134">Gets the specified subnet by virtual network and resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.Fluent.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.Fluent.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.SubnetsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.Fluent.ISubnetsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.Fluent.ISubnetsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.SubnetsOperationsExtensions.ListAsync (operations, resourceGroupName, virtualNetworkName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.SubnetsOperationsExtensions/&lt;ListAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.ISubnetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fcf59-135">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fcf59-135">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fcf59-136">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fcf59-136">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="fcf59-137">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="fcf59-137">The name of the virtual network.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fcf59-138">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fcf59-138">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fcf59-139">仮想ネットワーク内のすべてのサブネットを取得します。</span><span class="sxs-lookup"><span data-stu-id="fcf59-139">Gets all subnets in a virtual network.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.Fluent.ISubnetsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.Fluent.ISubnetsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.SubnetsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.Fluent.ISubnetsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.Fluent.ISubnetsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.SubnetsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.SubnetsOperationsExtensions/&lt;ListNextAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.ISubnetsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fcf59-140">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fcf59-140">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="fcf59-141">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="fcf59-141">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fcf59-142">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fcf59-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fcf59-143">仮想ネットワーク内のすべてのサブネットを取得します。</span><span class="sxs-lookup"><span data-stu-id="fcf59-143">Gets all subnets in a virtual network.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>