<Type Name="VirtualMachineConfiguration" FullName="Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration">
  <TypeSignature Language="C#" Value="public class VirtualMachineConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineConfiguration extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineConfiguration" />
  <TypeSignature Language="F#" Value="type VirtualMachineConfiguration = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="fb566-101">構成は、Azure Virtual Machines インフラストラクチャに基づいて、プール内のノードを計算します。</span><span class="sxs-lookup"><span data-stu-id="fb566-101">The configuration for compute nodes in a pool based on the Azure Virtual Machines infrastructure.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="fb566-102">VirtualMachineConfiguration クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fb566-102">Initializes a new instance of the VirtualMachineConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineConfiguration (Microsoft.Azure.Management.Batch.Models.ImageReference imageReference, string nodeAgentSkuId, Microsoft.Azure.Management.Batch.Models.OSDisk osDisk = null, Microsoft.Azure.Management.Batch.Models.WindowsConfiguration windowsConfiguration = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.DataDisk&gt; dataDisks = null, string licenseType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Batch.Models.ImageReference imageReference, string nodeAgentSkuId, class Microsoft.Azure.Management.Batch.Models.OSDisk osDisk, class Microsoft.Azure.Management.Batch.Models.WindowsConfiguration windowsConfiguration, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.DataDisk&gt; dataDisks, string licenseType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration.#ctor(Microsoft.Azure.Management.Batch.Models.ImageReference,System.String,Microsoft.Azure.Management.Batch.Models.OSDisk,Microsoft.Azure.Management.Batch.Models.WindowsConfiguration,System.Collections.Generic.IList{Microsoft.Azure.Management.Batch.Models.DataDisk},System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration : Microsoft.Azure.Management.Batch.Models.ImageReference * string * Microsoft.Azure.Management.Batch.Models.OSDisk * Microsoft.Azure.Management.Batch.Models.WindowsConfiguration * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.DataDisk&gt; * string -&gt; Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration" Usage="new Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration (imageReference, nodeAgentSkuId, osDisk, windowsConfiguration, dataDisks, licenseType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="imageReference" Type="Microsoft.Azure.Management.Batch.Models.ImageReference" />
        <Parameter Name="nodeAgentSkuId" Type="System.String" />
        <Parameter Name="osDisk" Type="Microsoft.Azure.Management.Batch.Models.OSDisk" />
        <Parameter Name="windowsConfiguration" Type="Microsoft.Azure.Management.Batch.Models.WindowsConfiguration" />
        <Parameter Name="dataDisks" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.DataDisk&gt;" />
        <Parameter Name="licenseType" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="imageReference"><span data-ttu-id="fb566-103">使用するには、Azure の仮想マシンの Marketplace イメージまたはカスタムの仮想マシンのイメージへの参照。</span><span class="sxs-lookup"><span data-stu-id="fb566-103">A reference to the Azure Virtual Machines Marketplace Image or the custom Virtual Machine Image to use.</span></span></param>
        <param name="nodeAgentSkuId"><span data-ttu-id="fb566-104">プロビジョニングする Batch ノード エージェント SKU では、プール内のノードを計算します。</span><span class="sxs-lookup"><span data-stu-id="fb566-104">The SKU of the Batch node agent to be provisioned on compute nodes in the pool.</span></span></param>
        <param name="osDisk"><span data-ttu-id="fb566-105">仮想マシンのオペレーティング システム ディスクの設定です。</span><span class="sxs-lookup"><span data-stu-id="fb566-105">Settings for the operating system disk of the Virtual Machine.</span></span></param>
        <param name="windowsConfiguration"><span data-ttu-id="fb566-106">仮想マシンで Windows オペレーティング システムの設定です。</span><span class="sxs-lookup"><span data-stu-id="fb566-106">Windows operating system settings on the virtual machine.</span></span></param>
        <param name="dataDisks"><span data-ttu-id="fb566-107">プール内の comptue ノードに接続されているデータ ディスクの構成。</span><span class="sxs-lookup"><span data-stu-id="fb566-107">The configuration for data disks attached to the comptue nodes in the pool.</span></span></param>
        <param name="licenseType"><span data-ttu-id="fb566-108">オペレーティング システムを展開するときに使用される内部設置型ライセンスの種類。</span><span class="sxs-lookup"><span data-stu-id="fb566-108">The type of on-premises license to be used when deploying the operating system.</span></span></param>
        <summary>
            <span data-ttu-id="fb566-109">VirtualMachineConfiguration クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fb566-109">Initializes a new instance of the VirtualMachineConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataDisks">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.DataDisk&gt; DataDisks { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.DataDisk&gt; DataDisks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration.DataDisks" />
      <MemberSignature Language="VB.NET" Value="Public Property DataDisks As IList(Of DataDisk)" />
      <MemberSignature Language="F#" Value="member this.DataDisks : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.DataDisk&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration.DataDisks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dataDisks")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.DataDisk&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb566-110">取得またはプール内の comptue ノードに接続されているデータ ディスクの構成を設定します。</span><span class="sxs-lookup"><span data-stu-id="fb566-110">Gets or sets the configuration for data disks attached to the comptue nodes in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="fb566-111">このプロパティを指定する必要があります指定されたかどうか、プール内の計算ノードは空のデータ ディスクを関連付けることがある必要があります。</span><span class="sxs-lookup"><span data-stu-id="fb566-111">This property must be specified if the compute nodes in the pool need to have empty data disks attached to them.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ImageReference">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.ImageReference ImageReference { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.ImageReference ImageReference" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration.ImageReference" />
      <MemberSignature Language="VB.NET" Value="Public Property ImageReference As ImageReference" />
      <MemberSignature Language="F#" Value="member this.ImageReference : Microsoft.Azure.Management.Batch.Models.ImageReference with get, set" Usage="Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration.ImageReference" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="imageReference")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.ImageReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb566-112">取得または使用するには、Azure の仮想マシン Marketplace イメージを使用すると、またはカスタムの仮想マシンのイメージへの参照を設定します。</span><span class="sxs-lookup"><span data-stu-id="fb566-112">Gets or sets a reference to the Azure Virtual Machines Marketplace Image or the custom Virtual Machine Image to use.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LicenseType">
      <MemberSignature Language="C#" Value="public string LicenseType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LicenseType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration.LicenseType" />
      <MemberSignature Language="VB.NET" Value="Public Property LicenseType As String" />
      <MemberSignature Language="F#" Value="member this.LicenseType : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration.LicenseType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
             <span data-ttu-id="fb566-113">取得またはオペレーティング システムを展開するときに使用される内部設置型ライセンスの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="fb566-113">Gets or sets the type of on-premises license to be used when deploying the operating system.</span></span>
             </summary>
        <value>To be added.</value>
        <remarks>
             <span data-ttu-id="fb566-114">これは、Windows オペレーティング システムが含まれており、展開するノードの有効な内部設置型ライセンスを保持する場合にのみ使用されるイメージにのみ適用されます。</span><span class="sxs-lookup"><span data-stu-id="fb566-114">This only applies to images that contain the Windows operating system, and should only be used when you hold valid on-premises licenses for the nodes which will be deployed.</span></span> <span data-ttu-id="fb566-115">省略した場合、なし、内部設置型ライセンス割引が適用されます。</span><span class="sxs-lookup"><span data-stu-id="fb566-115">If omitted, no on-premises licensing discount is applied.</span></span> <span data-ttu-id="fb566-116">値は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="fb566-116">Values are:</span></span>
             
             <span data-ttu-id="fb566-117">Windows Server は、内部設置型ライセンス Windows_Server - です。</span><span class="sxs-lookup"><span data-stu-id="fb566-117">Windows_Server - The on-premises license is for Windows Server.</span></span>
             <span data-ttu-id="fb566-118">Windows クライアントは、内部設置型ライセンス Windows_Client - です。</span><span class="sxs-lookup"><span data-stu-id="fb566-118">Windows_Client - The on-premises license is for Windows Client.</span></span>
            
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeAgentSkuId">
      <MemberSignature Language="C#" Value="public string NodeAgentSkuId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeAgentSkuId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration.NodeAgentSkuId" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeAgentSkuId As String" />
      <MemberSignature Language="F#" Value="member this.NodeAgentSkuId : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration.NodeAgentSkuId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nodeAgentSkuId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb566-119">取得または設定をプール内の計算ノードで提供するバッチ ノード エージェント SKU。</span><span class="sxs-lookup"><span data-stu-id="fb566-119">Gets or sets the SKU of the Batch node agent to be provisioned on compute nodes in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="fb566-120">Batch ノード エージェントは、プール内の各ノード上で実行され、ノードと、バッチ サービスの間のコマンドとコントロール インターフェイスを提供するプログラムです。</span><span class="sxs-lookup"><span data-stu-id="fb566-120">The Batch node agent is a program that runs on each node in the pool, and provides the command-and-control interface between the node and the Batch service.</span></span> <span data-ttu-id="fb566-121">オペレーティング システムに応じてさまざまなノード エージェントの実装 (SKU と呼ばれます) があります。</span><span class="sxs-lookup"><span data-stu-id="fb566-121">There are different implementations of the node agent, known as SKUs, for different operating systems.</span></span> <span data-ttu-id="fb566-122">ノード エージェント SKU 選択した画像の参照に一致するを指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="fb566-122">You must specify a node agent SKU which matches the selected image reference.</span></span> <span data-ttu-id="fb566-123">検証済みのイメージの参照の一覧と共にサポートされているノード エージェント Sku の一覧を取得するには、'リストには、ノード エージェント Sku がサポートされている' 操作を参照してください。</span><span class="sxs-lookup"><span data-stu-id="fb566-123">To get the list of supported node agent SKUs along with their list of verified image references, see the 'List supported node agent SKUs' operation.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OsDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.OSDisk OsDisk { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.OSDisk OsDisk" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration.OsDisk" />
      <MemberSignature Language="VB.NET" Value="Public Property OsDisk As OSDisk" />
      <MemberSignature Language="F#" Value="member this.OsDisk : Microsoft.Azure.Management.Batch.Models.OSDisk with get, set" Usage="Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration.OsDisk" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="osDisk")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.OSDisk</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb566-124">取得または仮想マシンのオペレーティング システム ディスクの設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="fb566-124">Gets or sets settings for the operating system disk of the Virtual Machine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="virtualMachineConfiguration.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="fb566-125">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="fb566-125">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fb566-126">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fb566-126">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="WindowsConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.WindowsConfiguration WindowsConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.WindowsConfiguration WindowsConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration.WindowsConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property WindowsConfiguration As WindowsConfiguration" />
      <MemberSignature Language="F#" Value="member this.WindowsConfiguration : Microsoft.Azure.Management.Batch.Models.WindowsConfiguration with get, set" Usage="Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration.WindowsConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="windowsConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.WindowsConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb566-127">取得または仮想マシンで windows オペレーティング システムの設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="fb566-127">Gets or sets windows operating system settings on the virtual machine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="fb566-128">このプロパティにはできません、imageReference が Linux OS イメージを指定するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="fb566-128">This property must not be specified if the imageReference specifies a Linux OS image.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>