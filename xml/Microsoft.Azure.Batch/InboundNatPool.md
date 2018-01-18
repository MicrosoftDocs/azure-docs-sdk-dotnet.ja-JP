<Type Name="InboundNatPool" FullName="Microsoft.Azure.Batch.InboundNatPool">
  <TypeSignature Language="C#" Value="public class InboundNatPool" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit InboundNatPool extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.InboundNatPool" />
  <TypeSignature Language="VB.NET" Value="Public Class InboundNatPool" />
  <TypeSignature Language="F#" Value="type InboundNatPool = class&#xA;    interface ITransportObjectProvider&lt;InboundNATPool&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="4c3d3-101">着信 NAT プールでアドレスを特定のポートを使用できる Batch プールを外部からのノードを計算します。</span><span class="sxs-lookup"><span data-stu-id="4c3d3-101">A inbound NAT pool that can be used to address specific ports on compute nodes in a Batch pool externally.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public InboundNatPool (string name, Microsoft.Azure.Batch.Common.InboundEndpointProtocol protocol, int backendPort, int frontendPortRangeStart, int frontendPortRangeEnd, System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.NetworkSecurityGroupRule&gt; networkSecurityGroupRules = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype Microsoft.Azure.Batch.Common.InboundEndpointProtocol protocol, int32 backendPort, int32 frontendPortRangeStart, int32 frontendPortRangeEnd, class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Batch.NetworkSecurityGroupRule&gt; networkSecurityGroupRules) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.InboundNatPool.#ctor(System.String,Microsoft.Azure.Batch.Common.InboundEndpointProtocol,System.Int32,System.Int32,System.Int32,System.Collections.Generic.IReadOnlyList{Microsoft.Azure.Batch.NetworkSecurityGroupRule})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, protocol As InboundEndpointProtocol, backendPort As Integer, frontendPortRangeStart As Integer, frontendPortRangeEnd As Integer, Optional networkSecurityGroupRules As IReadOnlyList(Of NetworkSecurityGroupRule) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.InboundNatPool : string * Microsoft.Azure.Batch.Common.InboundEndpointProtocol * int * int * int * System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.NetworkSecurityGroupRule&gt; -&gt; Microsoft.Azure.Batch.InboundNatPool" Usage="new Microsoft.Azure.Batch.InboundNatPool (name, protocol, backendPort, frontendPortRangeStart, frontendPortRangeEnd, networkSecurityGroupRules)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="protocol" Type="Microsoft.Azure.Batch.Common.InboundEndpointProtocol" />
        <Parameter Name="backendPort" Type="System.Int32" />
        <Parameter Name="frontendPortRangeStart" Type="System.Int32" />
        <Parameter Name="frontendPortRangeEnd" Type="System.Int32" />
        <Parameter Name="networkSecurityGroupRules" Type="System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.NetworkSecurityGroupRule&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="4c3d3-102">エンドポイントの名前。</span><span class="sxs-lookup"><span data-stu-id="4c3d3-102">The name of the endpoint.</span></span></param>
        <param name="protocol"><span data-ttu-id="4c3d3-103">エンドポイントのプロトコルです。</span><span class="sxs-lookup"><span data-stu-id="4c3d3-103">The protocol of the endpoint.</span></span></param>
        <param name="backendPort"><span data-ttu-id="4c3d3-104">コンピューティング ノード上のポート番号。</span><span class="sxs-lookup"><span data-stu-id="4c3d3-104">The port number on the compute node.</span></span></param>
        <param name="frontendPortRangeStart"><span data-ttu-id="4c3d3-105">個々 のコンピューティング ノードで、backendPort への着信アクセスを提供するために使用する外部ポートの範囲の最初のポート番号。</span><span class="sxs-lookup"><span data-stu-id="4c3d3-105">The first port number in the range of external ports that will be used to provide inbound access to the backendPort on individual compute nodes.</span></span></param>
        <param name="frontendPortRangeEnd"><span data-ttu-id="4c3d3-106">個々 のコンピューティング ノードで、backendPort への着信アクセスを提供するために使用する外部ポートの範囲の最後のポート番号。</span><span class="sxs-lookup"><span data-stu-id="4c3d3-106">The last port number in the range of external ports that will be used to provide inbound access to the backendPort on individual compute nodes.</span></span></param>
        <param name="networkSecurityGroupRules"><span data-ttu-id="4c3d3-107">エンドポイントに適用されるネットワーク セキュリティ グループ ルールの一覧。</span><span class="sxs-lookup"><span data-stu-id="4c3d3-107">A list of network security group rules that will be applied to the endpoint.</span></span></param>
        <summary>
            <span data-ttu-id="4c3d3-108"><see cref="T:Microsoft.Azure.Batch.InboundNatPool" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4c3d3-108">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.InboundNatPool" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackendPort">
      <MemberSignature Language="C#" Value="public int BackendPort { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 BackendPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.InboundNatPool.BackendPort" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackendPort As Integer" />
      <MemberSignature Language="F#" Value="member this.BackendPort : int" Usage="Microsoft.Azure.Batch.InboundNatPool.BackendPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4c3d3-109">コンピューティング ノードで、ポート番号を取得します。</span><span class="sxs-lookup"><span data-stu-id="4c3d3-109">Gets the port number on the compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="4c3d3-110">これは、Batch プール内で一意でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="4c3d3-110">This must be unique within a Batch pool.</span></span> <span data-ttu-id="4c3d3-111">指定できる値は 1 ~ 65535 の間は点を除いて 22、3389、29876 および 29877 についてこれらは予約されています。</span><span class="sxs-lookup"><span data-stu-id="4c3d3-111">Acceptable values are between 1 and 65535 except for 22, 3389, 29876 and 29877 as these are reserved.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="FrontendPortRangeEnd">
      <MemberSignature Language="C#" Value="public int FrontendPortRangeEnd { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 FrontendPortRangeEnd" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.InboundNatPool.FrontendPortRangeEnd" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FrontendPortRangeEnd As Integer" />
      <MemberSignature Language="F#" Value="member this.FrontendPortRangeEnd : int" Usage="Microsoft.Azure.Batch.InboundNatPool.FrontendPortRangeEnd" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4c3d3-112">個々 のコンピューティング ノードで、backendPort への着信アクセスを提供するために使用する外部ポートの範囲の最後のポート番号を取得します。</span><span class="sxs-lookup"><span data-stu-id="4c3d3-112">Gets the last port number in the range of external ports that will be used to provide inbound access to the backendPort on individual compute nodes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="4c3d3-113">1 ~ 65534、Batch service によって予約されている 55000 50000 からポート以外で使用可能な値の範囲です。</span><span class="sxs-lookup"><span data-stu-id="4c3d3-113">Acceptable values range between 1 and 65534 except ports from 50000 to 55000 which are reserved by the Batch service.</span></span> <span data-ttu-id="4c3d3-114">プール内のすべての範囲は、異なる必要があり、重ねることはできません。</span><span class="sxs-lookup"><span data-stu-id="4c3d3-114">All ranges within a pool must be distinct and cannot overlap.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="FrontendPortRangeStart">
      <MemberSignature Language="C#" Value="public int FrontendPortRangeStart { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 FrontendPortRangeStart" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.InboundNatPool.FrontendPortRangeStart" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FrontendPortRangeStart As Integer" />
      <MemberSignature Language="F#" Value="member this.FrontendPortRangeStart : int" Usage="Microsoft.Azure.Batch.InboundNatPool.FrontendPortRangeStart" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4c3d3-115">個々 のコンピューティング ノードで、backendPort への着信アクセスを提供するために使用する外部ポートの範囲内の最初のポート番号を取得します。</span><span class="sxs-lookup"><span data-stu-id="4c3d3-115">Gets the first port number in the range of external ports that will be used to provide inbound access to the backendPort on individual compute nodes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="4c3d3-116">1 ~ 65534 に予約されている 55000 50000 からポート以外で使用可能な値の範囲です。</span><span class="sxs-lookup"><span data-stu-id="4c3d3-116">Acceptable values range between 1 and 65534 except ports from 50000 to 55000 which are reserved.</span></span> <span data-ttu-id="4c3d3-117">プール内のすべての範囲は、異なる必要があり、重ねることはできません。</span><span class="sxs-lookup"><span data-stu-id="4c3d3-117">All ranges within a pool must be distinct and cannot overlap.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.InboundNatPool.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Batch.InboundNatPool.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4c3d3-118">エンドポイントの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="4c3d3-118">Gets the name of the endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="4c3d3-119">名前は、Batch プール内で一意である必要があります、文字、数字、アンダー スコア、ピリオド、およびハイフンを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="4c3d3-119">The name must be unique within a Batch pool, can contain letters, numbers, underscores, periods, and hyphens.</span></span> <span data-ttu-id="4c3d3-120">名の先頭文字はや数、文字、数字、またはアンダー スコアで終わる必要があります 77 文字を超えることはできません。</span><span class="sxs-lookup"><span data-stu-id="4c3d3-120">Names must start with a letter or number, must end with a letter, number, or underscore, and cannot exceed 77 characters.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkSecurityGroupRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.NetworkSecurityGroupRule&gt; NetworkSecurityGroupRules { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Batch.NetworkSecurityGroupRule&gt; NetworkSecurityGroupRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.InboundNatPool.NetworkSecurityGroupRules" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NetworkSecurityGroupRules As IReadOnlyList(Of NetworkSecurityGroupRule)" />
      <MemberSignature Language="F#" Value="member this.NetworkSecurityGroupRules : System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.NetworkSecurityGroupRule&gt;" Usage="Microsoft.Azure.Batch.InboundNatPool.NetworkSecurityGroupRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.NetworkSecurityGroupRule&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4c3d3-121">エンドポイントに適用されるグループの規則のネットワーク セキュリティの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="4c3d3-121">Gets a list of network security group rules that will be applied to the endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="4c3d3-122">プールのすべてのエンドポイント間で指定できるルールの最大数は 25 です。</span><span class="sxs-lookup"><span data-stu-id="4c3d3-122">The maximum number of rules that can be specified across all the endpoints on a pool is 25.</span></span> <span data-ttu-id="4c3d3-123">ネットワーク セキュリティ グループの規則が指定されていない場合は、指定 backendPort への着信アクセスを許可する既定のルールが作成されます。</span><span class="sxs-lookup"><span data-stu-id="4c3d3-123">If no network security group rules are specified, a default rule will be created to allow inbound access to the specified backendPort.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Protocol">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Common.InboundEndpointProtocol Protocol { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Batch.Common.InboundEndpointProtocol Protocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.InboundNatPool.Protocol" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Protocol As InboundEndpointProtocol" />
      <MemberSignature Language="F#" Value="member this.Protocol : Microsoft.Azure.Batch.Common.InboundEndpointProtocol" Usage="Microsoft.Azure.Batch.InboundNatPool.Protocol" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.InboundEndpointProtocol</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4c3d3-124">エンドポイントのプロトコルを取得します。</span><span class="sxs-lookup"><span data-stu-id="4c3d3-124">Gets the protocol of the endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>