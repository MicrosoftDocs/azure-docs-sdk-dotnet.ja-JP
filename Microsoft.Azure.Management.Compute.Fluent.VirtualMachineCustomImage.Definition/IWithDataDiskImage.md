<Type Name="IWithDataDiskImage" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithDataDiskImage">
  <TypeSignature Language="C#" Value="public interface IWithDataDiskImage" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDataDiskImage" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithDataDiskImage" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDataDiskImage" />
  <TypeSignature Language="F#" Value="type IWithDataDiskImage = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            データの追加を許可するイメージ定義のステージは、ディスク イメージがあります。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineDataDiskImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.CustomImageDataDisk.Definition.IBlank&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings&gt; DefineDataDiskImage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.CustomImageDataDisk.Definition.IBlank`1&lt;class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings&gt; DefineDataDiskImage() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithDataDiskImage.DefineDataDiskImage" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineDataDiskImage () As IBlank(Of IWithCreateAndDataDiskImageOSDiskSettings)" />
      <MemberSignature Language="F#" Value="abstract member DefineDataDiskImage : unit -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.CustomImageDataDisk.Definition.IBlank&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings&gt;" Usage="iWithDataDiskImage.DefineDataDiskImage " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.CustomImageDataDisk.Definition.IBlank&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            値で始まるイメージに追加する新しいデータ ディスク イメージの定義を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithDataDiskImageFromManagedDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithDataDiskImageFromManagedDisk (string sourceManagedDiskId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithDataDiskImageFromManagedDisk(string sourceManagedDiskId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithDataDiskImage.WithDataDiskImageFromManagedDisk(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDataDiskImageFromManagedDisk (sourceManagedDiskId As String) As IWithCreateAndDataDiskImageOSDiskSettings" />
      <MemberSignature Language="F#" Value="abstract member WithDataDiskImageFromManagedDisk : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings" Usage="iWithDataDiskImage.WithDataDiskImageFromManagedDisk sourceManagedDiskId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceManagedDiskId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sourceManagedDiskId">ソースの管理対象ディスクのリソース id です。</param>
        <summary>
            ソースとして既存の管理対象ディスクとデータ ディスク イメージを追加します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithDataDiskImageFromSnapshot">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithDataDiskImageFromSnapshot (string sourceSnapshotId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithDataDiskImageFromSnapshot(string sourceSnapshotId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithDataDiskImage.WithDataDiskImageFromSnapshot(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDataDiskImageFromSnapshot (sourceSnapshotId As String) As IWithCreateAndDataDiskImageOSDiskSettings" />
      <MemberSignature Language="F#" Value="abstract member WithDataDiskImageFromSnapshot : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings" Usage="iWithDataDiskImage.WithDataDiskImageFromSnapshot sourceSnapshotId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceSnapshotId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sourceSnapshotId">ソースのスナップショットのリソース id です。</param>
        <summary>
            ソースとして既存のスナップショットを持つデータ ディスク イメージを追加します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithDataDiskImageFromVhd">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithDataDiskImageFromVhd (string sourceVhdUrl);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithDataDiskImageFromVhd(string sourceVhdUrl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithDataDiskImage.WithDataDiskImageFromVhd(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDataDiskImageFromVhd (sourceVhdUrl As String) As IWithCreateAndDataDiskImageOSDiskSettings" />
      <MemberSignature Language="F#" Value="abstract member WithDataDiskImageFromVhd : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings" Usage="iWithDataDiskImage.WithDataDiskImageFromVhd sourceVhdUrl" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceVhdUrl" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sourceVhdUrl">ソース バーチャル ハード ディスクの URL です。</param>
        <summary>
            ソースとして、仮想ハード ディスクにデータ ディスク イメージを追加します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>