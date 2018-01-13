<Type Name="ImageReference" FullName="Microsoft.Azure.Management.Batch.Models.ImageReference">
  <TypeSignature Language="C#" Value="public class ImageReference" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ImageReference extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.ImageReference" />
  <TypeSignature Language="VB.NET" Value="Public Class ImageReference" />
  <TypeSignature Language="F#" Value="type ImageReference = class" />
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
            <span data-ttu-id="b4275-101">Azure の仮想マシンの Marketplace イメージまたはカスタムの仮想マシンの Azure イメージ リソースへの参照。</span><span class="sxs-lookup"><span data-stu-id="b4275-101">A reference to an Azure Virtual Machines Marketplace image or the Azure Image resource of a custom Virtual Machine.</span></span> <span data-ttu-id="b4275-102">Azure Batch によって検証すべて Imagereference の一覧を取得するには、'リストには、ノード エージェント Sku がサポートされている' 操作を参照してください。</span><span class="sxs-lookup"><span data-stu-id="b4275-102">To get the list of all imageReferences verified by Azure Batch, see the 'List supported node agent SKUs' operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImageReference ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.ImageReference.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b4275-103">ImageReference クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b4275-103">Initializes a new instance of the ImageReference class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImageReference (string publisher = null, string offer = null, string sku = null, string version = null, string id = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string publisher, string offer, string sku, string version, string id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.ImageReference.#ctor(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional publisher As String = null, Optional offer As String = null, Optional sku As String = null, Optional version As String = null, Optional id As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.ImageReference : string * string * string * string * string -&gt; Microsoft.Azure.Management.Batch.Models.ImageReference" Usage="new Microsoft.Azure.Management.Batch.Models.ImageReference (publisher, offer, sku, version, id)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="publisher" Type="System.String" />
        <Parameter Name="offer" Type="System.String" />
        <Parameter Name="sku" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="publisher"><span data-ttu-id="b4275-104">Azure の仮想マシンの Marketplace イメージのパブリッシャーです。</span><span class="sxs-lookup"><span data-stu-id="b4275-104">The publisher of the Azure Virtual Machines Marketplace image.</span></span></param>
        <param name="offer"><span data-ttu-id="b4275-105">Azure の仮想マシンの Marketplace イメージのオファーの種類。</span><span class="sxs-lookup"><span data-stu-id="b4275-105">The offer type of the Azure Virtual Machines Marketplace image.</span></span></param>
        <param name="sku"><span data-ttu-id="b4275-106">Azure の仮想マシンの Marketplace イメージの SKU。</span><span class="sxs-lookup"><span data-stu-id="b4275-106">The SKU of the Azure Virtual Machines Marketplace image.</span></span></param>
        <param name="version"><span data-ttu-id="b4275-107">Azure の仮想マシンの Marketplace イメージのバージョン。</span><span class="sxs-lookup"><span data-stu-id="b4275-107">The version of the Azure Virtual Machines Marketplace image.</span></span></param>
        <param name="id"><span data-ttu-id="b4275-108">バーチャル マシンのイメージを ARM リソース識別子です。</span><span class="sxs-lookup"><span data-stu-id="b4275-108">The ARM resource identifier of the virtual machine image.</span></span> <span data-ttu-id="b4275-109">このカスタム イメージを使用して、プールのノードが作成されますが計算されます。</span><span class="sxs-lookup"><span data-stu-id="b4275-109">Computes nodes of the pool will be created using this custom image.</span></span> <span data-ttu-id="b4275-110">これは、フォーム/subscriptions/{subscriptionId}/resourceGroups/{resourceGroup}/providers/Microsoft.Compute/images/{imageName の}</span><span class="sxs-lookup"><span data-stu-id="b4275-110">This is of the form /subscriptions/{subscriptionId}/resourceGroups/{resourceGroup}/providers/Microsoft.Compute/images/{imageName}</span></span></param>
        <summary>
            <span data-ttu-id="b4275-111">ImageReference クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b4275-111">Initializes a new instance of the ImageReference class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.ImageReference.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.ImageReference.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b4275-112">取得またはバーチャル マシンのイメージを ARM リソース識別子を設定します。</span><span class="sxs-lookup"><span data-stu-id="b4275-112">Gets or sets the ARM resource identifier of the virtual machine image.</span></span> <span data-ttu-id="b4275-113">このカスタム イメージを使用して、プールのノードが作成されますが計算されます。</span><span class="sxs-lookup"><span data-stu-id="b4275-113">Computes nodes of the pool will be created using this custom image.</span></span> <span data-ttu-id="b4275-114">これは、フォーム/subscriptions/{subscriptionId}/resourceGroups/{resourceGroup}/providers/Microsoft.Compute/images/{imageName の}</span><span class="sxs-lookup"><span data-stu-id="b4275-114">This is of the form /subscriptions/{subscriptionId}/resourceGroups/{resourceGroup}/providers/Microsoft.Compute/images/{imageName}</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="b4275-115">このプロパティは、その他のプロパティで相互に排他的です。</span><span class="sxs-lookup"><span data-stu-id="b4275-115">This property is mutually exclusive with other properties.</span></span> <span data-ttu-id="b4275-116">バーチャル マシンのイメージは、同じリージョンと、Azure Batch アカウントとサブスクリプションにする必要があります。</span><span class="sxs-lookup"><span data-stu-id="b4275-116">The virtual machine image must be in the same region and subscription as the Azure Batch account.</span></span> <span data-ttu-id="b4275-117">バッチ サービスと通信する Batch ノード エージェントに対するファイアウォール設定に関する情報は、https://docs.microsoft.com/en-us/azure/batch/batch-api-basics#virtual-network-vnet-and-firewall-configuration を参照してください。</span><span class="sxs-lookup"><span data-stu-id="b4275-117">For information about the firewall settings for Batch node agent to communicate with Batch service see https://docs.microsoft.com/en-us/azure/batch/batch-api-basics#virtual-network-vnet-and-firewall-configuration .</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Offer">
      <MemberSignature Language="C#" Value="public string Offer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Offer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.ImageReference.Offer" />
      <MemberSignature Language="VB.NET" Value="Public Property Offer As String" />
      <MemberSignature Language="F#" Value="member this.Offer : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.ImageReference.Offer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="offer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b4275-118">取得または Azure の仮想マシンの Marketplace イメージのオファーの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="b4275-118">Gets or sets the offer type of the Azure Virtual Machines Marketplace image.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="b4275-119">たとえば、UbuntuServer または WindowsServer です。</span><span class="sxs-lookup"><span data-stu-id="b4275-119">For example, UbuntuServer or WindowsServer.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Publisher">
      <MemberSignature Language="C#" Value="public string Publisher { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Publisher" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.ImageReference.Publisher" />
      <MemberSignature Language="VB.NET" Value="Public Property Publisher As String" />
      <MemberSignature Language="F#" Value="member this.Publisher : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.ImageReference.Publisher" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="publisher")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b4275-120">取得または Azure の仮想マシンの Marketplace イメージのパブリッシャーを設定します。</span><span class="sxs-lookup"><span data-stu-id="b4275-120">Gets or sets the publisher of the Azure Virtual Machines Marketplace image.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="b4275-121">たとえば、正規または MicrosoftWindowsServer です。</span><span class="sxs-lookup"><span data-stu-id="b4275-121">For example, Canonical or MicrosoftWindowsServer.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public string Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.ImageReference.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As String" />
      <MemberSignature Language="F#" Value="member this.Sku : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.ImageReference.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b4275-122">取得または Azure の仮想マシンの Marketplace イメージの SKU を設定します。</span><span class="sxs-lookup"><span data-stu-id="b4275-122">Gets or sets the SKU of the Azure Virtual Machines Marketplace image.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="b4275-123">たとえば、14.04.0-LTS または 2012 R2 Datacenter します。</span><span class="sxs-lookup"><span data-stu-id="b4275-123">For example, 14.04.0-LTS or 2012-R2-Datacenter.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public string Version { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.ImageReference.Version" />
      <MemberSignature Language="VB.NET" Value="Public Property Version As String" />
      <MemberSignature Language="F#" Value="member this.Version : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.ImageReference.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="version")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b4275-124">取得または Azure の仮想マシンの Marketplace イメージのバージョンを設定します。</span><span class="sxs-lookup"><span data-stu-id="b4275-124">Gets or sets the version of the Azure Virtual Machines Marketplace image.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="b4275-125">イメージの最新バージョンを選択する 'latest' の値を指定することができます。</span><span class="sxs-lookup"><span data-stu-id="b4275-125">A value of 'latest' can be specified to select the latest version of an image.</span></span> <span data-ttu-id="b4275-126">省略した場合、既定値は '最新' です。</span><span class="sxs-lookup"><span data-stu-id="b4275-126">If omitted, the default is 'latest'.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>