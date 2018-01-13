<Type Name="IWithDiskSize" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Update.IWithDiskSize">
  <TypeSignature Language="C#" Value="public interface IWithDiskSize" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDiskSize" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Update.IWithDiskSize" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDiskSize" />
  <TypeSignature Language="F#" Value="type IWithDiskSize = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            仮想マシン データ ディスクの更新を許可するディスクのサイズを設定する段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithSizeInGB">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Update.IUpdate WithSizeInGB (int sizeInGB);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Update.IUpdate WithSizeInGB(int32 sizeInGB) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Update.IWithDiskSize.WithSizeInGB(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSizeInGB (sizeInGB As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithSizeInGB : int -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Update.IUpdate" Usage="iWithDiskSize.WithSizeInGB sizeInGB" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sizeInGB" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="sizeInGB">GB のディスク サイズです。</param>
        <summary>
            データ ディスクを GB で、新しいサイズを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>データ ディスクの更新の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>