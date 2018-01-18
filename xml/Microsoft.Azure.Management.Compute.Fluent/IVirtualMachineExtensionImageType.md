<Type Name="IVirtualMachineExtensionImageType" FullName="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImageType">
  <TypeSignature Language="C#" Value="public interface IVirtualMachineExtensionImageType : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionImageInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IVirtualMachineExtensionImageType implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionImageInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImageType" />
  <TypeSignature Language="VB.NET" Value="Public Interface IVirtualMachineExtensionImageType&#xA;Implements IHasInner(Of VirtualMachineExtensionImageInner), IHasName" />
  <TypeSignature Language="F#" Value="type IVirtualMachineExtensionImageType = interface&#xA;    interface IHasInner&lt;VirtualMachineExtensionImageInner&gt;&#xA;    interface IHasName" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionImageInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="36326-101">Azure の仮想マシン拡張機能のイメージの種類の変更できないクライアント側表現。</span><span class="sxs-lookup"><span data-stu-id="36326-101">An immutable client-side representation of an Azure virtual machine extension image type.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImageType.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImageType.Id" />
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
            <span data-ttu-id="36326-102">仮想マシン拡張機能のイメージの種類のリソース ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="36326-102">Gets the resource ID of the virtual machine extension image type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Publisher">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinePublisher Publisher { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinePublisher Publisher" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImageType.Publisher" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Publisher As IVirtualMachinePublisher" />
      <MemberSignature Language="F#" Value="member this.Publisher : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinePublisher" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImageType.Publisher" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinePublisher</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36326-103">この仮想マシン拡張機能のイメージの種類の発行者を取得します。</span><span class="sxs-lookup"><span data-stu-id="36326-103">Gets the publisher of this virtual machine extension image type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegionName">
      <MemberSignature Language="C#" Value="public string RegionName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RegionName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImageType.RegionName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RegionName As String" />
      <MemberSignature Language="F#" Value="member this.RegionName : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImageType.RegionName" />
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
            <span data-ttu-id="36326-104">どの仮想マシン イメージの種類の拡張機能が利用可能な領域を取得します。</span><span class="sxs-lookup"><span data-stu-id="36326-104">Gets the region in which virtual machine extension image type is available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Versions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImageVersions Versions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImageVersions Versions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImageType.Versions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Versions As IVirtualMachineExtensionImageVersions" />
      <MemberSignature Language="F#" Value="member this.Versions : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImageVersions" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImageType.Versions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImageVersions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36326-105">仮想マシン イメージの拡張機能のバージョンがこの種類で利用できるを取得します。</span><span class="sxs-lookup"><span data-stu-id="36326-105">Gets Virtual machine image extension versions available in this type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>