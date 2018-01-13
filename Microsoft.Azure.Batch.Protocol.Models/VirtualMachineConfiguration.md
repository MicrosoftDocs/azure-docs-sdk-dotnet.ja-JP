<Type Name="VirtualMachineConfiguration" FullName="Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration">
  <TypeSignature Language="C#" Value="public class VirtualMachineConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineConfiguration extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineConfiguration" />
  <TypeSignature Language="F#" Value="type VirtualMachineConfiguration = class" />
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
            <span data-ttu-id="9abaf-101">構成は、Azure Virtual Machines インフラストラクチャに基づいて、プール内のノードを計算します。</span><span class="sxs-lookup"><span data-stu-id="9abaf-101">The configuration for compute nodes in a pool based on the Azure Virtual Machines infrastructure.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.#ctor" />
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
            <span data-ttu-id="9abaf-102">VirtualMachineConfiguration クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="9abaf-102">Initializes a new instance of the VirtualMachineConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineConfiguration (Microsoft.Azure.Batch.Protocol.Models.ImageReference imageReference, string nodeAgentSKUId, Microsoft.Azure.Batch.Protocol.Models.OSDisk osDisk = null, Microsoft.Azure.Batch.Protocol.Models.WindowsConfiguration windowsConfiguration = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.DataDisk&gt; dataDisks = null, string licenseType = null, Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration containerConfiguration = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Protocol.Models.ImageReference imageReference, string nodeAgentSKUId, class Microsoft.Azure.Batch.Protocol.Models.OSDisk osDisk, class Microsoft.Azure.Batch.Protocol.Models.WindowsConfiguration windowsConfiguration, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.DataDisk&gt; dataDisks, string licenseType, class Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration containerConfiguration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.#ctor(Microsoft.Azure.Batch.Protocol.Models.ImageReference,System.String,Microsoft.Azure.Batch.Protocol.Models.OSDisk,Microsoft.Azure.Batch.Protocol.Models.WindowsConfiguration,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.DataDisk},System.String,Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration : Microsoft.Azure.Batch.Protocol.Models.ImageReference * string * Microsoft.Azure.Batch.Protocol.Models.OSDisk * Microsoft.Azure.Batch.Protocol.Models.WindowsConfiguration * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.DataDisk&gt; * string * Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration -&gt; Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration" Usage="new Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration (imageReference, nodeAgentSKUId, osDisk, windowsConfiguration, dataDisks, licenseType, containerConfiguration)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="imageReference" Type="Microsoft.Azure.Batch.Protocol.Models.ImageReference" />
        <Parameter Name="nodeAgentSKUId" Type="System.String" />
        <Parameter Name="osDisk" Type="Microsoft.Azure.Batch.Protocol.Models.OSDisk" />
        <Parameter Name="windowsConfiguration" Type="Microsoft.Azure.Batch.Protocol.Models.WindowsConfiguration" />
        <Parameter Name="dataDisks" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.DataDisk&gt;" />
        <Parameter Name="licenseType" Type="System.String" />
        <Parameter Name="containerConfiguration" Type="Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration" />
      </Parameters>
      <Docs>
        <param name="imageReference"><span data-ttu-id="9abaf-103">Azure の仮想マシンの Marketplace イメージまたはを使用するカスタムの仮想マシンのイメージへの参照。</span><span class="sxs-lookup"><span data-stu-id="9abaf-103">A reference to the Azure Virtual Machines Marketplace image or the custom Virtual Machine image to use.</span></span></param>
        <param name="nodeAgentSKUId"><span data-ttu-id="9abaf-104">プロビジョニングする Batch ノード エージェント SKU では、プール内のノードを計算します。</span><span class="sxs-lookup"><span data-stu-id="9abaf-104">The SKU of the Batch node agent to be provisioned on compute nodes in the pool.</span></span></param>
        <param name="osDisk"><span data-ttu-id="9abaf-105">仮想マシンのオペレーティング システム ディスクの設定です。</span><span class="sxs-lookup"><span data-stu-id="9abaf-105">Settings for the operating system disk of the Virtual Machine.</span></span></param>
        <param name="windowsConfiguration"><span data-ttu-id="9abaf-106">仮想マシンで Windows オペレーティング システムの設定です。</span><span class="sxs-lookup"><span data-stu-id="9abaf-106">Windows operating system settings on the virtual machine.</span></span></param>
        <param name="dataDisks"><span data-ttu-id="9abaf-107">プール内の comptue ノードに接続されているデータ ディスクの構成。</span><span class="sxs-lookup"><span data-stu-id="9abaf-107">The configuration for data disks attached to the comptue nodes in the pool.</span></span></param>
        <param name="licenseType"><span data-ttu-id="9abaf-108">オペレーティング システムを展開するときに使用される内部設置型ライセンスの種類。</span><span class="sxs-lookup"><span data-stu-id="9abaf-108">The type of on-premises license to be used when deploying the operating system.</span></span></param>
        <param name="containerConfiguration"><span data-ttu-id="9abaf-109">プールのコンテナーの構成。</span><span class="sxs-lookup"><span data-stu-id="9abaf-109">The container configuration for the pool.</span></span></param>
        <summary>
            <span data-ttu-id="9abaf-110">VirtualMachineConfiguration クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="9abaf-110">Initializes a new instance of the VirtualMachineConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration ContainerConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration ContainerConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.ContainerConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerConfiguration As ContainerConfiguration" />
      <MemberSignature Language="F#" Value="member this.ContainerConfiguration : Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.ContainerConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="containerConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9abaf-111">取得またはプールのコンテナーの構成を設定します。</span><span class="sxs-lookup"><span data-stu-id="9abaf-111">Gets or sets the container configuration for the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="9abaf-112">指定した場合、プール内のコンテナーでタスクを実行できるようにするには、各ノードでセットアップを実行します。</span><span class="sxs-lookup"><span data-stu-id="9abaf-112">If specified, setup is performed on each node in the pool to allow tasks to run in containers.</span></span> <span data-ttu-id="9abaf-113">すべての正規のタスクとこのプールで実行されるジョブ マネージャー タスクが containerSettings プロパティを指定する必要があり、その他のすべてのタスクが指定可能性があります。</span><span class="sxs-lookup"><span data-stu-id="9abaf-113">All regular tasks and job manager tasks run on this pool must specify the containerSettings property, and all other tasks may specify it.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DataDisks">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.DataDisk&gt; DataDisks { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.DataDisk&gt; DataDisks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.DataDisks" />
      <MemberSignature Language="VB.NET" Value="Public Property DataDisks As IList(Of DataDisk)" />
      <MemberSignature Language="F#" Value="member this.DataDisks : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.DataDisk&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.DataDisks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dataDisks")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.DataDisk&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9abaf-114">取得またはプール内の comptue ノードに接続されているデータ ディスクの構成を設定します。</span><span class="sxs-lookup"><span data-stu-id="9abaf-114">Gets or sets the configuration for data disks attached to the comptue nodes in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="9abaf-115">このプロパティを指定する必要があります指定されたかどうか、プール内の計算ノードは空のデータ ディスクを関連付けることがある必要があります。</span><span class="sxs-lookup"><span data-stu-id="9abaf-115">This property must be specified if the compute nodes in the pool need to have empty data disks attached to them.</span></span> <span data-ttu-id="9abaf-116">これは更新できません。</span><span class="sxs-lookup"><span data-stu-id="9abaf-116">This cannot be updated.</span></span> <span data-ttu-id="9abaf-117">各ノードでは、独自のディスク (ディスクは、ファイル共有ではありません) を取得します。</span><span class="sxs-lookup"><span data-stu-id="9abaf-117">Each node gets its own disk (the disk is not a file share).</span></span> <span data-ttu-id="9abaf-118">既存のディスクをアタッチすることはできません、各接続されたディスクが空です。</span><span class="sxs-lookup"><span data-stu-id="9abaf-118">Existing disks cannot be attached, each attached disk is empty.</span></span> <span data-ttu-id="9abaf-119">ノードがプールから削除されると、ディスクと関連付けられているすべてのデータも削除されます。</span><span class="sxs-lookup"><span data-stu-id="9abaf-119">When the node is removed from the pool, the disk and all data associated with it is also deleted.</span></span> <span data-ttu-id="9abaf-120">アタッチした後、ディスクがフォーマットされていない、他の情報を参照してください https://docs.microsoft.com/en-us/azure/virtual-machines/linux/classic/attach-disk#initialize-a-new-data-disk-in-linux や https://- 使用する前にフォーマットされている必要があります。docs.microsoft.com/en-us/azure/virtual-machines/windows/attach-disk-ps#add-an-empty-data-disk-to-a-virtual-machine です。</span><span class="sxs-lookup"><span data-stu-id="9abaf-120">The disk is not formatted after being attached, it must be formatted before use - for more information see https://docs.microsoft.com/en-us/azure/virtual-machines/linux/classic/attach-disk#initialize-a-new-data-disk-in-linux and https://docs.microsoft.com/en-us/azure/virtual-machines/windows/attach-disk-ps#add-an-empty-data-disk-to-a-virtual-machine.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ImageReference">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.ImageReference ImageReference { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.ImageReference ImageReference" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.ImageReference" />
      <MemberSignature Language="VB.NET" Value="Public Property ImageReference As ImageReference" />
      <MemberSignature Language="F#" Value="member this.ImageReference : Microsoft.Azure.Batch.Protocol.Models.ImageReference with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.ImageReference" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="imageReference")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ImageReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9abaf-121">取得または Azure の仮想マシンの Marketplace イメージまたはを使用するカスタムの仮想マシンのイメージへの参照を設定します。</span><span class="sxs-lookup"><span data-stu-id="9abaf-121">Gets or sets a reference to the Azure Virtual Machines Marketplace image or the custom Virtual Machine image to use.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="9abaf-122">このプロパティと osDisk は相互に排他的とプロパティのいずれかを指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="9abaf-122">This property and osDisk are mutually exclusive and one of the properties must be specified.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LicenseType">
      <MemberSignature Language="C#" Value="public string LicenseType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LicenseType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.LicenseType" />
      <MemberSignature Language="VB.NET" Value="Public Property LicenseType As String" />
      <MemberSignature Language="F#" Value="member this.LicenseType : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.LicenseType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="licenseType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
             <span data-ttu-id="9abaf-123">取得またはオペレーティング システムを展開するときに使用される内部設置型ライセンスの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="9abaf-123">Gets or sets the type of on-premises license to be used when deploying the operating system.</span></span>
             </summary>
        <value>To be added.</value>
        <remarks>
             <span data-ttu-id="9abaf-124">これは、Windows オペレーティング システムが含まれており、展開するノードの有効な内部設置型ライセンスを保持する場合にのみ使用されるイメージにのみ適用されます。</span><span class="sxs-lookup"><span data-stu-id="9abaf-124">This only applies to images that contain the Windows operating system, and should only be used when you hold valid on-premises licenses for the nodes which will be deployed.</span></span> <span data-ttu-id="9abaf-125">省略した場合、なし、内部設置型ライセンス割引が適用されます。</span><span class="sxs-lookup"><span data-stu-id="9abaf-125">If omitted, no on-premises licensing discount is applied.</span></span> <span data-ttu-id="9abaf-126">値は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="9abaf-126">Values are:</span></span>
             
             <span data-ttu-id="9abaf-127">Windows Server は、内部設置型ライセンス Windows_Server - です。</span><span class="sxs-lookup"><span data-stu-id="9abaf-127">Windows_Server - The on-premises license is for Windows Server.</span></span>
             <span data-ttu-id="9abaf-128">Windows クライアントは、内部設置型ライセンス Windows_Client - です。</span><span class="sxs-lookup"><span data-stu-id="9abaf-128">Windows_Client - The on-premises license is for Windows Client.</span></span>
            
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeAgentSKUId">
      <MemberSignature Language="C#" Value="public string NodeAgentSKUId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeAgentSKUId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.NodeAgentSKUId" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeAgentSKUId As String" />
      <MemberSignature Language="F#" Value="member this.NodeAgentSKUId : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.NodeAgentSKUId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nodeAgentSKUId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9abaf-129">取得または設定をプール内の計算ノードで提供するバッチ ノード エージェント SKU。</span><span class="sxs-lookup"><span data-stu-id="9abaf-129">Gets or sets the SKU of the Batch node agent to be provisioned on compute nodes in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="9abaf-130">Batch ノード エージェントは、プール内の各ノード上で実行され、ノードと、バッチ サービスの間のコマンドとコントロール インターフェイスを提供するプログラムです。</span><span class="sxs-lookup"><span data-stu-id="9abaf-130">The Batch node agent is a program that runs on each node in the pool, and provides the command-and-control interface between the node and the Batch service.</span></span> <span data-ttu-id="9abaf-131">オペレーティング システムに応じてさまざまなノード エージェントの実装 (SKU と呼ばれます) があります。</span><span class="sxs-lookup"><span data-stu-id="9abaf-131">There are different implementations of the node agent, known as SKUs, for different operating systems.</span></span> <span data-ttu-id="9abaf-132">ノード エージェント SKU 選択した画像の参照に一致するを指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="9abaf-132">You must specify a node agent SKU which matches the selected image reference.</span></span> <span data-ttu-id="9abaf-133">検証済みのイメージの参照の一覧と共にサポートされているノード エージェント Sku の一覧を取得するには、'リストには、ノード エージェント Sku がサポートされている' 操作を参照してください。</span><span class="sxs-lookup"><span data-stu-id="9abaf-133">To get the list of supported node agent SKUs along with their list of verified image references, see the 'List supported node agent SKUs' operation.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OsDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.OSDisk OsDisk { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.OSDisk OsDisk" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.OsDisk" />
      <MemberSignature Language="VB.NET" Value="Public Property OsDisk As OSDisk" />
      <MemberSignature Language="F#" Value="member this.OsDisk : Microsoft.Azure.Batch.Protocol.Models.OSDisk with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.OsDisk" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="osDisk")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.OSDisk</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9abaf-134">取得または仮想マシンのオペレーティング システム ディスクの設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="9abaf-134">Gets or sets settings for the operating system disk of the Virtual Machine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="9abaf-135">このプロパティに指定できる Batch アカウントが、poolAllocationMode プロパティ 'UserSubscription' に設定して作成されたかどうかにのみ指定します。</span><span class="sxs-lookup"><span data-stu-id="9abaf-135">This property can be specified only if the Batch account was created with its poolAllocationMode property set to 'UserSubscription'.</span></span> <span data-ttu-id="9abaf-136">このプロパティと imageReference は、相互に排他的とプロパティのいずれかを指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="9abaf-136">This property and imageReference are mutually exclusive and one of the properties must be specified.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="virtualMachineConfiguration.Validate " />
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
            <span data-ttu-id="9abaf-137">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="9abaf-137">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9abaf-138">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9abaf-138">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="WindowsConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.WindowsConfiguration WindowsConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.WindowsConfiguration WindowsConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.WindowsConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property WindowsConfiguration As WindowsConfiguration" />
      <MemberSignature Language="F#" Value="member this.WindowsConfiguration : Microsoft.Azure.Batch.Protocol.Models.WindowsConfiguration with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.VirtualMachineConfiguration.WindowsConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="windowsConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.WindowsConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9abaf-139">取得または仮想マシンで windows オペレーティング システムの設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="9abaf-139">Gets or sets windows operating system settings on the virtual machine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="9abaf-140">このプロパティにはできません、imageReference または osDisk プロパティが、Linux OS イメージを指定するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="9abaf-140">This property must not be specified if the imageReference or osDisk property specifies a Linux OS image.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>