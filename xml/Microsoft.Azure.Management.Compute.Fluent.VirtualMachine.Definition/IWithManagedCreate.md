<Type Name="IWithManagedCreate" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate">
  <TypeSignature Language="C#" Value="public interface IWithManagedCreate : Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithAvailabilityZone, Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate, Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedDataDisk, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithManagedCreate implements class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithAvailabilitySet, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithAvailabilityZone, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithBootDiagnostics, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithExtension, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedDataDisk, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedServiceIdentity, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOSDiskSettings, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPlan, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithSecondaryNetworkInterface, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithStorageAccount, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithVMSize, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags`1&lt;class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithManagedCreate&#xA;Implements IBeta, ICreatable(Of IVirtualMachine), IDefinitionWithTags(Of IWithCreate), IWithAvailabilityZone, IWithCreate, IWithManagedDataDisk" />
  <TypeSignature Language="F#" Value="type IWithManagedCreate = interface&#xA;    interface IWithManagedDataDisk&#xA;    interface IWithAvailabilityZone&#xA;    interface IBeta&#xA;    interface IWithCreate&#xA;    interface ICreatable&lt;IVirtualMachine&gt;&#xA;    interface IIndexable&#xA;    interface IDefinitionWithTags&lt;IWithCreate&gt;&#xA;    interface IWithOSDiskSettings&#xA;    interface IWithVMSize&#xA;    interface IWithStorageAccount&#xA;    interface IWithAvailabilitySet&#xA;    interface IWithSecondaryNetworkInterface&#xA;    interface IWithExtension&#xA;    interface IWithPlan&#xA;    interface IWithBootDiagnostics&#xA;    interface IWithManagedServiceIdentity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithAvailabilityZone</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedDataDisk</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="4eb40-101">含むすべての最低限必要な入力を作成して、オプションで、VM の定義のステージでは、データ ディスク固有の設定を指定するを管理します。</span><span class="sxs-lookup"><span data-stu-id="4eb40-101">The stage of the definition which contains all the minimum required inputs for the VM to be created and optionally allow managed data disks specific settings to be specified.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithDataDiskDefaultCachingType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithDataDiskDefaultCachingType (Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithDataDiskDefaultCachingType(valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate.WithDataDiskDefaultCachingType(Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDataDiskDefaultCachingType (cachingType As CachingTypes) As IWithManagedCreate" />
      <MemberSignature Language="F#" Value="abstract member WithDataDiskDefaultCachingType : Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate" Usage="iWithManagedCreate.WithDataDiskDefaultCachingType cachingType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cachingType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes" />
      </Parameters>
      <Docs>
        <param name="cachingType"><span data-ttu-id="4eb40-102">キャッシュの型。</span><span class="sxs-lookup"><span data-stu-id="4eb40-102">A caching type.</span></span></param>
        <summary>
            <span data-ttu-id="4eb40-103">既定の管理対象のデータ ディスクの種類のキャッシュを指定します。</span><span class="sxs-lookup"><span data-stu-id="4eb40-103">Specifies the default caching type for the managed data disks.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="4eb40-104">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="4eb40-104">The next stage of teh definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithDataDiskDefaultStorageAccountType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithDataDiskDefaultStorageAccountType (Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes storageAccountType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithDataDiskDefaultStorageAccountType(valuetype Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes storageAccountType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate.WithDataDiskDefaultStorageAccountType(Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDataDiskDefaultStorageAccountType (storageAccountType As StorageAccountTypes) As IWithManagedCreate" />
      <MemberSignature Language="F#" Value="abstract member WithDataDiskDefaultStorageAccountType : Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate" Usage="iWithManagedCreate.WithDataDiskDefaultStorageAccountType storageAccountType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="storageAccountType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes" />
      </Parameters>
      <Docs>
        <param name="storageAccountType"><span data-ttu-id="4eb40-105">ストレージ アカウントの種類。</span><span class="sxs-lookup"><span data-stu-id="4eb40-105">A storage account type.</span></span></param>
        <summary>
            <span data-ttu-id="4eb40-106">既定のキャッシュ ディスクの管理対象のデータ型を指定します。</span><span class="sxs-lookup"><span data-stu-id="4eb40-106">Specifies the default caching type for managed data disks.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="4eb40-107">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="4eb40-107">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithOSDiskStorageAccountType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithOSDiskStorageAccountType (Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes accountType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithOSDiskStorageAccountType(valuetype Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes accountType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate.WithOSDiskStorageAccountType(Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithOSDiskStorageAccountType (accountType As StorageAccountTypes) As IWithManagedCreate" />
      <MemberSignature Language="F#" Value="abstract member WithOSDiskStorageAccountType : Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate" Usage="iWithManagedCreate.WithOSDiskStorageAccountType accountType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes" />
      </Parameters>
      <Docs>
        <param name="accountType"><span data-ttu-id="4eb40-108">ストレージ アカウントの種類。</span><span class="sxs-lookup"><span data-stu-id="4eb40-108">Storage account type.</span></span></param>
        <summary>
            <span data-ttu-id="4eb40-109">管理対象の OS ディスクのストレージ アカウントの種類を指定します。</span><span class="sxs-lookup"><span data-stu-id="4eb40-109">Specifies the storage account type for the managed OS disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="4eb40-110">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="4eb40-110">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>