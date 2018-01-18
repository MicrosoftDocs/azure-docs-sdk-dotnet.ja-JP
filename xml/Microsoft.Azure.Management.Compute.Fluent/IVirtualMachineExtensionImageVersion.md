<Type Name="IVirtualMachineExtensionImageVersion" FullName="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImageVersion">
  <TypeSignature Language="C#" Value="public interface IVirtualMachineExtensionImageVersion : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionImageInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IVirtualMachineExtensionImageVersion implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionImageInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImageVersion" />
  <TypeSignature Language="VB.NET" Value="Public Interface IVirtualMachineExtensionImageVersion&#xA;Implements IHasInner(Of VirtualMachineExtensionImageInner), IHasName" />
  <TypeSignature Language="F#" Value="type IVirtualMachineExtensionImageVersion = interface&#xA;    interface IHasInner&lt;VirtualMachineExtensionImageInner&gt;&#xA;    interface IHasName" />
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
            <span data-ttu-id="b937a-101">Azure の仮想マシン拡張機能のイメージのバージョンの変更できないクライアント側表現。</span><span class="sxs-lookup"><span data-stu-id="b937a-101">An immutable client-side representation of an Azure virtual machine extension image version.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage GetImage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage GetImage() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImageVersion.GetImage" />
      <MemberSignature Language="VB.NET" Value="Public Function GetImage () As IVirtualMachineExtensionImage" />
      <MemberSignature Language="F#" Value="abstract member GetImage : unit -&gt; Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage" Usage="iVirtualMachineExtensionImageVersion.GetImage " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="b937a-102">仮想マシン拡張機能のイメージはこのバージョンを表します。</span><span class="sxs-lookup"><span data-stu-id="b937a-102">Virtual machine extension image this version represents.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="GetImageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage&gt; GetImageAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage&gt; GetImageAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImageVersion.GetImageAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetImageAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage&gt;" Usage="iVirtualMachineExtensionImageVersion.GetImageAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImageVersion.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImageVersion.Id" />
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
            <span data-ttu-id="b937a-103">拡張機能のイメージのバージョンのリソース ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="b937a-103">Gets the resource ID of the extension image version.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegionName">
      <MemberSignature Language="C#" Value="public string RegionName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RegionName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImageVersion.RegionName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RegionName As String" />
      <MemberSignature Language="F#" Value="member this.RegionName : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImageVersion.RegionName" />
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
            <span data-ttu-id="b937a-104">どの仮想マシン拡張機能のイメージのバージョンが利用可能な領域を取得します。</span><span class="sxs-lookup"><span data-stu-id="b937a-104">Gets the region in which virtual machine extension image version is available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImageType Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImageType Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImageVersion.Type" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Type As IVirtualMachineExtensionImageType" />
      <MemberSignature Language="F#" Value="member this.Type : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImageType" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImageVersion.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImageType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b937a-105">このバージョンが属する仮想マシン拡張イメージの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="b937a-105">Gets the virtual machine extension image type this version belongs to.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>