<Type Name="IWithOSDiskImageSource" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithOSDiskImageSource">
  <TypeSignature Language="C#" Value="public interface IWithOSDiskImageSource" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithOSDiskImageSource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithOSDiskImageSource" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithOSDiskImageSource" />
  <TypeSignature Language="F#" Value="type IWithOSDiskImageSource = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c3408-101">OS ソースと OS イメージの OS の状態を選択できるように、イメージ定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="c3408-101">The stage of the image definition allowing to choose an OS source and an OS state for the OS image.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithLinuxFromDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithLinuxFromDisk (Microsoft.Azure.Management.Compute.Fluent.IDisk sourceManagedDisk, Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes osState);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithLinuxFromDisk(class Microsoft.Azure.Management.Compute.Fluent.IDisk sourceManagedDisk, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes osState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithOSDiskImageSource.WithLinuxFromDisk(Microsoft.Azure.Management.Compute.Fluent.IDisk,Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithLinuxFromDisk (sourceManagedDisk As IDisk, osState As OperatingSystemStateTypes) As IWithCreateAndDataDiskImageOSDiskSettings" />
      <MemberSignature Language="F#" Value="abstract member WithLinuxFromDisk : Microsoft.Azure.Management.Compute.Fluent.IDisk * Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings" Usage="iWithOSDiskImageSource.WithLinuxFromDisk (sourceManagedDisk, osState)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceManagedDisk" Type="Microsoft.Azure.Management.Compute.Fluent.IDisk" />
        <Parameter Name="osState" Type="Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes" />
      </Parameters>
      <Docs>
        <param name="sourceManagedDisk"><span data-ttu-id="c3408-102">ソースは、ディスクを管理します。</span><span class="sxs-lookup"><span data-stu-id="c3408-102">Source managed disk.</span></span></param>
        <param name="osState"><span data-ttu-id="c3408-103">オペレーティング システムの状態。</span><span class="sxs-lookup"><span data-stu-id="c3408-103">Operating system state.</span></span></param>
        <summary>
            <span data-ttu-id="c3408-104">Linux のソース管理ディスクのディスク イメージの OS を指定します。</span><span class="sxs-lookup"><span data-stu-id="c3408-104">Specifies the Linux source managed disk for the OS disk image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="c3408-105">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="c3408-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithLinuxFromDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithLinuxFromDisk (string sourceManagedDiskId, Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes osState);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithLinuxFromDisk(string sourceManagedDiskId, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes osState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithOSDiskImageSource.WithLinuxFromDisk(System.String,Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithLinuxFromDisk (sourceManagedDiskId As String, osState As OperatingSystemStateTypes) As IWithCreateAndDataDiskImageOSDiskSettings" />
      <MemberSignature Language="F#" Value="abstract member WithLinuxFromDisk : string * Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings" Usage="iWithOSDiskImageSource.WithLinuxFromDisk (sourceManagedDiskId, osState)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceManagedDiskId" Type="System.String" />
        <Parameter Name="osState" Type="Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes" />
      </Parameters>
      <Docs>
        <param name="sourceManagedDiskId"><span data-ttu-id="c3408-106">ソースの管理対象ディスクのリソース id です。</span><span class="sxs-lookup"><span data-stu-id="c3408-106">Source managed disk resource ID.</span></span></param>
        <param name="osState"><span data-ttu-id="c3408-107">オペレーティング システムの状態。</span><span class="sxs-lookup"><span data-stu-id="c3408-107">Operating system state.</span></span></param>
        <summary>
            <span data-ttu-id="c3408-108">Linux のソース管理ディスクのディスク イメージの OS を指定します。</span><span class="sxs-lookup"><span data-stu-id="c3408-108">Specifies the Linux source managed disk for the OS disk image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="c3408-109">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="c3408-109">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithLinuxFromSnapshot">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithLinuxFromSnapshot (Microsoft.Azure.Management.Compute.Fluent.ISnapshot sourceSnapshot, Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes osState);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithLinuxFromSnapshot(class Microsoft.Azure.Management.Compute.Fluent.ISnapshot sourceSnapshot, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes osState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithOSDiskImageSource.WithLinuxFromSnapshot(Microsoft.Azure.Management.Compute.Fluent.ISnapshot,Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithLinuxFromSnapshot (sourceSnapshot As ISnapshot, osState As OperatingSystemStateTypes) As IWithCreateAndDataDiskImageOSDiskSettings" />
      <MemberSignature Language="F#" Value="abstract member WithLinuxFromSnapshot : Microsoft.Azure.Management.Compute.Fluent.ISnapshot * Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings" Usage="iWithOSDiskImageSource.WithLinuxFromSnapshot (sourceSnapshot, osState)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceSnapshot" Type="Microsoft.Azure.Management.Compute.Fluent.ISnapshot" />
        <Parameter Name="osState" Type="Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes" />
      </Parameters>
      <Docs>
        <param name="sourceSnapshot"><span data-ttu-id="c3408-110">ソースのスナップショットのリソースです。</span><span class="sxs-lookup"><span data-stu-id="c3408-110">Source snapshot resource.</span></span></param>
        <param name="osState"><span data-ttu-id="c3408-111">オペレーティング システムの状態。</span><span class="sxs-lookup"><span data-stu-id="c3408-111">Operating system state.</span></span></param>
        <summary>
            <span data-ttu-id="c3408-112">OS ディスク イメージの Linux ソースのスナップショットを指定します。</span><span class="sxs-lookup"><span data-stu-id="c3408-112">Specifies the Linux source snapshot for the OS disk image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="c3408-113">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="c3408-113">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithLinuxFromSnapshot">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithLinuxFromSnapshot (string sourceSnapshotId, Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes osState);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithLinuxFromSnapshot(string sourceSnapshotId, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes osState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithOSDiskImageSource.WithLinuxFromSnapshot(System.String,Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithLinuxFromSnapshot (sourceSnapshotId As String, osState As OperatingSystemStateTypes) As IWithCreateAndDataDiskImageOSDiskSettings" />
      <MemberSignature Language="F#" Value="abstract member WithLinuxFromSnapshot : string * Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings" Usage="iWithOSDiskImageSource.WithLinuxFromSnapshot (sourceSnapshotId, osState)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceSnapshotId" Type="System.String" />
        <Parameter Name="osState" Type="Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes" />
      </Parameters>
      <Docs>
        <param name="sourceSnapshotId"><span data-ttu-id="c3408-114">ソースのスナップショットのリソース id です。</span><span class="sxs-lookup"><span data-stu-id="c3408-114">Source snapshot resource ID.</span></span></param>
        <param name="osState"><span data-ttu-id="c3408-115">オペレーティング システムの状態。</span><span class="sxs-lookup"><span data-stu-id="c3408-115">Operating system state.</span></span></param>
        <summary>
            <span data-ttu-id="c3408-116">OS ディスク イメージの Linux ソースのスナップショットを指定します。</span><span class="sxs-lookup"><span data-stu-id="c3408-116">Specifies the Linux source snapshot for the OS disk image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="c3408-117">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="c3408-117">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithLinuxFromVhd">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithLinuxFromVhd (string sourceVhdUrl, Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes osState);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithLinuxFromVhd(string sourceVhdUrl, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes osState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithOSDiskImageSource.WithLinuxFromVhd(System.String,Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithLinuxFromVhd (sourceVhdUrl As String, osState As OperatingSystemStateTypes) As IWithCreateAndDataDiskImageOSDiskSettings" />
      <MemberSignature Language="F#" Value="abstract member WithLinuxFromVhd : string * Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings" Usage="iWithOSDiskImageSource.WithLinuxFromVhd (sourceVhdUrl, osState)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceVhdUrl" Type="System.String" />
        <Parameter Name="osState" Type="Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes" />
      </Parameters>
      <Docs>
        <param name="sourceVhdUrl"><span data-ttu-id="c3408-118">ソースの Linux バーチャル ハード ディスクの URL です。</span><span class="sxs-lookup"><span data-stu-id="c3408-118">Source Linux virtual hard disk URL.</span></span></param>
        <param name="osState"><span data-ttu-id="c3408-119">オペレーティング システムの状態。</span><span class="sxs-lookup"><span data-stu-id="c3408-119">Operating system state.</span></span></param>
        <summary>
            <span data-ttu-id="c3408-120">指定、Linux OS ディスク イメージのネイティブの VHD のソースします。</span><span class="sxs-lookup"><span data-stu-id="c3408-120">Specifies the Linux source native VHD for the OS disk image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="c3408-121">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="c3408-121">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithWindowsFromDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithWindowsFromDisk (Microsoft.Azure.Management.Compute.Fluent.IDisk sourceManagedDisk, Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes osState);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithWindowsFromDisk(class Microsoft.Azure.Management.Compute.Fluent.IDisk sourceManagedDisk, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes osState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithOSDiskImageSource.WithWindowsFromDisk(Microsoft.Azure.Management.Compute.Fluent.IDisk,Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithWindowsFromDisk (sourceManagedDisk As IDisk, osState As OperatingSystemStateTypes) As IWithCreateAndDataDiskImageOSDiskSettings" />
      <MemberSignature Language="F#" Value="abstract member WithWindowsFromDisk : Microsoft.Azure.Management.Compute.Fluent.IDisk * Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings" Usage="iWithOSDiskImageSource.WithWindowsFromDisk (sourceManagedDisk, osState)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceManagedDisk" Type="Microsoft.Azure.Management.Compute.Fluent.IDisk" />
        <Parameter Name="osState" Type="Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes" />
      </Parameters>
      <Docs>
        <param name="sourceManagedDisk"><span data-ttu-id="c3408-122">ソースは、ディスクを管理します。</span><span class="sxs-lookup"><span data-stu-id="c3408-122">Source managed disk.</span></span></param>
        <param name="osState"><span data-ttu-id="c3408-123">オペレーティング システムの状態。</span><span class="sxs-lookup"><span data-stu-id="c3408-123">Operating system state.</span></span></param>
        <summary>
            <span data-ttu-id="c3408-124">Windows のソース管理ディスクのディスク イメージの OS を指定します。</span><span class="sxs-lookup"><span data-stu-id="c3408-124">Specifies the Windows source managed disk for the OS disk image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="c3408-125">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="c3408-125">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithWindowsFromDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithWindowsFromDisk (string sourceManagedDiskId, Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes osState);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithWindowsFromDisk(string sourceManagedDiskId, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes osState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithOSDiskImageSource.WithWindowsFromDisk(System.String,Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithWindowsFromDisk (sourceManagedDiskId As String, osState As OperatingSystemStateTypes) As IWithCreateAndDataDiskImageOSDiskSettings" />
      <MemberSignature Language="F#" Value="abstract member WithWindowsFromDisk : string * Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings" Usage="iWithOSDiskImageSource.WithWindowsFromDisk (sourceManagedDiskId, osState)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceManagedDiskId" Type="System.String" />
        <Parameter Name="osState" Type="Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes" />
      </Parameters>
      <Docs>
        <param name="sourceManagedDiskId"><span data-ttu-id="c3408-126">ソースの管理対象ディスクのリソース id です。</span><span class="sxs-lookup"><span data-stu-id="c3408-126">Source managed disk resource ID.</span></span></param>
        <param name="osState"><span data-ttu-id="c3408-127">オペレーティング システムの状態。</span><span class="sxs-lookup"><span data-stu-id="c3408-127">Operating system state.</span></span></param>
        <summary>
            <span data-ttu-id="c3408-128">Windows のソース管理ディスクのディスク イメージの OS を指定します。</span><span class="sxs-lookup"><span data-stu-id="c3408-128">Specifies the Windows source managed disk for the OS disk image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="c3408-129">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="c3408-129">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithWindowsFromSnapshot">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithWindowsFromSnapshot (Microsoft.Azure.Management.Compute.Fluent.ISnapshot sourceSnapshot, Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes osState);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithWindowsFromSnapshot(class Microsoft.Azure.Management.Compute.Fluent.ISnapshot sourceSnapshot, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes osState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithOSDiskImageSource.WithWindowsFromSnapshot(Microsoft.Azure.Management.Compute.Fluent.ISnapshot,Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithWindowsFromSnapshot (sourceSnapshot As ISnapshot, osState As OperatingSystemStateTypes) As IWithCreateAndDataDiskImageOSDiskSettings" />
      <MemberSignature Language="F#" Value="abstract member WithWindowsFromSnapshot : Microsoft.Azure.Management.Compute.Fluent.ISnapshot * Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings" Usage="iWithOSDiskImageSource.WithWindowsFromSnapshot (sourceSnapshot, osState)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceSnapshot" Type="Microsoft.Azure.Management.Compute.Fluent.ISnapshot" />
        <Parameter Name="osState" Type="Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes" />
      </Parameters>
      <Docs>
        <param name="sourceSnapshot"><span data-ttu-id="c3408-130">ソースのスナップショットのリソースです。</span><span class="sxs-lookup"><span data-stu-id="c3408-130">Source snapshot resource.</span></span></param>
        <param name="osState"><span data-ttu-id="c3408-131">オペレーティング システムの状態。</span><span class="sxs-lookup"><span data-stu-id="c3408-131">Operating system state.</span></span></param>
        <summary>
            <span data-ttu-id="c3408-132">OS ディスク イメージの Windows ソースのスナップショットを指定します。</span><span class="sxs-lookup"><span data-stu-id="c3408-132">Specifies the Windows source snapshot for the OS disk image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="c3408-133">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="c3408-133">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithWindowsFromSnapshot">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithWindowsFromSnapshot (string sourceSnapshotId, Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes osState);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithWindowsFromSnapshot(string sourceSnapshotId, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes osState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithOSDiskImageSource.WithWindowsFromSnapshot(System.String,Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithWindowsFromSnapshot (sourceSnapshotId As String, osState As OperatingSystemStateTypes) As IWithCreateAndDataDiskImageOSDiskSettings" />
      <MemberSignature Language="F#" Value="abstract member WithWindowsFromSnapshot : string * Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings" Usage="iWithOSDiskImageSource.WithWindowsFromSnapshot (sourceSnapshotId, osState)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceSnapshotId" Type="System.String" />
        <Parameter Name="osState" Type="Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes" />
      </Parameters>
      <Docs>
        <param name="sourceSnapshotId"><span data-ttu-id="c3408-134">ソースのスナップショットのリソース id です。</span><span class="sxs-lookup"><span data-stu-id="c3408-134">Source snapshot resource ID.</span></span></param>
        <param name="osState"><span data-ttu-id="c3408-135">オペレーティング システムの状態。</span><span class="sxs-lookup"><span data-stu-id="c3408-135">Operating system state.</span></span></param>
        <summary>
            <span data-ttu-id="c3408-136">OS ディスク イメージの Windows ソースのスナップショットを指定します。</span><span class="sxs-lookup"><span data-stu-id="c3408-136">Specifies the Windows source snapshot for the OS disk image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="c3408-137">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="c3408-137">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithWindowsFromVhd">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithWindowsFromVhd (string sourceVhdUrl, Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes osState);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithWindowsFromVhd(string sourceVhdUrl, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes osState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithOSDiskImageSource.WithWindowsFromVhd(System.String,Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithWindowsFromVhd (sourceVhdUrl As String, osState As OperatingSystemStateTypes) As IWithCreateAndDataDiskImageOSDiskSettings" />
      <MemberSignature Language="F#" Value="abstract member WithWindowsFromVhd : string * Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings" Usage="iWithOSDiskImageSource.WithWindowsFromVhd (sourceVhdUrl, osState)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceVhdUrl" Type="System.String" />
        <Parameter Name="osState" Type="Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes" />
      </Parameters>
      <Docs>
        <param name="sourceVhdUrl"><span data-ttu-id="c3408-138">ソースの Windows バーチャル ハード ディスクの URL です。</span><span class="sxs-lookup"><span data-stu-id="c3408-138">Source Windows virtual hard disk URL.</span></span></param>
        <param name="osState"><span data-ttu-id="c3408-139">オペレーティング システムの状態。</span><span class="sxs-lookup"><span data-stu-id="c3408-139">Operating system state.</span></span></param>
        <summary>
            <span data-ttu-id="c3408-140">Windows を指定のディスク イメージの OS のネイティブの VHD のソースします。</span><span class="sxs-lookup"><span data-stu-id="c3408-140">Specifies the Windows source native VHD for the OS disk image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="c3408-141">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="c3408-141">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>