<Type Name="IWithDiskLun" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Update.IWithDiskLun">
  <TypeSignature Language="C#" Value="public interface IWithDiskLun" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDiskLun" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Update.IWithDiskLun" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDiskLun" />
  <TypeSignature Language="F#" Value="type IWithDiskLun = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0aa5e-101">仮想マシン データ ディスクの更新を許可するディスク LUN の設定の段階です。</span><span class="sxs-lookup"><span data-stu-id="0aa5e-101">The stage of the virtual machine data disk update allowing to set the disk LUN.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithLun">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Update.IUpdate WithLun (int lun);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Update.IUpdate WithLun(int32 lun) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Update.IWithDiskLun.WithLun(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithLun (lun As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithLun : int -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Update.IUpdate" Usage="iWithDiskLun.WithLun lun" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lun" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="lun"><span data-ttu-id="0aa5e-102">論理ユニットの数です。</span><span class="sxs-lookup"><span data-stu-id="0aa5e-102">The logical unit number.</span></span></param>
        <summary>
            <span data-ttu-id="0aa5e-103">データ ディスクの新しい論理ユニット番号を指定します。</span><span class="sxs-lookup"><span data-stu-id="0aa5e-103">Specifies the new logical unit number for the data disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="0aa5e-104">データ ディスクの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="0aa5e-104">The next stage of data disk update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>