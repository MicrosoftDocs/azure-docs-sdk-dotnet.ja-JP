<Type Name="IVirtualMachineCustomImage" FullName="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineCustomImage">
  <TypeSignature Language="C#" Value="public interface IVirtualMachineCustomImage : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.Compute.Fluent.IComputeManager,Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Compute.Fluent.IComputeManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineCustomImage&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IVirtualMachineCustomImage implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource`2&lt;class Microsoft.Azure.Management.Compute.Fluent.IComputeManager, class Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IComputeManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineCustomImage&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineCustomImage" />
  <TypeSignature Language="VB.NET" Value="Public Interface IVirtualMachineCustomImage&#xA;Implements IGroupableResource(Of IComputeManager, ImageInner), IHasInner(Of ImageInner), IHasManager(Of IComputeManager), IRefreshable(Of IVirtualMachineCustomImage)" />
  <TypeSignature Language="F#" Value="type IVirtualMachineCustomImage = interface&#xA;    interface IGroupableResource&lt;IComputeManager, ImageInner&gt;&#xA;    interface IResource&#xA;    interface IIndexable&#xA;    interface IHasId&#xA;    interface IHasName&#xA;    interface IHasResourceGroup&#xA;    interface IHasManager&lt;IComputeManager&gt;&#xA;    interface IHasInner&lt;ImageInner&gt;&#xA;    interface IRefreshable&lt;IVirtualMachineCustomImage&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.Compute.Fluent.IComputeManager,Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Compute.Fluent.IComputeManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineCustomImage&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="25983-101">Azure の仮想マシンのカスタム イメージの変更できないクライアント側表現。</span><span class="sxs-lookup"><span data-stu-id="25983-101">An immutable client-side representation of an Azure virtual machine custom image.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DataDiskImages">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;int,Microsoft.Azure.Management.Compute.Fluent.Models.ImageDataDisk&gt; DataDiskImages { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;int32, class Microsoft.Azure.Management.Compute.Fluent.Models.ImageDataDisk&gt; DataDiskImages" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineCustomImage.DataDiskImages" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DataDiskImages As IReadOnlyDictionary(Of Integer, ImageDataDisk)" />
      <MemberSignature Language="F#" Value="member this.DataDiskImages : System.Collections.Generic.IReadOnlyDictionary&lt;int, Microsoft.Azure.Management.Compute.Fluent.Models.ImageDataDisk&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineCustomImage.DataDiskImages" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.Int32,Microsoft.Azure.Management.Compute.Fluent.Models.ImageDataDisk&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="25983-102">ディスクの LUN でインデックス付けされた、このイメージにデータ ディスク イメージを取得します。</span><span class="sxs-lookup"><span data-stu-id="25983-102">Gets data disk images in this image, indexed by the disk LUN.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsCreatedFromVirtualMachine">
      <MemberSignature Language="C#" Value="public bool IsCreatedFromVirtualMachine { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsCreatedFromVirtualMachine" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineCustomImage.IsCreatedFromVirtualMachine" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsCreatedFromVirtualMachine As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsCreatedFromVirtualMachine : bool" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineCustomImage.IsCreatedFromVirtualMachine" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="25983-103">このイメージは、仮想マシンのキャプチャによって作成された場合は true を取得します。</span><span class="sxs-lookup"><span data-stu-id="25983-103">Gets true if this image was created by capturing a virtual machine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OSDiskImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.ImageOSDisk OSDiskImage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.ImageOSDisk OSDiskImage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineCustomImage.OSDiskImage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OSDiskImage As ImageOSDisk" />
      <MemberSignature Language="F#" Value="member this.OSDiskImage : Microsoft.Azure.Management.Compute.Fluent.Models.ImageOSDisk" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineCustomImage.OSDiskImage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.ImageOSDisk</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="25983-104">このイメージにオペレーティング システムのディスク イメージを取得します。</span><span class="sxs-lookup"><span data-stu-id="25983-104">Gets operating system disk image in this image.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceVirtualMachineId">
      <MemberSignature Language="C#" Value="public string SourceVirtualMachineId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceVirtualMachineId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineCustomImage.SourceVirtualMachineId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SourceVirtualMachineId As String" />
      <MemberSignature Language="F#" Value="member this.SourceVirtualMachineId : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineCustomImage.SourceVirtualMachineId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="25983-105">このイメージは、その仮想マシンをキャプチャして作成した場合は、仮想マシンの ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="25983-105">Gets ID of the virtual machine if this image was created by capturing that virtual machine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>