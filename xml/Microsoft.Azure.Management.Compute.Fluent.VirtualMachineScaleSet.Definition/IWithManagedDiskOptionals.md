<Type Name="IWithManagedDiskOptionals" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedDiskOptionals">
  <TypeSignature Language="C#" Value="public interface IWithManagedDiskOptionals" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithManagedDiskOptionals" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedDiskOptionals" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithManagedDiskOptionals" />
  <TypeSignature Language="F#" Value="type IWithManagedDiskOptionals = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="88373-101">管理されるディスクにのみ適用する optionals です。</span><span class="sxs-lookup"><span data-stu-id="88373-101">The optionals applicable only for managed disks.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithDataDiskDefaultCachingType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate WithDataDiskDefaultCachingType (Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate WithDataDiskDefaultCachingType(valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedDiskOptionals.WithDataDiskDefaultCachingType(Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDataDiskDefaultCachingType (cachingType As CachingTypes) As IWithManagedCreate" />
      <MemberSignature Language="F#" Value="abstract member WithDataDiskDefaultCachingType : Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate" Usage="iWithManagedDiskOptionals.WithDataDiskDefaultCachingType cachingType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cachingType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes" />
      </Parameters>
      <Docs>
        <param name="cachingType"><span data-ttu-id="88373-102">キャッシュの型。</span><span class="sxs-lookup"><span data-stu-id="88373-102">The caching type.</span></span></param>
        <summary>
            <span data-ttu-id="88373-103">既定の管理対象のデータ ディスクの種類のキャッシュを指定します。</span><span class="sxs-lookup"><span data-stu-id="88373-103">Specifies the default caching type for the managed data disks.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="88373-104">VM の作成可能な定義を表す段階です。</span><span class="sxs-lookup"><span data-stu-id="88373-104">The stage representing creatable VM definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithDataDiskDefaultStorageAccountType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate WithDataDiskDefaultStorageAccountType (Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes storageAccountType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate WithDataDiskDefaultStorageAccountType(valuetype Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes storageAccountType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedDiskOptionals.WithDataDiskDefaultStorageAccountType(Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDataDiskDefaultStorageAccountType (storageAccountType As StorageAccountTypes) As IWithManagedCreate" />
      <MemberSignature Language="F#" Value="abstract member WithDataDiskDefaultStorageAccountType : Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate" Usage="iWithManagedDiskOptionals.WithDataDiskDefaultStorageAccountType storageAccountType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="storageAccountType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes" />
      </Parameters>
      <Docs>
        <param name="storageAccountType"><span data-ttu-id="88373-105">ストレージ アカウントの種類。</span><span class="sxs-lookup"><span data-stu-id="88373-105">The storage account type.</span></span></param>
        <summary>
            <span data-ttu-id="88373-106">既定の管理対象のデータ ディスクの種類のキャッシュを指定します。</span><span class="sxs-lookup"><span data-stu-id="88373-106">Specifies the default caching type for the managed data disks.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="88373-107">VM の作成可能な定義を表す段階です。</span><span class="sxs-lookup"><span data-stu-id="88373-107">The stage representing creatable VM definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithOSDiskStorageAccountType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate WithOSDiskStorageAccountType (Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes accountType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate WithOSDiskStorageAccountType(valuetype Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes accountType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedDiskOptionals.WithOSDiskStorageAccountType(Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithOSDiskStorageAccountType (accountType As StorageAccountTypes) As IWithManagedCreate" />
      <MemberSignature Language="F#" Value="abstract member WithOSDiskStorageAccountType : Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate" Usage="iWithManagedDiskOptionals.WithOSDiskStorageAccountType accountType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes" />
      </Parameters>
      <Docs>
        <param name="accountType"><span data-ttu-id="88373-108">ストレージ アカウントの種類。</span><span class="sxs-lookup"><span data-stu-id="88373-108">The storage account type.</span></span></param>
        <summary>
            <span data-ttu-id="88373-109">管理対象の OS ディスクのストレージ アカウントの種類を指定します。</span><span class="sxs-lookup"><span data-stu-id="88373-109">Specifies the storage account type for managed OS disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="88373-110">VM の作成可能な定義を表す段階です。</span><span class="sxs-lookup"><span data-stu-id="88373-110">The stage representing creatable VM definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>