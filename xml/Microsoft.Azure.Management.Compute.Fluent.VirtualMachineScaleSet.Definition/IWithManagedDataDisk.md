<Type Name="IWithManagedDataDisk" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedDataDisk">
  <TypeSignature Language="C#" Value="public interface IWithManagedDataDisk" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithManagedDataDisk" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedDataDisk" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithManagedDataDisk" />
  <TypeSignature Language="F#" Value="type IWithManagedDataDisk = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f5fea-101">仮想マシンのスケールのステージでは、マネージ データ ディスクを指定できるように定義を設定します。</span><span class="sxs-lookup"><span data-stu-id="f5fea-101">The stage of a virtual machine scale set definition allowing to specify managed data disks.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithNewDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate WithNewDataDisk (int sizeInGB);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate WithNewDataDisk(int32 sizeInGB) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedDataDisk.WithNewDataDisk(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewDataDisk (sizeInGB As Integer) As IWithManagedCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewDataDisk : int -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate" Usage="iWithManagedDataDisk.WithNewDataDisk sizeInGB" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sizeInGB" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="sizeInGB"><span data-ttu-id="f5fea-102">管理対象ディスクのサイズ。</span><span class="sxs-lookup"><span data-stu-id="f5fea-102">The size of the managed disk.</span></span></param>
        <summary>
            <span data-ttu-id="f5fea-103">管理対象ディスクを特定のサイズで暗黙的に作成する必要があることを指定します。</span><span class="sxs-lookup"><span data-stu-id="f5fea-103">Specifies that a managed disk needs to be created implicitly with the given size.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="f5fea-104">仮想マシンの定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="f5fea-104">The next stage of virtual machine definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate WithNewDataDisk (int sizeInGB, int lun, Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate WithNewDataDisk(int32 sizeInGB, int32 lun, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedDataDisk.WithNewDataDisk(System.Int32,System.Int32,Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewDataDisk (sizeInGB As Integer, lun As Integer, cachingType As CachingTypes) As IWithManagedCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewDataDisk : int * int * Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate" Usage="iWithManagedDataDisk.WithNewDataDisk (sizeInGB, lun, cachingType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sizeInGB" Type="System.Int32" />
        <Parameter Name="lun" Type="System.Int32" />
        <Parameter Name="cachingType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes" />
      </Parameters>
      <Docs>
        <param name="sizeInGB"><span data-ttu-id="f5fea-105">管理対象ディスクのサイズ。</span><span class="sxs-lookup"><span data-stu-id="f5fea-105">The size of the managed disk.</span></span></param>
        <param name="lun"><span data-ttu-id="f5fea-106">ディスクの LUN です。</span><span class="sxs-lookup"><span data-stu-id="f5fea-106">The disk LUN.</span></span></param>
        <param name="cachingType"><span data-ttu-id="f5fea-107">キャッシュの型。</span><span class="sxs-lookup"><span data-stu-id="f5fea-107">The caching type.</span></span></param>
        <summary>
            <span data-ttu-id="f5fea-108">管理対象ディスクを指定した設定で暗黙的に作成する必要があることを指定します。</span><span class="sxs-lookup"><span data-stu-id="f5fea-108">Specifies that a managed disk needs to be created implicitly with the given settings.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="f5fea-109">仮想マシンの定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="f5fea-109">The next stage of virtual machine definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate WithNewDataDisk (int sizeInGB, int lun, Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType, Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes storageAccountType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate WithNewDataDisk(int32 sizeInGB, int32 lun, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes storageAccountType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedDataDisk.WithNewDataDisk(System.Int32,System.Int32,Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes,Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewDataDisk (sizeInGB As Integer, lun As Integer, cachingType As CachingTypes, storageAccountType As StorageAccountTypes) As IWithManagedCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewDataDisk : int * int * Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes * Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate" Usage="iWithManagedDataDisk.WithNewDataDisk (sizeInGB, lun, cachingType, storageAccountType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sizeInGB" Type="System.Int32" />
        <Parameter Name="lun" Type="System.Int32" />
        <Parameter Name="cachingType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes" />
        <Parameter Name="storageAccountType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes" />
      </Parameters>
      <Docs>
        <param name="sizeInGB"><span data-ttu-id="f5fea-110">管理対象ディスクのサイズ。</span><span class="sxs-lookup"><span data-stu-id="f5fea-110">The size of the managed disk.</span></span></param>
        <param name="lun"><span data-ttu-id="f5fea-111">ディスクの LUN です。</span><span class="sxs-lookup"><span data-stu-id="f5fea-111">The disk LUN.</span></span></param>
        <param name="cachingType"><span data-ttu-id="f5fea-112">キャッシュの型。</span><span class="sxs-lookup"><span data-stu-id="f5fea-112">The caching type.</span></span></param>
        <param name="storageAccountType"><span data-ttu-id="f5fea-113">ストレージ アカウントの種類。</span><span class="sxs-lookup"><span data-stu-id="f5fea-113">The storage account type.</span></span></param>
        <summary>
            <span data-ttu-id="f5fea-114">管理対象ディスクを指定した設定で暗黙的に作成する必要があることを指定します。</span><span class="sxs-lookup"><span data-stu-id="f5fea-114">Specifies that a managed disk needs to be created implicitly with the given settings.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="f5fea-115">仮想マシンの定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="f5fea-115">The next stage of virtual machine definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewDataDiskFromImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate WithNewDataDiskFromImage (int imageLun);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate WithNewDataDiskFromImage(int32 imageLun) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedDataDisk.WithNewDataDiskFromImage(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewDataDiskFromImage (imageLun As Integer) As IWithManagedCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewDataDiskFromImage : int -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate" Usage="iWithManagedDataDisk.WithNewDataDiskFromImage imageLun" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="imageLun" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="imageLun"><span data-ttu-id="f5fea-116">ソース データのディスク イメージの LUN です。</span><span class="sxs-lookup"><span data-stu-id="f5fea-116">The LUN of the source data disk image.</span></span></param>
        <summary>
            <span data-ttu-id="f5fea-117">データ ディスクを仮想マシンのイメージに、データ ディスクのイメージから作成することを指定します。</span><span class="sxs-lookup"><span data-stu-id="f5fea-117">Specifies the data disk to be created from the data disk image in the virtual machine image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="f5fea-118">仮想マシンの定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="f5fea-118">The next stage of virtual machine definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewDataDiskFromImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate WithNewDataDiskFromImage (int imageLun, int newSizeInGB, Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate WithNewDataDiskFromImage(int32 imageLun, int32 newSizeInGB, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedDataDisk.WithNewDataDiskFromImage(System.Int32,System.Int32,Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewDataDiskFromImage (imageLun As Integer, newSizeInGB As Integer, cachingType As CachingTypes) As IWithManagedCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewDataDiskFromImage : int * int * Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate" Usage="iWithManagedDataDisk.WithNewDataDiskFromImage (imageLun, newSizeInGB, cachingType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="imageLun" Type="System.Int32" />
        <Parameter Name="newSizeInGB" Type="System.Int32" />
        <Parameter Name="cachingType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes" />
      </Parameters>
      <Docs>
        <param name="imageLun"><span data-ttu-id="f5fea-119">ソース データのディスク イメージの LUN です。</span><span class="sxs-lookup"><span data-stu-id="f5fea-119">The LUN of the source data disk image.</span></span></param>
        <param name="newSizeInGB"><span data-ttu-id="f5fea-120">データ ディスク イメージで指定された既定のサイズをオーバーライドする新しいサイズ。</span><span class="sxs-lookup"><span data-stu-id="f5fea-120">The new size that overrides the default size specified in the data disk image.</span></span></param>
        <param name="cachingType"><span data-ttu-id="f5fea-121">キャッシュの型。</span><span class="sxs-lookup"><span data-stu-id="f5fea-121">The caching type.</span></span></param>
        <summary>
            <span data-ttu-id="f5fea-122">データ ディスクを仮想マシンのイメージに、データ ディスクのイメージから作成することを指定します。</span><span class="sxs-lookup"><span data-stu-id="f5fea-122">Specifies the data disk to be created from the data disk image in the virtual machine image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="f5fea-123">仮想マシンの定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="f5fea-123">The next stage of virtual machine definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewDataDiskFromImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate WithNewDataDiskFromImage (int imageLun, int newSizeInGB, Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType, Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes storageAccountType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate WithNewDataDiskFromImage(int32 imageLun, int32 newSizeInGB, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes storageAccountType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedDataDisk.WithNewDataDiskFromImage(System.Int32,System.Int32,Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes,Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewDataDiskFromImage (imageLun As Integer, newSizeInGB As Integer, cachingType As CachingTypes, storageAccountType As StorageAccountTypes) As IWithManagedCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewDataDiskFromImage : int * int * Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes * Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate" Usage="iWithManagedDataDisk.WithNewDataDiskFromImage (imageLun, newSizeInGB, cachingType, storageAccountType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="imageLun" Type="System.Int32" />
        <Parameter Name="newSizeInGB" Type="System.Int32" />
        <Parameter Name="cachingType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes" />
        <Parameter Name="storageAccountType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes" />
      </Parameters>
      <Docs>
        <param name="imageLun"><span data-ttu-id="f5fea-124">ソース データのディスク イメージの LUN です。</span><span class="sxs-lookup"><span data-stu-id="f5fea-124">The LUN of the source data disk image.</span></span></param>
        <param name="newSizeInGB"><span data-ttu-id="f5fea-125">データ ディスク イメージで指定された既定のサイズをオーバーライドする新しいサイズ。</span><span class="sxs-lookup"><span data-stu-id="f5fea-125">The new size that overrides the default size specified in the data disk image.</span></span></param>
        <param name="cachingType"><span data-ttu-id="f5fea-126">キャッシュの型。</span><span class="sxs-lookup"><span data-stu-id="f5fea-126">The caching type.</span></span></param>
        <param name="storageAccountType"><span data-ttu-id="f5fea-127">ストレージ アカウントの種類。</span><span class="sxs-lookup"><span data-stu-id="f5fea-127">The storage account type.</span></span></param>
        <summary>
            <span data-ttu-id="f5fea-128">データ ディスクを仮想マシンのイメージに、データ ディスクのイメージから作成することを指定します。</span><span class="sxs-lookup"><span data-stu-id="f5fea-128">Specifies the data disk to be created from the data disk image in the virtual machine image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="f5fea-129">仮想マシンの定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="f5fea-129">The next stage of virtual machine definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>