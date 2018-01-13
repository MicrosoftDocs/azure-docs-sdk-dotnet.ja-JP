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
            仮想マシン データ ディスクの更新を許可する型のキャッシュ ディスクの設定の段階です。
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
        <param name="cachingType">型のキャッシュ ディスク。 使用可能な値が含まれます。 'None'、'ReadOnly'、'ReadWrite' です。</param>
        <summary>
            データ ディスクの新しいキャッシュの種類を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>データ ディスクの更新の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>