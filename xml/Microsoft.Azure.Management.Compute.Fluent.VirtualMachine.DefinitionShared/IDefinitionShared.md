<Type Name="IDefinitionShared" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.DefinitionShared.IDefinitionShared">
  <TypeSignature Language="C#" Value="public interface IDefinitionShared : Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IBlank, Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate, Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithGroup, Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithNetwork, Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS, Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPrivateIP, Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPublicIPAddress, Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithSubnet, Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithCreatableResourceGroup&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithNetwork&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithExistingResourceGroup&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithNetwork&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithGroup&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithNetwork&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithNewResourceGroup&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithNetwork&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithRegion&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithGroup&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDefinitionShared implements class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IBlank, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithAvailabilitySet, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithBootDiagnostics, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithExtension, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithGroup, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedServiceIdentity, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithNetwork, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOSDiskSettings, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPlan, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPrimaryNetworkInterface, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPrivateIP, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPublicIPAddress, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithSecondaryNetworkInterface, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithStorageAccount, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithSubnet, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithVMSize, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithCreatableResourceGroup`1&lt;class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithNetwork&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithExistingResourceGroup`1&lt;class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithNetwork&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithGroup`1&lt;class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithNetwork&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithNewResourceGroup`1&lt;class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithNetwork&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithRegion`1&lt;class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithGroup&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags`1&lt;class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.DefinitionShared.IDefinitionShared" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDefinitionShared&#xA;Implements IBeta, IBlank, ICreatable(Of IVirtualMachine), IDefinitionWithRegion(Of IWithGroup), IDefinitionWithTags(Of IWithCreate), IWithCreatableResourceGroup(Of IWithNetwork), IWithCreate, IWithExistingResourceGroup(Of IWithNetwork), IWithGroup, IWithGroup(Of IWithNetwork), IWithNetwork, IWithNewResourceGroup(Of IWithNetwork), IWithOS, IWithPrivateIP, IWithPublicIPAddress, IWithSubnet" />
  <TypeSignature Language="F#" Value="type IDefinitionShared = interface&#xA;    interface IBlank&#xA;    interface IDefinitionWithRegion&lt;IWithGroup&gt;&#xA;    interface IWithGroup&#xA;    interface IWithGroup&lt;IWithNetwork&gt;&#xA;    interface IWithExistingResourceGroup&lt;IWithNetwork&gt;&#xA;    interface IWithNewResourceGroup&lt;IWithNetwork&gt;&#xA;    interface IWithCreatableResourceGroup&lt;IWithNetwork&gt;&#xA;    interface IWithNetwork&#xA;    interface IWithPrimaryNetworkInterface&#xA;    interface IWithSubnet&#xA;    interface IWithPrivateIP&#xA;    interface IWithPublicIPAddress&#xA;    interface IWithOS&#xA;    interface IWithCreate&#xA;    interface ICreatable&lt;IVirtualMachine&gt;&#xA;    interface IIndexable&#xA;    interface IDefinitionWithTags&lt;IWithCreate&gt;&#xA;    interface IWithOSDiskSettings&#xA;    interface IWithVMSize&#xA;    interface IWithStorageAccount&#xA;    interface IWithAvailabilitySet&#xA;    interface IWithSecondaryNetworkInterface&#xA;    interface IWithExtension&#xA;    interface IWithPlan&#xA;    interface IWithBootDiagnostics&#xA;    interface IWithManagedServiceIdentity&#xA;    interface IBeta" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IBlank</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithGroup</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithNetwork</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPrivateIP</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPublicIPAddress</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithSubnet</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithCreatableResourceGroup&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithNetwork&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithExistingResourceGroup&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithNetwork&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithGroup&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithNetwork&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithNewResourceGroup&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithNetwork&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithRegion&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithGroup&gt;</InterfaceName>
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
            <span data-ttu-id="8eabc-101">仮想マシンのスケールでは、ベースのバーチャル マシンのマネージ コードとアンマネージの定義の間で共有のステージを設定します。</span><span class="sxs-lookup"><span data-stu-id="8eabc-101">The virtual machine scale set stages shared between managed and unmanaged based virtual machine definitions.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members />
</Type>