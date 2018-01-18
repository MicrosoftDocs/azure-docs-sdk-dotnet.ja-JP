<Type Name="NetworkConfiguration" FullName="Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration">
  <TypeSignature Language="C#" Value="public class NetworkConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NetworkConfiguration extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class NetworkConfiguration" />
  <TypeSignature Language="F#" Value="type NetworkConfiguration = class" />
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
            <span data-ttu-id="99f47-101">プールのネットワーク構成にします。</span><span class="sxs-lookup"><span data-stu-id="99f47-101">The network configuration for a pool.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="99f47-102">NetworkConfiguration クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="99f47-102">Initializes a new instance of the NetworkConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkConfiguration (string subnetId = null, Microsoft.Azure.Batch.Protocol.Models.PoolEndpointConfiguration endpointConfiguration = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string subnetId, class Microsoft.Azure.Batch.Protocol.Models.PoolEndpointConfiguration endpointConfiguration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration.#ctor(System.String,Microsoft.Azure.Batch.Protocol.Models.PoolEndpointConfiguration)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional subnetId As String = null, Optional endpointConfiguration As PoolEndpointConfiguration = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration : string * Microsoft.Azure.Batch.Protocol.Models.PoolEndpointConfiguration -&gt; Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration" Usage="new Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration (subnetId, endpointConfiguration)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="subnetId" Type="System.String" />
        <Parameter Name="endpointConfiguration" Type="Microsoft.Azure.Batch.Protocol.Models.PoolEndpointConfiguration" />
      </Parameters>
      <Docs>
        <param name="subnetId"><span data-ttu-id="99f47-103">プールのコンピューティング ノードを参加させる、仮想ネットワーク サブネットの ARM リソース識別子。</span><span class="sxs-lookup"><span data-stu-id="99f47-103">The ARM resource identifier of the virtual network subnet which the compute nodes of the pool will join.</span></span> <span data-ttu-id="99f47-104">これは、フォーム/subscriptions/{サブスクリプション} {グループ} 必要な/providers/{プロバイダー}/virtualNetworks/{ネットワーク}/subnets/{サブネット} です。</span><span class="sxs-lookup"><span data-stu-id="99f47-104">This is of the form /subscriptions/{subscription}/resourceGroups/{group}/providers/{provider}/virtualNetworks/{network}/subnets/{subnet}.</span></span></param>
        <param name="endpointConfiguration"><span data-ttu-id="99f47-105">上のエンドポイントの構成は、Batch プール内のノードを計算します。</span><span class="sxs-lookup"><span data-stu-id="99f47-105">The configuration for endpoints on compute nodes in the Batch pool.</span></span></param>
        <summary>
            <span data-ttu-id="99f47-106">NetworkConfiguration クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="99f47-106">Initializes a new instance of the NetworkConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndpointConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.PoolEndpointConfiguration EndpointConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.PoolEndpointConfiguration EndpointConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration.EndpointConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property EndpointConfiguration As PoolEndpointConfiguration" />
      <MemberSignature Language="F#" Value="member this.EndpointConfiguration : Microsoft.Azure.Batch.Protocol.Models.PoolEndpointConfiguration with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration.EndpointConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="endpointConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.PoolEndpointConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="99f47-107">取得または Batch プール内の計算ノードのエンドポイントの構成を設定します。</span><span class="sxs-lookup"><span data-stu-id="99f47-107">Gets or sets the configuration for endpoints on compute nodes in the Batch pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="99f47-108">プールのエンドポイント構成は、virtualMachineConfiguration プロパティを使用してプールでのみサポートされます。</span><span class="sxs-lookup"><span data-stu-id="99f47-108">Pool endpoint configuration is only supported on pools with the virtualMachineConfiguration property.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SubnetId">
      <MemberSignature Language="C#" Value="public string SubnetId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubnetId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration.SubnetId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubnetId As String" />
      <MemberSignature Language="F#" Value="member this.SubnetId : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration.SubnetId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="subnetId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="99f47-109">取得またはプールのコンピューティング ノードを参加させる、仮想ネットワーク サブネットの ARM リソース識別子を設定します。</span><span class="sxs-lookup"><span data-stu-id="99f47-109">Gets or sets the ARM resource identifier of the virtual network subnet which the compute nodes of the pool will join.</span></span> <span data-ttu-id="99f47-110">これは、フォーム/subscriptions/{サブスクリプション} {グループ} 必要な/providers/{プロバイダー}/virtualNetworks/{ネットワーク}/subnets/{サブネット} です。</span><span class="sxs-lookup"><span data-stu-id="99f47-110">This is of the form /subscriptions/{subscription}/resourceGroups/{group}/providers/{provider}/virtualNetworks/{network}/subnets/{subnet}.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="99f47-111">仮想ネットワークは、同じリージョンと、Azure Batch アカウントとサブスクリプションにする必要があります。</span><span class="sxs-lookup"><span data-stu-id="99f47-111">The virtual network must be in the same region and subscription as the Azure Batch account.</span></span> <span data-ttu-id="99f47-112">指定したサブネットに、プール内のノードの数に合わせて十分な空き IP アドレスが必要です。</span><span class="sxs-lookup"><span data-stu-id="99f47-112">The specified subnet should have enough free IP addresses to accommodate the number of nodes in the pool.</span></span>
            <span data-ttu-id="99f47-113">サブネットには、十分な空き IP アドレスが割り当てられていない、プールは、コンピューティング ノードを割り当てます部分的にし、サイズ変更エラーが発生します。</span><span class="sxs-lookup"><span data-stu-id="99f47-113">If the subnet doesn't have enough free IP addresses, the pool will partially allocate compute nodes, and a resize error will occur.</span></span>
            <span data-ttu-id="99f47-114">'MicrosoftAzureBatch' サービス プリンシパルには、指定された VNet の 'クラシック仮想マシン コントリビューター' ロールベースのアクセス制御 (RBAC) の役割が必要です。</span><span class="sxs-lookup"><span data-stu-id="99f47-114">The 'MicrosoftAzureBatch' service principal must have the 'Classic Virtual Machine Contributor' Role-Based Access Control (RBAC) role for the specified VNet.</span></span> <span data-ttu-id="99f47-115">指定されたサブネットは、コンピューティング ノードでタスクをスケジュールできる Azure Batch のサービスからの通信を許可する必要があります。</span><span class="sxs-lookup"><span data-stu-id="99f47-115">The specified subnet must allow communication from the Azure Batch service to be able to schedule tasks on the compute nodes.</span></span> <span data-ttu-id="99f47-116">これは、指定された VNet が、関連付けられたネットワーク セキュリティ グループ (NSG) をチェックして検証できます。</span><span class="sxs-lookup"><span data-stu-id="99f47-116">This can be verified by checking if the specified VNet has any associated Network Security Groups (NSG).</span></span> <span data-ttu-id="99f47-117">NSG によって指定されたサブネット内の計算ノードへの通信が拒否された場合、バッチ サービスはコンピューティング ノードの状態に設定使用できなくなります。</span><span class="sxs-lookup"><span data-stu-id="99f47-117">If communication to the compute nodes in the specified subnet is denied by an NSG, then the Batch service will set the state of the compute nodes to unusable.</span></span> <span data-ttu-id="99f47-118">VirtualMachineConfiguration で作成されたプールの ARM 仮想ネットワークのみ ('Microsoft.Network/virtualNetworks') はサポートされますが、cloudServiceConfiguration で作成されたプールの ARM とクラシック仮想ネットワークの両方がサポートされています。</span><span class="sxs-lookup"><span data-stu-id="99f47-118">For pools created with virtualMachineConfiguration only ARM virtual networks ('Microsoft.Network/virtualNetworks') are supported, but for pools created with cloudServiceConfiguration both ARM and classic virtual networks are supported.</span></span> <span data-ttu-id="99f47-119">指定した VNet にネットワーク セキュリティ グループ (NSG) が関連付けられている場合、予約されているいくつかのシステム ポートの受信通信を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="99f47-119">If the specified VNet has any associated Network Security Groups (NSG), then a few reserved system ports must be enabled for inbound communication.</span></span> <span data-ttu-id="99f47-120">仮想マシン構成で作成されたプールの場合、ポート 29876 と 29877 を有効にしたうえで、Linux の場合はポート 22 を、Windows の場合はポート 3389 を有効にします。</span><span class="sxs-lookup"><span data-stu-id="99f47-120">For pools created with a virtual machine configuration, enable ports 29876 and 29877, as well as port 22 for Linux and port 3389 for Windows.</span></span> <span data-ttu-id="99f47-121">クラウド サービス構成で作成されたプールの場合、10100、20100、30100 の各ポートを有効にします。</span><span class="sxs-lookup"><span data-stu-id="99f47-121">For pools created with a cloud service configuration, enable ports 10100, 20100, and 30100.</span></span> <span data-ttu-id="99f47-122">またポート 443 での Azure ストレージへの発信接続を有効にします。</span><span class="sxs-lookup"><span data-stu-id="99f47-122">Also enable outbound connections to Azure Storage on port 443.</span></span> <span data-ttu-id="99f47-123">詳細についてを参照してください: https://docs.microsoft.com/en-us/azure/batch/batch-api-basics#virtual-network-vnet-and-firewall-configuration</span><span class="sxs-lookup"><span data-stu-id="99f47-123">For more details see: https://docs.microsoft.com/en-us/azure/batch/batch-api-basics#virtual-network-vnet-and-firewall-configuration</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.NetworkConfiguration.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="networkConfiguration.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="99f47-124">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="99f47-124">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="99f47-125">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="99f47-125">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>