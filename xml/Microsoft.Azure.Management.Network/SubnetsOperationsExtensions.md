<Type Name="SubnetsOperationsExtensions" FullName="Microsoft.Azure.Management.Network.SubnetsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class SubnetsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit SubnetsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.SubnetsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module SubnetsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type SubnetsOperationsExtensions = class" />
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
            <span data-ttu-id="3594d-101">SubnetsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="3594d-101">Extension methods for SubnetsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.Subnet BeginCreateOrUpdate (this Microsoft.Azure.Management.Network.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, string subnetName, Microsoft.Azure.Management.Network.Models.Subnet subnetParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.Subnet BeginCreateOrUpdate(class Microsoft.Azure.Management.Network.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, string subnetName, class Microsoft.Azure.Management.Network.Models.Subnet subnetParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Network.ISubnetsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Models.Subnet)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As ISubnetsOperations, resourceGroupName As String, virtualNetworkName As String, subnetName As String, subnetParameters As Subnet) As Subnet" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Network.ISubnetsOperations * string * string * string * Microsoft.Azure.Management.Network.Models.Subnet -&gt; Microsoft.Azure.Management.Network.Models.Subnet" Usage="Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, virtualNetworkName, subnetName, subnetParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.Subnet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ISubnetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="subnetName" Type="System.String" />
        <Parameter Name="subnetParameters" Type="Microsoft.Azure.Management.Network.Models.Subnet" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3594d-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3594d-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3594d-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="3594d-103">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="3594d-104">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="3594d-104">The name of the virtual network.</span></span>
            </param>
        <param name="subnetName">
            <span data-ttu-id="3594d-105">サブネットの名前。</span><span class="sxs-lookup"><span data-stu-id="3594d-105">The name of the subnet.</span></span>
            </param>
        <param name="subnetParameters">
            <span data-ttu-id="3594d-106">作成または更新サブネット操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="3594d-106">Parameters supplied to the create or update subnet operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3594d-107">作成するか、指定された仮想ネットワークのサブネットを更新します。</span><span class="sxs-lookup"><span data-stu-id="3594d-107">Creates or updates a subnet in the specified virtual network.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, string subnetName, Microsoft.Azure.Management.Network.Models.Subnet subnetParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.Subnet&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, string subnetName, class Microsoft.Azure.Management.Network.Models.Subnet subnetParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.ISubnetsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Models.Subnet,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.ISubnetsOperations * string * string * string * Microsoft.Azure.Management.Network.Models.Subnet * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt;" Usage="Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, virtualNetworkName, subnetName, subnetParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.SubnetsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ISubnetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="subnetName" Type="System.String" />
        <Parameter Name="subnetParameters" Type="Microsoft.Azure.Management.Network.Models.Subnet" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3594d-108">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3594d-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3594d-109">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="3594d-109">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="3594d-110">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="3594d-110">The name of the virtual network.</span></span>
            </param>
        <param name="subnetName">
            <span data-ttu-id="3594d-111">サブネットの名前。</span><span class="sxs-lookup"><span data-stu-id="3594d-111">The name of the subnet.</span></span>
            </param>
        <param name="subnetParameters">
            <span data-ttu-id="3594d-112">作成または更新サブネット操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="3594d-112">Parameters supplied to the create or update subnet operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3594d-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3594d-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3594d-114">作成するか、指定された仮想ネットワークのサブネットを更新します。</span><span class="sxs-lookup"><span data-stu-id="3594d-114">Creates or updates a subnet in the specified virtual network.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Network.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, string subnetName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Network.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, string subnetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Network.ISubnetsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As ISubnetsOperations, resourceGroupName As String, virtualNetworkName As String, subnetName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Network.ISubnetsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.BeginDelete (operations, resourceGroupName, virtualNetworkName, subnetName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ISubnetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="subnetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3594d-115">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3594d-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3594d-116">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="3594d-116">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="3594d-117">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="3594d-117">The name of the virtual network.</span></span>
            </param>
        <param name="subnetName">
            <span data-ttu-id="3594d-118">サブネットの名前。</span><span class="sxs-lookup"><span data-stu-id="3594d-118">The name of the subnet.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3594d-119">指定したサブネットを削除します。</span><span class="sxs-lookup"><span data-stu-id="3594d-119">Deletes the specified subnet.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, string subnetName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, string subnetName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.ISubnetsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.ISubnetsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, virtualNetworkName, subnetName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.SubnetsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ISubnetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="subnetName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3594d-120">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3594d-120">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3594d-121">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="3594d-121">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="3594d-122">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="3594d-122">The name of the virtual network.</span></span>
            </param>
        <param name="subnetName">
            <span data-ttu-id="3594d-123">サブネットの名前。</span><span class="sxs-lookup"><span data-stu-id="3594d-123">The name of the subnet.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3594d-124">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3594d-124">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3594d-125">指定したサブネットを削除します。</span><span class="sxs-lookup"><span data-stu-id="3594d-125">Deletes the specified subnet.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.Subnet CreateOrUpdate (this Microsoft.Azure.Management.Network.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, string subnetName, Microsoft.Azure.Management.Network.Models.Subnet subnetParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.Subnet CreateOrUpdate(class Microsoft.Azure.Management.Network.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, string subnetName, class Microsoft.Azure.Management.Network.Models.Subnet subnetParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Network.ISubnetsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Models.Subnet)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As ISubnetsOperations, resourceGroupName As String, virtualNetworkName As String, subnetName As String, subnetParameters As Subnet) As Subnet" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Network.ISubnetsOperations * string * string * string * Microsoft.Azure.Management.Network.Models.Subnet -&gt; Microsoft.Azure.Management.Network.Models.Subnet" Usage="Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, virtualNetworkName, subnetName, subnetParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.Subnet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ISubnetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="subnetName" Type="System.String" />
        <Parameter Name="subnetParameters" Type="Microsoft.Azure.Management.Network.Models.Subnet" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3594d-126">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3594d-126">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3594d-127">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="3594d-127">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="3594d-128">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="3594d-128">The name of the virtual network.</span></span>
            </param>
        <param name="subnetName">
            <span data-ttu-id="3594d-129">サブネットの名前。</span><span class="sxs-lookup"><span data-stu-id="3594d-129">The name of the subnet.</span></span>
            </param>
        <param name="subnetParameters">
            <span data-ttu-id="3594d-130">作成または更新サブネット操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="3594d-130">Parameters supplied to the create or update subnet operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3594d-131">作成するか、指定された仮想ネットワークのサブネットを更新します。</span><span class="sxs-lookup"><span data-stu-id="3594d-131">Creates or updates a subnet in the specified virtual network.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, string subnetName, Microsoft.Azure.Management.Network.Models.Subnet subnetParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.Subnet&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, string subnetName, class Microsoft.Azure.Management.Network.Models.Subnet subnetParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.ISubnetsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Models.Subnet,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.ISubnetsOperations * string * string * string * Microsoft.Azure.Management.Network.Models.Subnet * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt;" Usage="Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, virtualNetworkName, subnetName, subnetParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.SubnetsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ISubnetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="subnetName" Type="System.String" />
        <Parameter Name="subnetParameters" Type="Microsoft.Azure.Management.Network.Models.Subnet" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3594d-132">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3594d-132">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3594d-133">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="3594d-133">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="3594d-134">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="3594d-134">The name of the virtual network.</span></span>
            </param>
        <param name="subnetName">
            <span data-ttu-id="3594d-135">サブネットの名前。</span><span class="sxs-lookup"><span data-stu-id="3594d-135">The name of the subnet.</span></span>
            </param>
        <param name="subnetParameters">
            <span data-ttu-id="3594d-136">作成または更新サブネット操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="3594d-136">Parameters supplied to the create or update subnet operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3594d-137">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3594d-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3594d-138">作成するか、指定された仮想ネットワークのサブネットを更新します。</span><span class="sxs-lookup"><span data-stu-id="3594d-138">Creates or updates a subnet in the specified virtual network.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Network.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, string subnetName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Network.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, string subnetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.Delete(Microsoft.Azure.Management.Network.ISubnetsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As ISubnetsOperations, resourceGroupName As String, virtualNetworkName As String, subnetName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Network.ISubnetsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.Delete (operations, resourceGroupName, virtualNetworkName, subnetName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ISubnetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="subnetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3594d-139">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3594d-139">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3594d-140">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="3594d-140">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="3594d-141">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="3594d-141">The name of the virtual network.</span></span>
            </param>
        <param name="subnetName">
            <span data-ttu-id="3594d-142">サブネットの名前。</span><span class="sxs-lookup"><span data-stu-id="3594d-142">The name of the subnet.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3594d-143">指定したサブネットを削除します。</span><span class="sxs-lookup"><span data-stu-id="3594d-143">Deletes the specified subnet.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, string subnetName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, string subnetName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.ISubnetsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.ISubnetsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.DeleteAsync (operations, resourceGroupName, virtualNetworkName, subnetName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.SubnetsOperationsExtensions/&lt;DeleteAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ISubnetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="subnetName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3594d-144">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3594d-144">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3594d-145">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="3594d-145">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="3594d-146">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="3594d-146">The name of the virtual network.</span></span>
            </param>
        <param name="subnetName">
            <span data-ttu-id="3594d-147">サブネットの名前。</span><span class="sxs-lookup"><span data-stu-id="3594d-147">The name of the subnet.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3594d-148">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3594d-148">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3594d-149">指定したサブネットを削除します。</span><span class="sxs-lookup"><span data-stu-id="3594d-149">Deletes the specified subnet.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.Subnet Get (this Microsoft.Azure.Management.Network.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, string subnetName, string expand = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.Subnet Get(class Microsoft.Azure.Management.Network.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, string subnetName, string expand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.Get(Microsoft.Azure.Management.Network.ISubnetsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ISubnetsOperations, resourceGroupName As String, virtualNetworkName As String, subnetName As String, Optional expand As String = null) As Subnet" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Network.ISubnetsOperations * string * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.Subnet" Usage="Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.Get (operations, resourceGroupName, virtualNetworkName, subnetName, expand)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.Subnet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ISubnetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="subnetName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3594d-150">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3594d-150">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3594d-151">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="3594d-151">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="3594d-152">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="3594d-152">The name of the virtual network.</span></span>
            </param>
        <param name="subnetName">
            <span data-ttu-id="3594d-153">サブネットの名前。</span><span class="sxs-lookup"><span data-stu-id="3594d-153">The name of the subnet.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="3594d-154">参照されているリソースを展開します。</span><span class="sxs-lookup"><span data-stu-id="3594d-154">Expands referenced resources.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3594d-155">仮想ネットワークおよびリソース グループによって指定されたサブネットを取得します。</span><span class="sxs-lookup"><span data-stu-id="3594d-155">Gets the specified subnet by virtual network and resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt; GetAsync (this Microsoft.Azure.Management.Network.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, string subnetName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.Subnet&gt; GetAsync(class Microsoft.Azure.Management.Network.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, string subnetName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.ISubnetsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.ISubnetsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt;" Usage="Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.GetAsync (operations, resourceGroupName, virtualNetworkName, subnetName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.SubnetsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ISubnetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="subnetName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3594d-156">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3594d-156">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3594d-157">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="3594d-157">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="3594d-158">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="3594d-158">The name of the virtual network.</span></span>
            </param>
        <param name="subnetName">
            <span data-ttu-id="3594d-159">サブネットの名前。</span><span class="sxs-lookup"><span data-stu-id="3594d-159">The name of the subnet.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="3594d-160">参照されているリソースを展開します。</span><span class="sxs-lookup"><span data-stu-id="3594d-160">Expands referenced resources.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3594d-161">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3594d-161">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3594d-162">仮想ネットワークおよびリソース グループによって指定されたサブネットを取得します。</span><span class="sxs-lookup"><span data-stu-id="3594d-162">Gets the specified subnet by virtual network and resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt; List (this Microsoft.Azure.Management.Network.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.Subnet&gt; List(class Microsoft.Azure.Management.Network.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.List(Microsoft.Azure.Management.Network.ISubnetsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As ISubnetsOperations, resourceGroupName As String, virtualNetworkName As String) As IPage(Of Subnet)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Network.ISubnetsOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt;" Usage="Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.List (operations, resourceGroupName, virtualNetworkName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ISubnetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3594d-163">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3594d-163">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3594d-164">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="3594d-164">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="3594d-165">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="3594d-165">The name of the virtual network.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3594d-166">仮想ネットワーク内のすべてのサブネットを取得します。</span><span class="sxs-lookup"><span data-stu-id="3594d-166">Gets all subnets in a virtual network.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.Subnet&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.ISubnetsOperations operations, string resourceGroupName, string virtualNetworkName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.ISubnetsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.ISubnetsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt;&gt;" Usage="Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.ListAsync (operations, resourceGroupName, virtualNetworkName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.SubnetsOperationsExtensions/&lt;ListAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ISubnetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3594d-167">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3594d-167">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3594d-168">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="3594d-168">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="3594d-169">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="3594d-169">The name of the virtual network.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3594d-170">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3594d-170">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3594d-171">仮想ネットワーク内のすべてのサブネットを取得します。</span><span class="sxs-lookup"><span data-stu-id="3594d-171">Gets all subnets in a virtual network.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt; ListNext (this Microsoft.Azure.Management.Network.ISubnetsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.Subnet&gt; ListNext(class Microsoft.Azure.Management.Network.ISubnetsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.ListNext(Microsoft.Azure.Management.Network.ISubnetsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As ISubnetsOperations, nextPageLink As String) As IPage(Of Subnet)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Network.ISubnetsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt;" Usage="Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ISubnetsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3594d-172">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3594d-172">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3594d-173">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="3594d-173">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3594d-174">仮想ネットワーク内のすべてのサブネットを取得します。</span><span class="sxs-lookup"><span data-stu-id="3594d-174">Gets all subnets in a virtual network.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.ISubnetsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.Subnet&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.ISubnetsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.ISubnetsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.ISubnetsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt;&gt;" Usage="Microsoft.Azure.Management.Network.SubnetsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.SubnetsOperationsExtensions/&lt;ListNextAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ISubnetsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3594d-175">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3594d-175">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3594d-176">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="3594d-176">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3594d-177">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3594d-177">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3594d-178">仮想ネットワーク内のすべてのサブネットを取得します。</span><span class="sxs-lookup"><span data-stu-id="3594d-178">Gets all subnets in a virtual network.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>