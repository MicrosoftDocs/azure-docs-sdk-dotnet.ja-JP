<Type Name="IWithOSDiskSettings" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithOSDiskSettings">
  <TypeSignature Language="C#" Value="public interface IWithOSDiskSettings" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithOSDiskSettings" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithOSDiskSettings" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithOSDiskSettings" />
  <TypeSignature Language="F#" Value="type IWithOSDiskSettings = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="105e5-101">イメージ定義できるようにする、イメージの OS ディスクのイメージから作成時に、OS ディスクの構成を指定の段階です。</span><span class="sxs-lookup"><span data-stu-id="105e5-101">The stage of an image definition allowing to specify configurations for the OS disk when it is created from the image's  OS disk image.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithOSDiskCaching">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithOSDiskCaching (Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithOSDiskCaching(valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithOSDiskSettings.WithOSDiskCaching(Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithOSDiskCaching (cachingType As CachingTypes) As IWithCreateAndDataDiskImageOSDiskSettings" />
      <MemberSignature Language="F#" Value="abstract member WithOSDiskCaching : Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings" Usage="iWithOSDiskSettings.WithOSDiskCaching cachingType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cachingType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes" />
      </Parameters>
      <Docs>
        <param name="cachingType"><span data-ttu-id="105e5-102">型のキャッシュ ディスク。</span><span class="sxs-lookup"><span data-stu-id="105e5-102">The disk caching type.</span></span></param>
        <summary>
            <span data-ttu-id="105e5-103">OS ディスクのキャッシュの種類を指定します。</span><span class="sxs-lookup"><span data-stu-id="105e5-103">Specifies the caching type for OS disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="105e5-104">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="105e5-104">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithOSDiskSizeInGB">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithOSDiskSizeInGB (int diskSizeGB);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithOSDiskSizeInGB(int32 diskSizeGB) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithOSDiskSettings.WithOSDiskSizeInGB(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithOSDiskSizeInGB (diskSizeGB As Integer) As IWithCreateAndDataDiskImageOSDiskSettings" />
      <MemberSignature Language="F#" Value="abstract member WithOSDiskSizeInGB : int -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings" Usage="iWithOSDiskSettings.WithOSDiskSizeInGB diskSizeGB" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="diskSizeGB" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="diskSizeGB"><span data-ttu-id="105e5-105">GB のディスク サイズです。</span><span class="sxs-lookup"><span data-stu-id="105e5-105">The disk size in GB.</span></span></param>
        <summary>
            <span data-ttu-id="105e5-106">OS ディスクの GB のサイズを指定します。</span><span class="sxs-lookup"><span data-stu-id="105e5-106">Specifies the size in GB for OS disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="105e5-107">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="105e5-107">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>