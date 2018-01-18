<Type Name="IWithManagedDataDisk" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithManagedDataDisk">
  <TypeSignature Language="C#" Value="public interface IWithManagedDataDisk" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithManagedDataDisk" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithManagedDataDisk" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithManagedDataDisk" />
  <TypeSignature Language="F#" Value="type IWithManagedDataDisk = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="680cc-101">管理対象のデータ ディスクを指定できるようにバーチャル マシンの更新の段階です。</span><span class="sxs-lookup"><span data-stu-id="680cc-101">The stage of a virtual machine update allowing to specify a managed data disk.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithExistingDataDisk (Microsoft.Azure.Management.Compute.Fluent.IDisk disk);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithExistingDataDisk(class Microsoft.Azure.Management.Compute.Fluent.IDisk disk) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithManagedDataDisk.WithExistingDataDisk(Microsoft.Azure.Management.Compute.Fluent.IDisk)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingDataDisk (disk As IDisk) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingDataDisk : Microsoft.Azure.Management.Compute.Fluent.IDisk -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate" Usage="iWithManagedDataDisk.WithExistingDataDisk disk" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disk" Type="Microsoft.Azure.Management.Compute.Fluent.IDisk" />
      </Parameters>
      <Docs>
        <param name="disk"><span data-ttu-id="680cc-102">管理対象のディスク。</span><span class="sxs-lookup"><span data-stu-id="680cc-102">A managed disk.</span></span></param>
        <summary>
            <span data-ttu-id="680cc-103">既存のソース管理されているディスクを VM に関連付けます。</span><span class="sxs-lookup"><span data-stu-id="680cc-103">Associates an existing source managed disk with the VM.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="680cc-104">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="680cc-104">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithExistingDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithExistingDataDisk (Microsoft.Azure.Management.Compute.Fluent.IDisk disk, int lun, Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithExistingDataDisk(class Microsoft.Azure.Management.Compute.Fluent.IDisk disk, int32 lun, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithManagedDataDisk.WithExistingDataDisk(Microsoft.Azure.Management.Compute.Fluent.IDisk,System.Int32,Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingDataDisk (disk As IDisk, lun As Integer, cachingType As CachingTypes) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingDataDisk : Microsoft.Azure.Management.Compute.Fluent.IDisk * int * Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate" Usage="iWithManagedDataDisk.WithExistingDataDisk (disk, lun, cachingType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disk" Type="Microsoft.Azure.Management.Compute.Fluent.IDisk" />
        <Parameter Name="lun" Type="System.Int32" />
        <Parameter Name="cachingType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes" />
      </Parameters>
      <Docs>
        <param name="disk"><span data-ttu-id="680cc-105">管理対象ディスク。</span><span class="sxs-lookup"><span data-stu-id="680cc-105">The managed disk.</span></span></param>
        <param name="lun"><span data-ttu-id="680cc-106">ディスクの LUN です。</span><span class="sxs-lookup"><span data-stu-id="680cc-106">The disk LUN.</span></span></param>
        <param name="cachingType"><span data-ttu-id="680cc-107">キャッシュの型。</span><span class="sxs-lookup"><span data-stu-id="680cc-107">A caching type.</span></span></param>
        <summary>
            <span data-ttu-id="680cc-108">既存のソース管理されているディスクと設定を指定します。</span><span class="sxs-lookup"><span data-stu-id="680cc-108">Specifies an existing source managed disk and settings.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="680cc-109">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="680cc-109">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithExistingDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithExistingDataDisk (Microsoft.Azure.Management.Compute.Fluent.IDisk disk, int newSizeInGB, int lun, Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithExistingDataDisk(class Microsoft.Azure.Management.Compute.Fluent.IDisk disk, int32 newSizeInGB, int32 lun, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithManagedDataDisk.WithExistingDataDisk(Microsoft.Azure.Management.Compute.Fluent.IDisk,System.Int32,System.Int32,Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingDataDisk (disk As IDisk, newSizeInGB As Integer, lun As Integer, cachingType As CachingTypes) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingDataDisk : Microsoft.Azure.Management.Compute.Fluent.IDisk * int * int * Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate" Usage="iWithManagedDataDisk.WithExistingDataDisk (disk, newSizeInGB, lun, cachingType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disk" Type="Microsoft.Azure.Management.Compute.Fluent.IDisk" />
        <Parameter Name="newSizeInGB" Type="System.Int32" />
        <Parameter Name="lun" Type="System.Int32" />
        <Parameter Name="cachingType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes" />
      </Parameters>
      <Docs>
        <param name="disk"><span data-ttu-id="680cc-110">管理対象のディスク。</span><span class="sxs-lookup"><span data-stu-id="680cc-110">A managed disk.</span></span></param>
        <param name="newSizeInGB"><span data-ttu-id="680cc-111">ディスク サイズ (GB) のサイズを変更します。</span><span class="sxs-lookup"><span data-stu-id="680cc-111">The disk resize size in GB.</span></span></param>
        <param name="lun"><span data-ttu-id="680cc-112">ディスクの LUN です。</span><span class="sxs-lookup"><span data-stu-id="680cc-112">The disk LUN.</span></span></param>
        <param name="cachingType"><span data-ttu-id="680cc-113">キャッシュの型。</span><span class="sxs-lookup"><span data-stu-id="680cc-113">A caching type.</span></span></param>
        <summary>
            <span data-ttu-id="680cc-114">既存のソース管理されているディスクと設定を指定します。</span><span class="sxs-lookup"><span data-stu-id="680cc-114">Specifies an existing source managed disk and settings.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="680cc-115">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="680cc-115">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithNewDataDisk (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Compute.Fluent.IDisk&gt; creatable);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithNewDataDisk(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IDisk&gt; creatable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithManagedDataDisk.WithNewDataDisk(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.Compute.Fluent.IDisk})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewDataDisk (creatable As ICreatable(Of IDisk)) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewDataDisk : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Compute.Fluent.IDisk&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate" Usage="iWithManagedDataDisk.WithNewDataDisk creatable" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="creatable" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Compute.Fluent.IDisk&gt;" />
      </Parameters>
      <Docs>
        <param name="creatable"><span data-ttu-id="680cc-116">作成可能なディスクの定義。</span><span class="sxs-lookup"><span data-stu-id="680cc-116">A creatable disk definition.</span></span></param>
        <summary>
            <span data-ttu-id="680cc-117">管理対象ディスクを特定の定義で明示的に作成して、データ ディスクとして仮想マシンに接続する必要があることを指定します。</span><span class="sxs-lookup"><span data-stu-id="680cc-117">Specifies that a managed disk needs to be created explicitly with the given definition and attached to the virtual machine as a data disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="680cc-118">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="680cc-118">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithNewDataDisk (int sizeInGB);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithNewDataDisk(int32 sizeInGB) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithManagedDataDisk.WithNewDataDisk(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewDataDisk (sizeInGB As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewDataDisk : int -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate" Usage="iWithManagedDataDisk.WithNewDataDisk sizeInGB" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sizeInGB" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="sizeInGB"><span data-ttu-id="680cc-119">管理対象ディスクのサイズ。</span><span class="sxs-lookup"><span data-stu-id="680cc-119">The size of the managed disk.</span></span></param>
        <summary>
            <span data-ttu-id="680cc-120">管理対象ディスクを特定のサイズで暗黙的に作成する必要があることを指定します。</span><span class="sxs-lookup"><span data-stu-id="680cc-120">Specifies that a managed disk needs to be created implicitly with the given size.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="680cc-121">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="680cc-121">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithNewDataDisk (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Compute.Fluent.IDisk&gt; creatable, int lun, Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithNewDataDisk(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IDisk&gt; creatable, int32 lun, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithManagedDataDisk.WithNewDataDisk(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.Compute.Fluent.IDisk},System.Int32,Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewDataDisk (creatable As ICreatable(Of IDisk), lun As Integer, cachingType As CachingTypes) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewDataDisk : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Compute.Fluent.IDisk&gt; * int * Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate" Usage="iWithManagedDataDisk.WithNewDataDisk (creatable, lun, cachingType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="creatable" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Compute.Fluent.IDisk&gt;" />
        <Parameter Name="lun" Type="System.Int32" />
        <Parameter Name="cachingType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes" />
      </Parameters>
      <Docs>
        <param name="creatable"><span data-ttu-id="680cc-122">作成可能なディスクの定義。</span><span class="sxs-lookup"><span data-stu-id="680cc-122">A creatable disk definition.</span></span></param>
        <param name="lun"><span data-ttu-id="680cc-123">データ ディスク LUN。</span><span class="sxs-lookup"><span data-stu-id="680cc-123">The data disk LUN.</span></span></param>
        <param name="cachingType"><span data-ttu-id="680cc-124">データ ディスク型をキャッシュします。</span><span class="sxs-lookup"><span data-stu-id="680cc-124">A data disk caching type.</span></span></param>
        <summary>
            <span data-ttu-id="680cc-125">管理対象ディスクを特定の定義で明示的に作成して、データ ディスクとして仮想マシンに接続する必要があることを指定します。</span><span class="sxs-lookup"><span data-stu-id="680cc-125">Specifies that a managed disk needs to be created explicitly with the given definition and attached to the virtual machine as a data disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="680cc-126">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="680cc-126">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithNewDataDisk (int sizeInGB, int lun, Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithNewDataDisk(int32 sizeInGB, int32 lun, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithManagedDataDisk.WithNewDataDisk(System.Int32,System.Int32,Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewDataDisk (sizeInGB As Integer, lun As Integer, cachingType As CachingTypes) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewDataDisk : int * int * Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate" Usage="iWithManagedDataDisk.WithNewDataDisk (sizeInGB, lun, cachingType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sizeInGB" Type="System.Int32" />
        <Parameter Name="lun" Type="System.Int32" />
        <Parameter Name="cachingType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes" />
      </Parameters>
      <Docs>
        <param name="sizeInGB"><span data-ttu-id="680cc-127">管理対象ディスクのサイズ。</span><span class="sxs-lookup"><span data-stu-id="680cc-127">The size of the managed disk.</span></span></param>
        <param name="lun"><span data-ttu-id="680cc-128">ディスクの LUN です。</span><span class="sxs-lookup"><span data-stu-id="680cc-128">The disk LUN.</span></span></param>
        <param name="cachingType"><span data-ttu-id="680cc-129">キャッシュの型。</span><span class="sxs-lookup"><span data-stu-id="680cc-129">A caching type.</span></span></param>
        <summary>
            <span data-ttu-id="680cc-130">管理対象ディスクを指定した設定で暗黙的に作成する必要があることを指定します。</span><span class="sxs-lookup"><span data-stu-id="680cc-130">Specifies that a managed disk needs to be created implicitly with the given settings.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="680cc-131">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="680cc-131">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithNewDataDisk (int sizeInGB, int lun, Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType, Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes storageAccountType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithNewDataDisk(int32 sizeInGB, int32 lun, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes storageAccountType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithManagedDataDisk.WithNewDataDisk(System.Int32,System.Int32,Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes,Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewDataDisk (sizeInGB As Integer, lun As Integer, cachingType As CachingTypes, storageAccountType As StorageAccountTypes) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewDataDisk : int * int * Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes * Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate" Usage="iWithManagedDataDisk.WithNewDataDisk (sizeInGB, lun, cachingType, storageAccountType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sizeInGB" Type="System.Int32" />
        <Parameter Name="lun" Type="System.Int32" />
        <Parameter Name="cachingType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes" />
        <Parameter Name="storageAccountType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes" />
      </Parameters>
      <Docs>
        <param name="sizeInGB"><span data-ttu-id="680cc-132">管理対象ディスクのサイズ。</span><span class="sxs-lookup"><span data-stu-id="680cc-132">The size of the managed disk.</span></span></param>
        <param name="lun"><span data-ttu-id="680cc-133">ディスクの LUN です。</span><span class="sxs-lookup"><span data-stu-id="680cc-133">The disk LUN.</span></span></param>
        <param name="cachingType"><span data-ttu-id="680cc-134">キャッシュの型。</span><span class="sxs-lookup"><span data-stu-id="680cc-134">A caching type.</span></span></param>
        <param name="storageAccountType"><span data-ttu-id="680cc-135">ストレージ アカウントの種類。</span><span class="sxs-lookup"><span data-stu-id="680cc-135">A storage account type.</span></span></param>
        <summary>
            <span data-ttu-id="680cc-136">管理対象ディスクを指定した設定で暗黙的に作成する必要があることを指定します。</span><span class="sxs-lookup"><span data-stu-id="680cc-136">Specifies that a managed disk needs to be created implicitly with the given settings.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="680cc-137">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="680cc-137">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithoutDataDisk (int lun);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithoutDataDisk(int32 lun) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithManagedDataDisk.WithoutDataDisk(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutDataDisk (lun As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutDataDisk : int -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate" Usage="iWithManagedDataDisk.WithoutDataDisk lun" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lun" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="lun"><span data-ttu-id="680cc-138">ディスクの LUN です。</span><span class="sxs-lookup"><span data-stu-id="680cc-138">The disk LUN.</span></span></param>
        <summary>
            <span data-ttu-id="680cc-139">バーチャル マシンから指定された LUN に管理されているデータ ディスクをデタッチします。</span><span class="sxs-lookup"><span data-stu-id="680cc-139">Detaches a managed data disk with the given LUN from the virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="680cc-140">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="680cc-140">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>