<Type Name="IWithOS" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS">
  <TypeSignature Language="C#" Value="public interface IWithOS" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithOS" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithOS" />
  <TypeSignature Language="F#" Value="type IWithOS = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="42a43-101">仮想マシンのスケールのステージでは、オペレーティング システム イメージを指定できるように定義を設定します。</span><span class="sxs-lookup"><span data-stu-id="42a43-101">The stage of the virtual machine scale set definition allowing to specify the operating system image.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithLatestLinuxImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManagedOrUnmanaged WithLatestLinuxImage (string publisher, string offer, string sku);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManagedOrUnmanaged WithLatestLinuxImage(string publisher, string offer, string sku) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS.WithLatestLinuxImage(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithLatestLinuxImage (publisher As String, offer As String, sku As String) As IWithLinuxRootUsernameManagedOrUnmanaged" />
      <MemberSignature Language="F#" Value="abstract member WithLatestLinuxImage : string * string * string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManagedOrUnmanaged" Usage="iWithOS.WithLatestLinuxImage (publisher, offer, sku)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManagedOrUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="publisher" Type="System.String" />
        <Parameter Name="offer" Type="System.String" />
        <Parameter Name="sku" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="publisher"><span data-ttu-id="42a43-102">イメージの発行元。</span><span class="sxs-lookup"><span data-stu-id="42a43-102">The publisher of the image.</span></span></param>
        <param name="offer"><span data-ttu-id="42a43-103">イメージのプラン。</span><span class="sxs-lookup"><span data-stu-id="42a43-103">The offer of the image.</span></span></param>
        <param name="sku"><span data-ttu-id="42a43-104">イメージの SKU。</span><span class="sxs-lookup"><span data-stu-id="42a43-104">The SKU of the image.</span></span></param>
        <summary>
            <span data-ttu-id="42a43-105">Marketplace Linux イメージの最新バージョンを使用することを指定します。</span><span class="sxs-lookup"><span data-stu-id="42a43-105">Specifies that the latest version of a marketplace Linux image should be used.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="42a43-106">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="42a43-106">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithLatestWindowsImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged WithLatestWindowsImage (string publisher, string offer, string sku);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged WithLatestWindowsImage(string publisher, string offer, string sku) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS.WithLatestWindowsImage(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithLatestWindowsImage (publisher As String, offer As String, sku As String) As IWithWindowsAdminUsernameManagedOrUnmanaged" />
      <MemberSignature Language="F#" Value="abstract member WithLatestWindowsImage : string * string * string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged" Usage="iWithOS.WithLatestWindowsImage (publisher, offer, sku)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="publisher" Type="System.String" />
        <Parameter Name="offer" Type="System.String" />
        <Parameter Name="sku" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="publisher"><span data-ttu-id="42a43-107">イメージのパブリッシャーを指定します。</span><span class="sxs-lookup"><span data-stu-id="42a43-107">Specifies the publisher of the image.</span></span></param>
        <param name="offer"><span data-ttu-id="42a43-108">イメージのオファーを指定します。</span><span class="sxs-lookup"><span data-stu-id="42a43-108">Specifies the offer of the image.</span></span></param>
        <param name="sku"><span data-ttu-id="42a43-109">イメージの SKU を指定します。</span><span class="sxs-lookup"><span data-stu-id="42a43-109">Specifies the SKU of the image.</span></span></param>
        <summary>
            <span data-ttu-id="42a43-110">指定した marketplace の Windows イメージの最新バージョンを使用することを指定します。</span><span class="sxs-lookup"><span data-stu-id="42a43-110">Specifies that the latest version of the specified marketplace Windows image should be used.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="42a43-111">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="42a43-111">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithLinuxCustomImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManaged WithLinuxCustomImage (string customImageId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManaged WithLinuxCustomImage(string customImageId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS.WithLinuxCustomImage(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithLinuxCustomImage (customImageId As String) As IWithLinuxRootUsernameManaged" />
      <MemberSignature Language="F#" Value="abstract member WithLinuxCustomImage : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManaged" Usage="iWithOS.WithLinuxCustomImage customImageId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customImageId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="customImageId"><span data-ttu-id="42a43-112">カスタム イメージのリソース ID です。</span><span class="sxs-lookup"><span data-stu-id="42a43-112">The resource ID of the custom image.</span></span></param>
        <summary>
            <span data-ttu-id="42a43-113">使用するには、Linux カスタム イメージの ID を指定します。</span><span class="sxs-lookup"><span data-stu-id="42a43-113">Specifies the ID of a Linux custom image to be used.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="42a43-114">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="42a43-114">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithPopularLinuxImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManagedOrUnmanaged WithPopularLinuxImage (Microsoft.Azure.Management.Compute.Fluent.KnownLinuxVirtualMachineImage knownImage);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManagedOrUnmanaged WithPopularLinuxImage(valuetype Microsoft.Azure.Management.Compute.Fluent.KnownLinuxVirtualMachineImage knownImage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS.WithPopularLinuxImage(Microsoft.Azure.Management.Compute.Fluent.KnownLinuxVirtualMachineImage)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPopularLinuxImage (knownImage As KnownLinuxVirtualMachineImage) As IWithLinuxRootUsernameManagedOrUnmanaged" />
      <MemberSignature Language="F#" Value="abstract member WithPopularLinuxImage : Microsoft.Azure.Management.Compute.Fluent.KnownLinuxVirtualMachineImage -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManagedOrUnmanaged" Usage="iWithOS.WithPopularLinuxImage knownImage" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManagedOrUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="knownImage" Type="Microsoft.Azure.Management.Compute.Fluent.KnownLinuxVirtualMachineImage" />
      </Parameters>
      <Docs>
        <param name="knownImage"><span data-ttu-id="42a43-115">既知のマーケットプレイス イメージです。</span><span class="sxs-lookup"><span data-stu-id="42a43-115">A known market-place image.</span></span></param>
        <summary>
            <span data-ttu-id="42a43-116">既知の marketplace、仮想マシンのオペレーティング システムとして使用する Linux イメージを指定します。</span><span class="sxs-lookup"><span data-stu-id="42a43-116">Specifies a known marketplace Linux image used as the virtual machine's operating system.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="42a43-117">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="42a43-117">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithPopularWindowsImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged WithPopularWindowsImage (Microsoft.Azure.Management.Compute.Fluent.KnownWindowsVirtualMachineImage knownImage);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged WithPopularWindowsImage(valuetype Microsoft.Azure.Management.Compute.Fluent.KnownWindowsVirtualMachineImage knownImage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS.WithPopularWindowsImage(Microsoft.Azure.Management.Compute.Fluent.KnownWindowsVirtualMachineImage)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPopularWindowsImage (knownImage As KnownWindowsVirtualMachineImage) As IWithWindowsAdminUsernameManagedOrUnmanaged" />
      <MemberSignature Language="F#" Value="abstract member WithPopularWindowsImage : Microsoft.Azure.Management.Compute.Fluent.KnownWindowsVirtualMachineImage -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged" Usage="iWithOS.WithPopularWindowsImage knownImage" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="knownImage" Type="Microsoft.Azure.Management.Compute.Fluent.KnownWindowsVirtualMachineImage" />
      </Parameters>
      <Docs>
        <param name="knownImage"><span data-ttu-id="42a43-118">既知のマーケットプレイス イメージです。</span><span class="sxs-lookup"><span data-stu-id="42a43-118">A known market-place image.</span></span></param>
        <summary>
            <span data-ttu-id="42a43-119">スケール セット内の仮想マシンのオペレーティング システムとして使用される既知の marketplace Windows イメージを指定します。</span><span class="sxs-lookup"><span data-stu-id="42a43-119">Specifies a known marketplace Windows image used as the operating system for the virtual machines in the scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="42a43-120">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="42a43-120">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithSpecificLinuxImageVersion">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManagedOrUnmanaged WithSpecificLinuxImageVersion (Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference imageReference);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManagedOrUnmanaged WithSpecificLinuxImageVersion(class Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference imageReference) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS.WithSpecificLinuxImageVersion(Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference)" />
      <MemberSignature Language="F#" Value="abstract member WithSpecificLinuxImageVersion : Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManagedOrUnmanaged" Usage="iWithOS.WithSpecificLinuxImageVersion imageReference" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManagedOrUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="imageReference" Type="Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference" />
      </Parameters>
      <Docs>
        <param name="imageReference"><span data-ttu-id="42a43-121">パブリッシャー、プラン、SKU、および市場インプレース イメージのバージョンについて説明します。</span><span class="sxs-lookup"><span data-stu-id="42a43-121">Describes the publisher, offer, SKU and version of the market-place image.</span></span></param>
        <summary>
            <span data-ttu-id="42a43-122">特定のバージョンのために使用される marketplace に Linux イメージを指定します。</span><span class="sxs-lookup"><span data-stu-id="42a43-122">Specifies the specific version of a market-place Linux image that should be used.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="42a43-123">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="42a43-123">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithSpecificWindowsImageVersion">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged WithSpecificWindowsImageVersion (Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference imageReference);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged WithSpecificWindowsImageVersion(class Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference imageReference) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS.WithSpecificWindowsImageVersion(Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference)" />
      <MemberSignature Language="F#" Value="abstract member WithSpecificWindowsImageVersion : Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged" Usage="iWithOS.WithSpecificWindowsImageVersion imageReference" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="imageReference" Type="Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference" />
      </Parameters>
      <Docs>
        <param name="imageReference"><span data-ttu-id="42a43-124">パブリッシャー、プラン、SKU、および marketplace イメージのバージョンについて説明します。</span><span class="sxs-lookup"><span data-stu-id="42a43-124">Describes publisher, offer, SKU and version of the marketplace image.</span></span></param>
        <summary>
            <span data-ttu-id="42a43-125">Windows イメージを使用する必要があります marketplace の特定のバージョンを指定します。</span><span class="sxs-lookup"><span data-stu-id="42a43-125">Specifies the specific version of a marketplace Windows image needs to be used.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="42a43-126">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="42a43-126">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithStoredLinuxImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameUnmanaged WithStoredLinuxImage (string imageUrl);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameUnmanaged WithStoredLinuxImage(string imageUrl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS.WithStoredLinuxImage(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithStoredLinuxImage (imageUrl As String) As IWithLinuxRootUsernameUnmanaged" />
      <MemberSignature Language="F#" Value="abstract member WithStoredLinuxImage : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameUnmanaged" Usage="iWithOS.WithStoredLinuxImage imageUrl" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="imageUrl" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="imageUrl"><span data-ttu-id="42a43-127">URL の VHD。</span><span class="sxs-lookup"><span data-stu-id="42a43-127">The URL the the VHD.</span></span></param>
        <summary>
            <span data-ttu-id="42a43-128">仮想マシンのオペレーティング システムとして使用されるユーザー (カスタム) Linux イメージを指定します。</span><span class="sxs-lookup"><span data-stu-id="42a43-128">Specifies the user (custom) Linux image used as the virtual machine's operating system.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="42a43-129">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="42a43-129">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithStoredWindowsImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameUnmanaged WithStoredWindowsImage (string imageUrl);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameUnmanaged WithStoredWindowsImage(string imageUrl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS.WithStoredWindowsImage(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithStoredWindowsImage (imageUrl As String) As IWithWindowsAdminUsernameUnmanaged" />
      <MemberSignature Language="F#" Value="abstract member WithStoredWindowsImage : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameUnmanaged" Usage="iWithOS.WithStoredWindowsImage imageUrl" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="imageUrl" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="imageUrl"><span data-ttu-id="42a43-130">VHD の URL です。</span><span class="sxs-lookup"><span data-stu-id="42a43-130">The URL of the VHD.</span></span></param>
        <summary>
            <span data-ttu-id="42a43-131">仮想マシン スケール セット内のオペレーティング システムとして使用するユーザー (カスタム) の Windows イメージを指定します。</span><span class="sxs-lookup"><span data-stu-id="42a43-131">Specifies the user (custom) Windows image to be used as the operating system for the virtual machines in the scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="42a43-132">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="42a43-132">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithWindowsCustomImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManaged WithWindowsCustomImage (string customImageId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManaged WithWindowsCustomImage(string customImageId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS.WithWindowsCustomImage(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithWindowsCustomImage (customImageId As String) As IWithWindowsAdminUsernameManaged" />
      <MemberSignature Language="F#" Value="abstract member WithWindowsCustomImage : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManaged" Usage="iWithOS.WithWindowsCustomImage customImageId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customImageId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="customImageId"><span data-ttu-id="42a43-133">カスタム イメージのリソース ID です。</span><span class="sxs-lookup"><span data-stu-id="42a43-133">The resource ID of the custom image.</span></span></param>
        <summary>
            <span data-ttu-id="42a43-134">使用するには、Windows のカスタム イメージの ID を指定します。</span><span class="sxs-lookup"><span data-stu-id="42a43-134">Specifies the ID of a Windows custom image to be used.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="42a43-135">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="42a43-135">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>