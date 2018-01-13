<Type Name="IVirtualMachineSku" FullName="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineSku">
  <TypeSignature Language="C#" Value="public interface IVirtualMachineSku : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IVirtualMachineSku implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineSku" />
  <TypeSignature Language="VB.NET" Value="Public Interface IVirtualMachineSku&#xA;Implements IHasName" />
  <TypeSignature Language="F#" Value="type IVirtualMachineSku = interface&#xA;    interface IHasName" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="374cb-101">仮想マシン イメージの SKU を表します。</span><span class="sxs-lookup"><span data-stu-id="374cb-101">Represents a virtual machine image SKU.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Images">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesInSku Images { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesInSku Images" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineSku.Images" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Images As IVirtualMachineImagesInSku" />
      <MemberSignature Language="F#" Value="member this.Images : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesInSku" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineSku.Images" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesInSku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="374cb-102">SKU では、仮想マシン イメージを取得します。</span><span class="sxs-lookup"><span data-stu-id="374cb-102">Gets virtual machine images in the SKU.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Offer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineOffer Offer { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineOffer Offer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineSku.Offer" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Offer As IVirtualMachineOffer" />
      <MemberSignature Language="F#" Value="member this.Offer : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineOffer" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineSku.Offer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineOffer</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="374cb-103">この SKU が所属する仮想マシンのオファー名を取得します。</span><span class="sxs-lookup"><span data-stu-id="374cb-103">Gets the virtual machine offer name that this SKU belongs to.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Publisher">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinePublisher Publisher { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinePublisher Publisher" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineSku.Publisher" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Publisher As IVirtualMachinePublisher" />
      <MemberSignature Language="F#" Value="member this.Publisher : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinePublisher" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineSku.Publisher" />
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
            <span data-ttu-id="374cb-104">この仮想マシン イメージ プラン SKU の発行元を取得します。</span><span class="sxs-lookup"><span data-stu-id="374cb-104">Gets the publisher of this virtual machine image offer SKU.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Region">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region Region { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region Region" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineSku.Region" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Region As Region" />
      <MemberSignature Language="F#" Value="member this.Region : Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineSku.Region" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="374cb-105">ここでこのバーチャル マシンのイメージを提供 SKU が利用可能な領域を取得します。</span><span class="sxs-lookup"><span data-stu-id="374cb-105">Gets the region where this virtual machine image offer SKU is available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>