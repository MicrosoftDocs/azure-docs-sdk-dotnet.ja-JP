<Type Name="VirtualNetworkGatewaysOperationsExtensions" FullName="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VirtualNetworkGatewaysOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VirtualNetworkGatewaysOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VirtualNetworkGatewaysOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VirtualNetworkGatewaysOperationsExtensions = class" />
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
            <span data-ttu-id="cd00c-101">VirtualNetworkGatewaysOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="cd00c-101">Extension methods for VirtualNetworkGatewaysOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway BeginCreateOrUpdate (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway BeginCreateOrUpdate(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayName As String, parameters As VirtualNetworkGateway) As VirtualNetworkGateway" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway -&gt; Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, virtualNetworkGatewayName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-103">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="cd00c-104">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-104">The name of the virtual network gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="cd00c-105">作成または更新の各仮想ネットワーク ゲートウェイの操作に渡されるパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-105">Parameters supplied to create or update virtual network gateway operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-106">作成するか、指定されたリソース グループに仮想ネットワーク ゲートウェイを更新します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-106">Creates or updates a virtual network gateway in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, virtualNetworkGatewayName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-108">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-108">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="cd00c-109">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-109">The name of the virtual network gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="cd00c-110">作成または更新の各仮想ネットワーク ゲートウェイの操作に渡されるパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-110">Parameters supplied to create or update virtual network gateway operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cd00c-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cd00c-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-112">作成するか、指定されたリソース グループに仮想ネットワーク ゲートウェイを更新します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-112">Creates or updates a virtual network gateway in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginDelete (operations, resourceGroupName, virtualNetworkGatewayName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-114">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-114">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="cd00c-115">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-115">The name of the virtual network gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-116">指定された仮想ネットワーク ゲートウェイを削除します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-116">Deletes the specified virtual network gateway.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, virtualNetworkGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;BeginDeleteAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-118">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-118">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="cd00c-119">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-119">The name of the virtual network gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cd00c-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cd00c-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-121">指定された仮想ネットワーク ゲートウェイを削除します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-121">Deletes the specified virtual network gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGeneratevpnclientpackage">
      <MemberSignature Language="C#" Value="public static string BeginGeneratevpnclientpackage (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Models.VpnClientParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string BeginGeneratevpnclientpackage(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.VpnClientParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginGeneratevpnclientpackage(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VpnClientParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginGeneratevpnclientpackage (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayName As String, parameters As VpnClientParameters) As String" />
      <MemberSignature Language="F#" Value="static member BeginGeneratevpnclientpackage : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.VpnClientParameters -&gt; string" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginGeneratevpnclientpackage (operations, resourceGroupName, virtualNetworkGatewayName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VpnClientParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-122">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-123">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-123">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="cd00c-124">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-124">The name of the virtual network gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="cd00c-125">パラメーターは、VPN クライアント パッケージの操作を生成の仮想ネットワーク ゲートウェイを指定します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-125">Parameters supplied to the generate virtual network gateway VPN client package operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-126">指定されたリソース グループ内の仮想ネットワーク ゲートウェイのクライアントを P2S VPN クライアント パッケージを生成します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-126">Generates VPN client package for P2S client of the virtual network gateway in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGeneratevpnclientpackageAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;string&gt; BeginGeneratevpnclientpackageAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Models.VpnClientParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;string&gt; BeginGeneratevpnclientpackageAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.VpnClientParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginGeneratevpnclientpackageAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VpnClientParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGeneratevpnclientpackageAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.VpnClientParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginGeneratevpnclientpackageAsync (operations, resourceGroupName, virtualNetworkGatewayName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;BeginGeneratevpnclientpackageAsync&gt;d__43))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VpnClientParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-127">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-127">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-128">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-128">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="cd00c-129">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-129">The name of the virtual network gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="cd00c-130">パラメーターは、VPN クライアント パッケージの操作を生成の仮想ネットワーク ゲートウェイを指定します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-130">Parameters supplied to the generate virtual network gateway VPN client package operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cd00c-131">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cd00c-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-132">指定されたリソース グループ内の仮想ネットワーク ゲートウェイのクライアントを P2S VPN クライアント パッケージを生成します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-132">Generates VPN client package for P2S client of the virtual network gateway in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGenerateVpnProfile">
      <MemberSignature Language="C#" Value="public static string BeginGenerateVpnProfile (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Models.VpnClientParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string BeginGenerateVpnProfile(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.VpnClientParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginGenerateVpnProfile(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VpnClientParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginGenerateVpnProfile (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayName As String, parameters As VpnClientParameters) As String" />
      <MemberSignature Language="F#" Value="static member BeginGenerateVpnProfile : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.VpnClientParameters -&gt; string" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginGenerateVpnProfile (operations, resourceGroupName, virtualNetworkGatewayName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VpnClientParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-133">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-133">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-134">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-134">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="cd00c-135">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-135">The name of the virtual network gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="cd00c-136">パラメーターは、VPN クライアント パッケージの操作を生成の仮想ネットワーク ゲートウェイを指定します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-136">Parameters supplied to the generate virtual network gateway VPN client package operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-137">指定されたリソース グループ内の仮想ネットワーク ゲートウェイのクライアントを P2S VPN プロファイルを生成します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-137">Generates VPN profile for P2S client of the virtual network gateway in the specified resource group.</span></span> <span data-ttu-id="cd00c-138">IKEV2 および radius ベースの認証に使用されます。</span><span class="sxs-lookup"><span data-stu-id="cd00c-138">Used for IKEV2 and radius based authentication.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGenerateVpnProfileAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;string&gt; BeginGenerateVpnProfileAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Models.VpnClientParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;string&gt; BeginGenerateVpnProfileAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.VpnClientParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginGenerateVpnProfileAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VpnClientParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGenerateVpnProfileAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.VpnClientParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginGenerateVpnProfileAsync (operations, resourceGroupName, virtualNetworkGatewayName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;BeginGenerateVpnProfileAsync&gt;d__45))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VpnClientParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-139">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-139">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-140">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-140">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="cd00c-141">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-141">The name of the virtual network gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="cd00c-142">パラメーターは、VPN クライアント パッケージの操作を生成の仮想ネットワーク ゲートウェイを指定します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-142">Parameters supplied to the generate virtual network gateway VPN client package operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cd00c-143">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cd00c-143">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-144">指定されたリソース グループ内の仮想ネットワーク ゲートウェイのクライアントを P2S VPN プロファイルを生成します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-144">Generates VPN profile for P2S client of the virtual network gateway in the specified resource group.</span></span> <span data-ttu-id="cd00c-145">IKEV2 および radius ベースの認証に使用されます。</span><span class="sxs-lookup"><span data-stu-id="cd00c-145">Used for IKEV2 and radius based authentication.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetAdvertisedRoutes">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.GatewayRouteListResult BeginGetAdvertisedRoutes (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string peer);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.GatewayRouteListResult BeginGetAdvertisedRoutes(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string peer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginGetAdvertisedRoutes(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginGetAdvertisedRoutes (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayName As String, peer As String) As GatewayRouteListResult" />
      <MemberSignature Language="F#" Value="static member BeginGetAdvertisedRoutes : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.GatewayRouteListResult" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginGetAdvertisedRoutes (operations, resourceGroupName, virtualNetworkGatewayName, peer)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.GatewayRouteListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="peer" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-146">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-146">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-147">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-147">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="cd00c-148">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-148">The name of the virtual network gateway.</span></span>
            </param>
        <param name="peer">
            <span data-ttu-id="cd00c-149">ピアの IP アドレス</span><span class="sxs-lookup"><span data-stu-id="cd00c-149">The IP address of the peer</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-150">この操作は、仮想ネットワーク ゲートウェイが、指定したピアにアドバタイズするルートの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-150">This operation retrieves a list of routes the virtual network gateway is advertising to the specified peer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetAdvertisedRoutesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.GatewayRouteListResult&gt; BeginGetAdvertisedRoutesAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string peer, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.GatewayRouteListResult&gt; BeginGetAdvertisedRoutesAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string peer, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginGetAdvertisedRoutesAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetAdvertisedRoutesAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.GatewayRouteListResult&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginGetAdvertisedRoutesAsync (operations, resourceGroupName, virtualNetworkGatewayName, peer, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;BeginGetAdvertisedRoutesAsync&gt;d__53))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.GatewayRouteListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="peer" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-151">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-151">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-152">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-152">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="cd00c-153">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-153">The name of the virtual network gateway.</span></span>
            </param>
        <param name="peer">
            <span data-ttu-id="cd00c-154">ピアの IP アドレス</span><span class="sxs-lookup"><span data-stu-id="cd00c-154">The IP address of the peer</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cd00c-155">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cd00c-155">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-156">この操作は、仮想ネットワーク ゲートウェイが、指定したピアにアドバタイズするルートの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-156">This operation retrieves a list of routes the virtual network gateway is advertising to the specified peer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetBgpPeerStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.BgpPeerStatusListResult BeginGetBgpPeerStatus (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string peer = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.BgpPeerStatusListResult BeginGetBgpPeerStatus(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string peer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginGetBgpPeerStatus(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginGetBgpPeerStatus (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayName As String, Optional peer As String = null) As BgpPeerStatusListResult" />
      <MemberSignature Language="F#" Value="static member BeginGetBgpPeerStatus : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.BgpPeerStatusListResult" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginGetBgpPeerStatus (operations, resourceGroupName, virtualNetworkGatewayName, peer)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.BgpPeerStatusListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="peer" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-157">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-157">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-158">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-158">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="cd00c-159">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-159">The name of the virtual network gateway.</span></span>
            </param>
        <param name="peer">
            <span data-ttu-id="cd00c-160">状態を取得するピアの IP アドレス。</span><span class="sxs-lookup"><span data-stu-id="cd00c-160">The IP address of the peer to retrieve the status of.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-161">GetBgpPeerStatus 操作では、すべての BGP ピアの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-161">The GetBgpPeerStatus operation retrieves the status of all BGP peers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetBgpPeerStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.BgpPeerStatusListResult&gt; BeginGetBgpPeerStatusAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string peer = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.BgpPeerStatusListResult&gt; BeginGetBgpPeerStatusAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string peer, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginGetBgpPeerStatusAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetBgpPeerStatusAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.BgpPeerStatusListResult&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginGetBgpPeerStatusAsync (operations, resourceGroupName, virtualNetworkGatewayName, peer, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;BeginGetBgpPeerStatusAsync&gt;d__49))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.BgpPeerStatusListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="peer" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-162">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-162">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-163">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-163">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="cd00c-164">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-164">The name of the virtual network gateway.</span></span>
            </param>
        <param name="peer">
            <span data-ttu-id="cd00c-165">状態を取得するピアの IP アドレス。</span><span class="sxs-lookup"><span data-stu-id="cd00c-165">The IP address of the peer to retrieve the status of.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cd00c-166">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cd00c-166">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-167">GetBgpPeerStatus 操作では、すべての BGP ピアの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-167">The GetBgpPeerStatus operation retrieves the status of all BGP peers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetLearnedRoutes">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.GatewayRouteListResult BeginGetLearnedRoutes (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.GatewayRouteListResult BeginGetLearnedRoutes(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginGetLearnedRoutes(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginGetLearnedRoutes (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayName As String) As GatewayRouteListResult" />
      <MemberSignature Language="F#" Value="static member BeginGetLearnedRoutes : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string -&gt; Microsoft.Azure.Management.Network.Models.GatewayRouteListResult" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginGetLearnedRoutes (operations, resourceGroupName, virtualNetworkGatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.GatewayRouteListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-168">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-168">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-169">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-169">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="cd00c-170">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-170">The name of the virtual network gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-171">この操作では、仮想ネットワーク ゲートウェイが学習したルートの一覧を取得は、BGP ピアから学習したルートを含むです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-171">This operation retrieves a list of routes the virtual network gateway has learned, including routes learned from BGP peers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetLearnedRoutesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.GatewayRouteListResult&gt; BeginGetLearnedRoutesAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.GatewayRouteListResult&gt; BeginGetLearnedRoutesAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginGetLearnedRoutesAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetLearnedRoutesAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.GatewayRouteListResult&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginGetLearnedRoutesAsync (operations, resourceGroupName, virtualNetworkGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;BeginGetLearnedRoutesAsync&gt;d__51))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.GatewayRouteListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-172">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-172">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-173">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-173">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="cd00c-174">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-174">The name of the virtual network gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cd00c-175">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cd00c-175">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-176">この操作では、仮想ネットワーク ゲートウェイが学習したルートの一覧を取得は、BGP ピアから学習したルートを含むです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-176">This operation retrieves a list of routes the virtual network gateway has learned, including routes learned from BGP peers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetVpnProfilePackageUrl">
      <MemberSignature Language="C#" Value="public static string BeginGetVpnProfilePackageUrl (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string BeginGetVpnProfilePackageUrl(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginGetVpnProfilePackageUrl(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginGetVpnProfilePackageUrl (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayName As String) As String" />
      <MemberSignature Language="F#" Value="static member BeginGetVpnProfilePackageUrl : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string -&gt; string" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginGetVpnProfilePackageUrl (operations, resourceGroupName, virtualNetworkGatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-177">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-177">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-178">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-178">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="cd00c-179">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-179">The name of the virtual network gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-180">事前生成済みの P2S クライアントは、指定されたリソース グループ内の仮想ネットワーク ゲートウェイの VPN プロファイルの取得。</span><span class="sxs-lookup"><span data-stu-id="cd00c-180">Gets pre-generated VPN profile for P2S client of the virtual network gateway in the specified resource group.</span></span> <span data-ttu-id="cd00c-181">まずを使用して生成する必要があるプロファイル generateVpnProfile です。</span><span class="sxs-lookup"><span data-stu-id="cd00c-181">The profile needs to be generated first using generateVpnProfile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetVpnProfilePackageUrlAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;string&gt; BeginGetVpnProfilePackageUrlAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;string&gt; BeginGetVpnProfilePackageUrlAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginGetVpnProfilePackageUrlAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetVpnProfilePackageUrlAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginGetVpnProfilePackageUrlAsync (operations, resourceGroupName, virtualNetworkGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;BeginGetVpnProfilePackageUrlAsync&gt;d__47))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-182">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-182">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-183">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-183">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="cd00c-184">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-184">The name of the virtual network gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cd00c-185">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cd00c-185">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-186">事前生成済みの P2S クライアントは、指定されたリソース グループ内の仮想ネットワーク ゲートウェイの VPN プロファイルの取得。</span><span class="sxs-lookup"><span data-stu-id="cd00c-186">Gets pre-generated VPN profile for P2S client of the virtual network gateway in the specified resource group.</span></span> <span data-ttu-id="cd00c-187">まずを使用して生成する必要があるプロファイル generateVpnProfile です。</span><span class="sxs-lookup"><span data-stu-id="cd00c-187">The profile needs to be generated first using generateVpnProfile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginReset">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway BeginReset (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string gatewayVip = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway BeginReset(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string gatewayVip) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginReset(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginReset (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayName As String, Optional gatewayVip As String = null) As VirtualNetworkGateway" />
      <MemberSignature Language="F#" Value="static member BeginReset : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginReset (operations, resourceGroupName, virtualNetworkGatewayName, gatewayVip)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="gatewayVip" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-188">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-188">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-189">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-189">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="cd00c-190">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-190">The name of the virtual network gateway.</span></span>
            </param>
        <param name="gatewayVip">
            <span data-ttu-id="cd00c-191">仮想ネットワーク ゲートウェイの vip アドレスがアクティブ/アクティブ機能を有効にしているゲートウェイの開始のリセットを提供します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-191">Virtual network gateway vip address supplied to the begin reset of the active-active feature enabled gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-192">指定されたリソース グループ内の仮想ネットワーク ゲートウェイのプライマリをリセットします。</span><span class="sxs-lookup"><span data-stu-id="cd00c-192">Resets the primary of the virtual network gateway in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginResetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt; BeginResetAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string gatewayVip = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt; BeginResetAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string gatewayVip, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginResetAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginResetAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginResetAsync (operations, resourceGroupName, virtualNetworkGatewayName, gatewayVip, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;BeginResetAsync&gt;d__41))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="gatewayVip" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-193">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-193">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-194">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-194">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="cd00c-195">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-195">The name of the virtual network gateway.</span></span>
            </param>
        <param name="gatewayVip">
            <span data-ttu-id="cd00c-196">仮想ネットワーク ゲートウェイの vip アドレスがアクティブ/アクティブ機能を有効にしているゲートウェイの開始のリセットを提供します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-196">Virtual network gateway vip address supplied to the begin reset of the active-active feature enabled gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cd00c-197">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cd00c-197">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-198">指定されたリソース グループ内の仮想ネットワーク ゲートウェイのプライマリをリセットします。</span><span class="sxs-lookup"><span data-stu-id="cd00c-198">Resets the primary of the virtual network gateway in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateTags">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway BeginUpdateTags (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Models.TagsObject parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway BeginUpdateTags(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginUpdateTags(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdateTags (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayName As String, parameters As TagsObject) As VirtualNetworkGateway" />
      <MemberSignature Language="F#" Value="static member BeginUpdateTags : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject -&gt; Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginUpdateTags (operations, resourceGroupName, virtualNetworkGatewayName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-199">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-199">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-200">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-200">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="cd00c-201">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-201">The name of the virtual network gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="cd00c-202">仮想ネットワーク ゲートウェイのタグを更新する指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="cd00c-202">Parameters supplied to update virtual network gateway tags.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-203">仮想ネットワーク ゲートウェイのタグを更新します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-203">Updates a virtual network gateway tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateTagsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt; BeginUpdateTagsAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Models.TagsObject parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt; BeginUpdateTagsAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginUpdateTagsAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateTagsAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginUpdateTagsAsync (operations, resourceGroupName, virtualNetworkGatewayName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;BeginUpdateTagsAsync&gt;d__39))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-204">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-204">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-205">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-205">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="cd00c-206">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-206">The name of the virtual network gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="cd00c-207">仮想ネットワーク ゲートウェイのタグを更新する指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="cd00c-207">Parameters supplied to update virtual network gateway tags.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cd00c-208">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cd00c-208">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-209">仮想ネットワーク ゲートウェイのタグを更新します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-209">Updates a virtual network gateway tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway CreateOrUpdate (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway CreateOrUpdate(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayName As String, parameters As VirtualNetworkGateway) As VirtualNetworkGateway" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway -&gt; Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, virtualNetworkGatewayName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-210">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-210">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-211">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-211">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="cd00c-212">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-212">The name of the virtual network gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="cd00c-213">作成または更新の各仮想ネットワーク ゲートウェイの操作に渡されるパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-213">Parameters supplied to create or update virtual network gateway operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-214">作成するか、指定されたリソース グループに仮想ネットワーク ゲートウェイを更新します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-214">Creates or updates a virtual network gateway in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, virtualNetworkGatewayName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-215">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-215">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-216">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-216">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="cd00c-217">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-217">The name of the virtual network gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="cd00c-218">作成または更新の各仮想ネットワーク ゲートウェイの操作に渡されるパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-218">Parameters supplied to create or update virtual network gateway operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cd00c-219">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cd00c-219">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-220">作成するか、指定されたリソース グループに仮想ネットワーク ゲートウェイを更新します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-220">Creates or updates a virtual network gateway in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.Delete(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.Delete (operations, resourceGroupName, virtualNetworkGatewayName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-221">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-221">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-222">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-222">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="cd00c-223">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-223">The name of the virtual network gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-224">指定された仮想ネットワーク ゲートウェイを削除します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-224">Deletes the specified virtual network gateway.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.DeleteAsync (operations, resourceGroupName, virtualNetworkGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;DeleteAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-225">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-225">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-226">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-226">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="cd00c-227">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-227">The name of the virtual network gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cd00c-228">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cd00c-228">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-229">指定された仮想ネットワーク ゲートウェイを削除します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-229">Deletes the specified virtual network gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateGatewayVpnProfile">
      <MemberSignature Language="C#" Value="public static string GenerateGatewayVpnProfile (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Models.VpnClientParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GenerateGatewayVpnProfile(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.VpnClientParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GenerateGatewayVpnProfile(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VpnClientParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GenerateGatewayVpnProfile (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayName As String, parameters As VpnClientParameters) As String" />
      <MemberSignature Language="F#" Value="static member GenerateGatewayVpnProfile : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.VpnClientParameters -&gt; string" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GenerateGatewayVpnProfile (operations, resourceGroupName, virtualNetworkGatewayName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VpnClientParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-230">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-230">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-231">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-231">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="cd00c-232">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-232">The name of the virtual network gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="cd00c-233">パラメーターは、VPN クライアント パッケージの操作を生成の仮想ネットワーク ゲートウェイを指定します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-233">Parameters supplied to the generate virtual network gateway VPN client package operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-234">指定されたリソース グループ内の仮想ネットワーク ゲートウェイのクライアントを P2S VPN プロファイルを生成します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-234">Generates VPN profile for P2S client of the virtual network gateway in the specified resource group.</span></span> <span data-ttu-id="cd00c-235">IKEV2 および radius ベースの認証に使用されます。</span><span class="sxs-lookup"><span data-stu-id="cd00c-235">Used for IKEV2 and radius based authentication.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateGatewayVpnProfileAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;string&gt; GenerateGatewayVpnProfileAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Models.VpnClientParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;string&gt; GenerateGatewayVpnProfileAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.VpnClientParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GenerateGatewayVpnProfileAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VpnClientParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GenerateGatewayVpnProfileAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.VpnClientParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GenerateGatewayVpnProfileAsync (operations, resourceGroupName, virtualNetworkGatewayName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;GenerateGatewayVpnProfileAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VpnClientParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-236">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-236">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-237">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-237">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="cd00c-238">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-238">The name of the virtual network gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="cd00c-239">パラメーターは、VPN クライアント パッケージの操作を生成の仮想ネットワーク ゲートウェイを指定します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-239">Parameters supplied to the generate virtual network gateway VPN client package operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cd00c-240">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cd00c-240">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-241">指定されたリソース グループ内の仮想ネットワーク ゲートウェイのクライアントを P2S VPN プロファイルを生成します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-241">Generates VPN profile for P2S client of the virtual network gateway in the specified resource group.</span></span> <span data-ttu-id="cd00c-242">IKEV2 および radius ベースの認証に使用されます。</span><span class="sxs-lookup"><span data-stu-id="cd00c-242">Used for IKEV2 and radius based authentication.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Generatevpnclientpackage">
      <MemberSignature Language="C#" Value="public static string Generatevpnclientpackage (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Models.VpnClientParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string Generatevpnclientpackage(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.VpnClientParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.Generatevpnclientpackage(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VpnClientParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Generatevpnclientpackage (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayName As String, parameters As VpnClientParameters) As String" />
      <MemberSignature Language="F#" Value="static member Generatevpnclientpackage : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.VpnClientParameters -&gt; string" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.Generatevpnclientpackage (operations, resourceGroupName, virtualNetworkGatewayName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VpnClientParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-243">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-243">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-244">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-244">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="cd00c-245">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-245">The name of the virtual network gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="cd00c-246">パラメーターは、VPN クライアント パッケージの操作を生成の仮想ネットワーク ゲートウェイを指定します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-246">Parameters supplied to the generate virtual network gateway VPN client package operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-247">指定されたリソース グループ内の仮想ネットワーク ゲートウェイのクライアントを P2S VPN クライアント パッケージを生成します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-247">Generates VPN client package for P2S client of the virtual network gateway in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GeneratevpnclientpackageAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;string&gt; GeneratevpnclientpackageAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Models.VpnClientParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;string&gt; GeneratevpnclientpackageAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.VpnClientParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GeneratevpnclientpackageAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VpnClientParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GeneratevpnclientpackageAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.VpnClientParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GeneratevpnclientpackageAsync (operations, resourceGroupName, virtualNetworkGatewayName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;GeneratevpnclientpackageAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VpnClientParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-248">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-248">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-249">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-249">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="cd00c-250">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-250">The name of the virtual network gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="cd00c-251">パラメーターは、VPN クライアント パッケージの操作を生成の仮想ネットワーク ゲートウェイを指定します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-251">Parameters supplied to the generate virtual network gateway VPN client package operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cd00c-252">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cd00c-252">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-253">指定されたリソース グループ内の仮想ネットワーク ゲートウェイのクライアントを P2S VPN クライアント パッケージを生成します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-253">Generates VPN client package for P2S client of the virtual network gateway in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateVpnProfile">
      <MemberSignature Language="C#" Value="public static string GenerateVpnProfile (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Models.VpnClientParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GenerateVpnProfile(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.VpnClientParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GenerateVpnProfile(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VpnClientParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GenerateVpnProfile (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayName As String, parameters As VpnClientParameters) As String" />
      <MemberSignature Language="F#" Value="static member GenerateVpnProfile : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.VpnClientParameters -&gt; string" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GenerateVpnProfile (operations, resourceGroupName, virtualNetworkGatewayName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VpnClientParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-254">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-254">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-255">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-255">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="cd00c-256">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-256">The name of the virtual network gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="cd00c-257">パラメーターは、VPN クライアント パッケージの操作を生成の仮想ネットワーク ゲートウェイを指定します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-257">Parameters supplied to the generate virtual network gateway VPN client package operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-258">指定されたリソース グループ内の仮想ネットワーク ゲートウェイのクライアントを P2S VPN プロファイルを生成します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-258">Generates VPN profile for P2S client of the virtual network gateway in the specified resource group.</span></span> <span data-ttu-id="cd00c-259">IKEV2 および radius ベースの認証に使用されます。</span><span class="sxs-lookup"><span data-stu-id="cd00c-259">Used for IKEV2 and radius based authentication.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateVpnProfileAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;string&gt; GenerateVpnProfileAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Models.VpnClientParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;string&gt; GenerateVpnProfileAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.VpnClientParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GenerateVpnProfileAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VpnClientParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GenerateVpnProfileAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.VpnClientParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GenerateVpnProfileAsync (operations, resourceGroupName, virtualNetworkGatewayName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;GenerateVpnProfileAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VpnClientParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-260">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-260">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-261">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-261">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="cd00c-262">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-262">The name of the virtual network gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="cd00c-263">パラメーターは、VPN クライアント パッケージの操作を生成の仮想ネットワーク ゲートウェイを指定します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-263">Parameters supplied to the generate virtual network gateway VPN client package operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cd00c-264">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cd00c-264">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-265">指定されたリソース グループ内の仮想ネットワーク ゲートウェイのクライアントを P2S VPN プロファイルを生成します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-265">Generates VPN profile for P2S client of the virtual network gateway in the specified resource group.</span></span> <span data-ttu-id="cd00c-266">IKEV2 および radius ベースの認証に使用されます。</span><span class="sxs-lookup"><span data-stu-id="cd00c-266">Used for IKEV2 and radius based authentication.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway Get (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway Get(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.Get(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayName As String) As VirtualNetworkGateway" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string -&gt; Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.Get (operations, resourceGroupName, virtualNetworkGatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-267">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-267">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-268">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-268">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="cd00c-269">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-269">The name of the virtual network gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-270">リソース グループによって指定された仮想ネットワーク ゲートウェイを取得します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-270">Gets the specified virtual network gateway by resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAdvertisedRoutes">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.GatewayRouteListResult GetAdvertisedRoutes (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string peer);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.GatewayRouteListResult GetAdvertisedRoutes(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string peer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GetAdvertisedRoutes(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAdvertisedRoutes (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayName As String, peer As String) As GatewayRouteListResult" />
      <MemberSignature Language="F#" Value="static member GetAdvertisedRoutes : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.GatewayRouteListResult" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GetAdvertisedRoutes (operations, resourceGroupName, virtualNetworkGatewayName, peer)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.GatewayRouteListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="peer" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-271">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-271">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-272">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-272">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="cd00c-273">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-273">The name of the virtual network gateway.</span></span>
            </param>
        <param name="peer">
            <span data-ttu-id="cd00c-274">ピアの IP アドレス</span><span class="sxs-lookup"><span data-stu-id="cd00c-274">The IP address of the peer</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-275">この操作は、仮想ネットワーク ゲートウェイが、指定したピアにアドバタイズするルートの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-275">This operation retrieves a list of routes the virtual network gateway is advertising to the specified peer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAdvertisedRoutesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.GatewayRouteListResult&gt; GetAdvertisedRoutesAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string peer, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.GatewayRouteListResult&gt; GetAdvertisedRoutesAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string peer, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GetAdvertisedRoutesAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAdvertisedRoutesAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.GatewayRouteListResult&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GetAdvertisedRoutesAsync (operations, resourceGroupName, virtualNetworkGatewayName, peer, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;GetAdvertisedRoutesAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.GatewayRouteListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="peer" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-276">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-276">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-277">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-277">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="cd00c-278">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-278">The name of the virtual network gateway.</span></span>
            </param>
        <param name="peer">
            <span data-ttu-id="cd00c-279">ピアの IP アドレス</span><span class="sxs-lookup"><span data-stu-id="cd00c-279">The IP address of the peer</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cd00c-280">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cd00c-280">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-281">この操作は、仮想ネットワーク ゲートウェイが、指定したピアにアドバタイズするルートの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-281">This operation retrieves a list of routes the virtual network gateway is advertising to the specified peer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt; GetAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt; GetAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GetAsync (operations, resourceGroupName, virtualNetworkGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-282">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-282">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-283">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-283">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="cd00c-284">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-284">The name of the virtual network gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cd00c-285">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cd00c-285">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-286">リソース グループによって指定された仮想ネットワーク ゲートウェイを取得します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-286">Gets the specified virtual network gateway by resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBgpPeerStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.BgpPeerStatusListResult GetBgpPeerStatus (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string peer = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.BgpPeerStatusListResult GetBgpPeerStatus(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string peer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GetBgpPeerStatus(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetBgpPeerStatus (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayName As String, Optional peer As String = null) As BgpPeerStatusListResult" />
      <MemberSignature Language="F#" Value="static member GetBgpPeerStatus : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.BgpPeerStatusListResult" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GetBgpPeerStatus (operations, resourceGroupName, virtualNetworkGatewayName, peer)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.BgpPeerStatusListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="peer" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-287">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-287">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-288">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-288">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="cd00c-289">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-289">The name of the virtual network gateway.</span></span>
            </param>
        <param name="peer">
            <span data-ttu-id="cd00c-290">状態を取得するピアの IP アドレス。</span><span class="sxs-lookup"><span data-stu-id="cd00c-290">The IP address of the peer to retrieve the status of.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-291">GetBgpPeerStatus 操作では、すべての BGP ピアの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-291">The GetBgpPeerStatus operation retrieves the status of all BGP peers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBgpPeerStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.BgpPeerStatusListResult&gt; GetBgpPeerStatusAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string peer = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.BgpPeerStatusListResult&gt; GetBgpPeerStatusAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string peer, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GetBgpPeerStatusAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetBgpPeerStatusAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.BgpPeerStatusListResult&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GetBgpPeerStatusAsync (operations, resourceGroupName, virtualNetworkGatewayName, peer, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;GetBgpPeerStatusAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.BgpPeerStatusListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="peer" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-292">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-292">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-293">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-293">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="cd00c-294">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-294">The name of the virtual network gateway.</span></span>
            </param>
        <param name="peer">
            <span data-ttu-id="cd00c-295">状態を取得するピアの IP アドレス。</span><span class="sxs-lookup"><span data-stu-id="cd00c-295">The IP address of the peer to retrieve the status of.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cd00c-296">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cd00c-296">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-297">GetBgpPeerStatus 操作では、すべての BGP ピアの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-297">The GetBgpPeerStatus operation retrieves the status of all BGP peers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetGatewayVpnProfile">
      <MemberSignature Language="C#" Value="public static string GetGatewayVpnProfile (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetGatewayVpnProfile(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GetGatewayVpnProfile(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetGatewayVpnProfile (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayName As String) As String" />
      <MemberSignature Language="F#" Value="static member GetGatewayVpnProfile : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string -&gt; string" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GetGatewayVpnProfile (operations, resourceGroupName, virtualNetworkGatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-298">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-298">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-299">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-299">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="cd00c-300">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-300">The name of the virtual network gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-301">事前生成済みの P2S クライアントは、指定されたリソース グループ内の仮想ネットワーク ゲートウェイの VPN プロファイルの取得。</span><span class="sxs-lookup"><span data-stu-id="cd00c-301">Gets pre-generated VPN profile for P2S client of the virtual network gateway in the specified resource group.</span></span> <span data-ttu-id="cd00c-302">まずを使用して生成する必要があるプロファイル generateVpnProfile です。</span><span class="sxs-lookup"><span data-stu-id="cd00c-302">The profile needs to be generated first using generateVpnProfile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetGatewayVpnProfileAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;string&gt; GetGatewayVpnProfileAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;string&gt; GetGatewayVpnProfileAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GetGatewayVpnProfileAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetGatewayVpnProfileAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GetGatewayVpnProfileAsync (operations, resourceGroupName, virtualNetworkGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;GetGatewayVpnProfileAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-303">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-303">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-304">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-304">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="cd00c-305">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-305">The name of the virtual network gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cd00c-306">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cd00c-306">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-307">事前生成済みの P2S クライアントは、指定されたリソース グループ内の仮想ネットワーク ゲートウェイの VPN プロファイルの取得。</span><span class="sxs-lookup"><span data-stu-id="cd00c-307">Gets pre-generated VPN profile for P2S client of the virtual network gateway in the specified resource group.</span></span> <span data-ttu-id="cd00c-308">まずを使用して生成する必要があるプロファイル generateVpnProfile です。</span><span class="sxs-lookup"><span data-stu-id="cd00c-308">The profile needs to be generated first using generateVpnProfile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLearnedRoutes">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.GatewayRouteListResult GetLearnedRoutes (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.GatewayRouteListResult GetLearnedRoutes(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GetLearnedRoutes(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetLearnedRoutes (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayName As String) As GatewayRouteListResult" />
      <MemberSignature Language="F#" Value="static member GetLearnedRoutes : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string -&gt; Microsoft.Azure.Management.Network.Models.GatewayRouteListResult" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GetLearnedRoutes (operations, resourceGroupName, virtualNetworkGatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.GatewayRouteListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-309">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-309">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-310">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-310">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="cd00c-311">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-311">The name of the virtual network gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-312">この操作では、仮想ネットワーク ゲートウェイが学習したルートの一覧を取得は、BGP ピアから学習したルートを含むです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-312">This operation retrieves a list of routes the virtual network gateway has learned, including routes learned from BGP peers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLearnedRoutesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.GatewayRouteListResult&gt; GetLearnedRoutesAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.GatewayRouteListResult&gt; GetLearnedRoutesAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GetLearnedRoutesAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetLearnedRoutesAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.GatewayRouteListResult&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GetLearnedRoutesAsync (operations, resourceGroupName, virtualNetworkGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;GetLearnedRoutesAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.GatewayRouteListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-313">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-313">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-314">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-314">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="cd00c-315">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-315">The name of the virtual network gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cd00c-316">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cd00c-316">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-317">この操作では、仮想ネットワーク ゲートウェイが学習したルートの一覧を取得は、BGP ピアから学習したルートを含むです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-317">This operation retrieves a list of routes the virtual network gateway has learned, including routes learned from BGP peers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVpnProfilePackageUrl">
      <MemberSignature Language="C#" Value="public static string GetVpnProfilePackageUrl (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetVpnProfilePackageUrl(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GetVpnProfilePackageUrl(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetVpnProfilePackageUrl (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayName As String) As String" />
      <MemberSignature Language="F#" Value="static member GetVpnProfilePackageUrl : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string -&gt; string" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GetVpnProfilePackageUrl (operations, resourceGroupName, virtualNetworkGatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-318">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-318">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-319">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-319">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="cd00c-320">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-320">The name of the virtual network gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-321">事前生成済みの P2S クライアントは、指定されたリソース グループ内の仮想ネットワーク ゲートウェイの VPN プロファイルの取得。</span><span class="sxs-lookup"><span data-stu-id="cd00c-321">Gets pre-generated VPN profile for P2S client of the virtual network gateway in the specified resource group.</span></span> <span data-ttu-id="cd00c-322">まずを使用して生成する必要があるプロファイル generateVpnProfile です。</span><span class="sxs-lookup"><span data-stu-id="cd00c-322">The profile needs to be generated first using generateVpnProfile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVpnProfilePackageUrlAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;string&gt; GetVpnProfilePackageUrlAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;string&gt; GetVpnProfilePackageUrlAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GetVpnProfilePackageUrlAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetVpnProfilePackageUrlAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GetVpnProfilePackageUrlAsync (operations, resourceGroupName, virtualNetworkGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;GetVpnProfilePackageUrlAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-323">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-323">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-324">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-324">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="cd00c-325">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-325">The name of the virtual network gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cd00c-326">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cd00c-326">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-327">事前生成済みの P2S クライアントは、指定されたリソース グループ内の仮想ネットワーク ゲートウェイの VPN プロファイルの取得。</span><span class="sxs-lookup"><span data-stu-id="cd00c-327">Gets pre-generated VPN profile for P2S client of the virtual network gateway in the specified resource group.</span></span> <span data-ttu-id="cd00c-328">まずを使用して生成する必要があるプロファイル generateVpnProfile です。</span><span class="sxs-lookup"><span data-stu-id="cd00c-328">The profile needs to be generated first using generateVpnProfile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt; List (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt; List(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.List(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String) As IPage(Of VirtualNetworkGateway)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.List (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-329">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-329">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-330">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-330">The name of the resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-331">リソース グループによってすべての仮想ネットワーク ゲートウェイを取得します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-331">Gets all virtual network gateways by resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.ListAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;ListAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-332">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-332">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-333">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-333">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cd00c-334">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cd00c-334">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-335">リソース グループによってすべての仮想ネットワーク ゲートウェイを取得します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-335">Gets all virtual network gateways by resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListConnections">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity&gt; ListConnections (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity&gt; ListConnections(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.ListConnections(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListConnections (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayName As String) As IPage(Of VirtualNetworkGatewayConnectionListEntity)" />
      <MemberSignature Language="F#" Value="static member ListConnections : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.ListConnections (operations, resourceGroupName, virtualNetworkGatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-336">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-336">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-337">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-337">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="cd00c-338">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-338">The name of the virtual network gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-339">仮想ネットワーク ゲートウェイ内のすべての接続を取得します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-339">Gets all the connections in a virtual network gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListConnectionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity&gt;&gt; ListConnectionsAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity&gt;&gt; ListConnectionsAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.ListConnectionsAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListConnectionsAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity&gt;&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.ListConnectionsAsync (operations, resourceGroupName, virtualNetworkGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;ListConnectionsAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-340">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-340">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-341">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-341">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="cd00c-342">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-342">The name of the virtual network gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cd00c-343">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cd00c-343">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-344">仮想ネットワーク ゲートウェイ内のすべての接続を取得します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-344">Gets all the connections in a virtual network gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListConnectionsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity&gt; ListConnectionsNext (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity&gt; ListConnectionsNext(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.ListConnectionsNext(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListConnectionsNext (operations As IVirtualNetworkGatewaysOperations, nextPageLink As String) As IPage(Of VirtualNetworkGatewayConnectionListEntity)" />
      <MemberSignature Language="F#" Value="static member ListConnectionsNext : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.ListConnectionsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-345">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-345">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="cd00c-346">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="cd00c-346">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-347">仮想ネットワーク ゲートウェイ内のすべての接続を取得します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-347">Gets all the connections in a virtual network gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListConnectionsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity&gt;&gt; ListConnectionsNextAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity&gt;&gt; ListConnectionsNextAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.ListConnectionsNextAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListConnectionsNextAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity&gt;&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.ListConnectionsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;ListConnectionsNextAsync&gt;d__57))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-348">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-348">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="cd00c-349">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="cd00c-349">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cd00c-350">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cd00c-350">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-351">仮想ネットワーク ゲートウェイ内のすべての接続を取得します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-351">Gets all the connections in a virtual network gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt; ListNext (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt; ListNext(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.ListNext(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IVirtualNetworkGatewaysOperations, nextPageLink As String) As IPage(Of VirtualNetworkGateway)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-352">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-352">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="cd00c-353">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="cd00c-353">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-354">リソース グループによってすべての仮想ネットワーク ゲートウェイを取得します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-354">Gets all virtual network gateways by resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;ListNextAsync&gt;d__55))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-355">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-355">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="cd00c-356">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="cd00c-356">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cd00c-357">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cd00c-357">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-358">リソース グループによってすべての仮想ネットワーク ゲートウェイを取得します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-358">Gets all virtual network gateways by resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Reset">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway Reset (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string gatewayVip = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway Reset(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string gatewayVip) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.Reset(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Reset (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayName As String, Optional gatewayVip As String = null) As VirtualNetworkGateway" />
      <MemberSignature Language="F#" Value="static member Reset : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.Reset (operations, resourceGroupName, virtualNetworkGatewayName, gatewayVip)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="gatewayVip" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-359">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-359">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-360">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-360">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="cd00c-361">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-361">The name of the virtual network gateway.</span></span>
            </param>
        <param name="gatewayVip">
            <span data-ttu-id="cd00c-362">仮想ネットワーク ゲートウェイの vip アドレスがアクティブ/アクティブ機能を有効にしているゲートウェイの開始のリセットを提供します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-362">Virtual network gateway vip address supplied to the begin reset of the active-active feature enabled gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-363">指定されたリソース グループ内の仮想ネットワーク ゲートウェイのプライマリをリセットします。</span><span class="sxs-lookup"><span data-stu-id="cd00c-363">Resets the primary of the virtual network gateway in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt; ResetAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string gatewayVip = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt; ResetAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string gatewayVip, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.ResetAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ResetAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.ResetAsync (operations, resourceGroupName, virtualNetworkGatewayName, gatewayVip, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;ResetAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="gatewayVip" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-364">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-364">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-365">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-365">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="cd00c-366">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-366">The name of the virtual network gateway.</span></span>
            </param>
        <param name="gatewayVip">
            <span data-ttu-id="cd00c-367">仮想ネットワーク ゲートウェイの vip アドレスがアクティブ/アクティブ機能を有効にしているゲートウェイの開始のリセットを提供します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-367">Virtual network gateway vip address supplied to the begin reset of the active-active feature enabled gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cd00c-368">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cd00c-368">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-369">指定されたリソース グループ内の仮想ネットワーク ゲートウェイのプライマリをリセットします。</span><span class="sxs-lookup"><span data-stu-id="cd00c-369">Resets the primary of the virtual network gateway in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportedVpnDevices">
      <MemberSignature Language="C#" Value="public static string SupportedVpnDevices (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string SupportedVpnDevices(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.SupportedVpnDevices(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SupportedVpnDevices (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayName As String) As String" />
      <MemberSignature Language="F#" Value="static member SupportedVpnDevices : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string -&gt; string" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.SupportedVpnDevices (operations, resourceGroupName, virtualNetworkGatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-370">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-370">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-371">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-371">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="cd00c-372">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-372">The name of the virtual network gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-373">サポートされている vpn デバイスの xml 形式の表記を取得します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-373">Gets a xml format representation for supported vpn devices.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportedVpnDevicesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;string&gt; SupportedVpnDevicesAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;string&gt; SupportedVpnDevicesAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.SupportedVpnDevicesAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SupportedVpnDevicesAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.SupportedVpnDevicesAsync (operations, resourceGroupName, virtualNetworkGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;SupportedVpnDevicesAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-374">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-374">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-375">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-375">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="cd00c-376">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-376">The name of the virtual network gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cd00c-377">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cd00c-377">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-378">サポートされている vpn デバイスの xml 形式の表記を取得します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-378">Gets a xml format representation for supported vpn devices.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTags">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway UpdateTags (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Models.TagsObject parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway UpdateTags(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.UpdateTags(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpdateTags (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayName As String, parameters As TagsObject) As VirtualNetworkGateway" />
      <MemberSignature Language="F#" Value="static member UpdateTags : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject -&gt; Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.UpdateTags (operations, resourceGroupName, virtualNetworkGatewayName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-379">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-379">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-380">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-380">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="cd00c-381">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-381">The name of the virtual network gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="cd00c-382">仮想ネットワーク ゲートウェイのタグを更新する指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="cd00c-382">Parameters supplied to update virtual network gateway tags.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-383">仮想ネットワーク ゲートウェイのタグを更新します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-383">Updates a virtual network gateway tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTagsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt; UpdateTagsAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Models.TagsObject parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt; UpdateTagsAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.UpdateTagsAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateTagsAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.UpdateTagsAsync (operations, resourceGroupName, virtualNetworkGatewayName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;UpdateTagsAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-384">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-384">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-385">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-385">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="cd00c-386">仮想ネットワーク ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-386">The name of the virtual network gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="cd00c-387">仮想ネットワーク ゲートウェイのタグを更新する指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="cd00c-387">Parameters supplied to update virtual network gateway tags.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cd00c-388">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cd00c-388">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-389">仮想ネットワーク ゲートウェイのタグを更新します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-389">Updates a virtual network gateway tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VpnDeviceConfigurationScript">
      <MemberSignature Language="C#" Value="public static string VpnDeviceConfigurationScript (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, Microsoft.Azure.Management.Network.Models.VpnDeviceScriptParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string VpnDeviceConfigurationScript(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, class Microsoft.Azure.Management.Network.Models.VpnDeviceScriptParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.VpnDeviceConfigurationScript(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VpnDeviceScriptParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function VpnDeviceConfigurationScript (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayConnectionName As String, parameters As VpnDeviceScriptParameters) As String" />
      <MemberSignature Language="F#" Value="static member VpnDeviceConfigurationScript : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.VpnDeviceScriptParameters -&gt; string" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.VpnDeviceConfigurationScript (operations, resourceGroupName, virtualNetworkGatewayConnectionName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VpnDeviceScriptParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-390">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-390">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-391">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-391">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            <span data-ttu-id="cd00c-392">構成スクリプトを生成する仮想ネットワーク ゲートウェイの接続の名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-392">The name of the virtual network gateway connection for which the configuration script is generated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="cd00c-393">Generate vpn デバイス スクリプトの操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="cd00c-393">Parameters supplied to the generate vpn device script operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-394">Vpn デバイス構成スクリプトの xml 形式の表記を取得します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-394">Gets a xml format representation for vpn device configuration script.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VpnDeviceConfigurationScriptAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;string&gt; VpnDeviceConfigurationScriptAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, Microsoft.Azure.Management.Network.Models.VpnDeviceScriptParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;string&gt; VpnDeviceConfigurationScriptAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, class Microsoft.Azure.Management.Network.Models.VpnDeviceScriptParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.VpnDeviceConfigurationScriptAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VpnDeviceScriptParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member VpnDeviceConfigurationScriptAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.VpnDeviceScriptParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.VpnDeviceConfigurationScriptAsync (operations, resourceGroupName, virtualNetworkGatewayConnectionName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;VpnDeviceConfigurationScriptAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VpnDeviceScriptParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd00c-395">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cd00c-395">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd00c-396">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-396">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            <span data-ttu-id="cd00c-397">構成スクリプトを生成する仮想ネットワーク ゲートウェイの接続の名前。</span><span class="sxs-lookup"><span data-stu-id="cd00c-397">The name of the virtual network gateway connection for which the configuration script is generated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="cd00c-398">Generate vpn デバイス スクリプトの操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="cd00c-398">Parameters supplied to the generate vpn device script operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cd00c-399">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cd00c-399">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd00c-400">Vpn デバイス構成スクリプトの xml 形式の表記を取得します。</span><span class="sxs-lookup"><span data-stu-id="cd00c-400">Gets a xml format representation for vpn device configuration script.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>