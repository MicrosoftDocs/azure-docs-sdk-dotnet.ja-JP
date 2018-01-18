<Type Name="IWithDiskCaching" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Update.IWithDiskCaching">
  <TypeSignature Language="C#" Value="public interface IWithDiskCaching" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDiskCaching" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Update.IWithDiskCaching" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDiskCaching" />
  <TypeSignature Language="F#" Value="type IWithDiskCaching = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b758c-101">仮想マシン データ ディスクの更新を許可する型のキャッシュ ディスクの設定の段階です。</span><span class="sxs-lookup"><span data-stu-id="b758c-101">The stage of the virtual machine data disk update allowing to set the disk caching type.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithCaching">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Update.IUpdate WithCaching (Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Update.IUpdate WithCaching(valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Update.IWithDiskCaching.WithCaching(Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithCaching (cachingType As CachingTypes) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithCaching : Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Update.IUpdate" Usage="iWithDiskCaching.WithCaching cachingType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cachingType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes" />
      </Parameters>
      <Docs>
        <param name="cachingType"><span data-ttu-id="b758c-102">型のキャッシュ ディスク。</span><span class="sxs-lookup"><span data-stu-id="b758c-102">The disk caching type.</span></span> <span data-ttu-id="b758c-103">使用可能な値が含まれます。 'None'、'ReadOnly'、'ReadWrite' です。</span><span class="sxs-lookup"><span data-stu-id="b758c-103">Possible values include: 'None', 'ReadOnly', 'ReadWrite'.</span></span></param>
        <summary>
            <span data-ttu-id="b758c-104">データ ディスクの新しいキャッシュの種類を指定します。</span><span class="sxs-lookup"><span data-stu-id="b758c-104">Specifies the new caching type for the data disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="b758c-105">データ ディスクの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="b758c-105">The next stage of data disk update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>