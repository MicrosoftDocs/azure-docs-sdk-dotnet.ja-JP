<Type Name="IWithOSSnapshotFromImage" FullName="Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithOSSnapshotFromImage">
  <TypeSignature Language="C#" Value="public interface IWithOSSnapshotFromImage" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithOSSnapshotFromImage" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithOSSnapshotFromImage" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithOSSnapshotFromImage" />
  <TypeSignature Language="F#" Value="type IWithOSSnapshotFromImage = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            元のオペレーティング システム イメージを選択できるように、管理対象ディスク定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="FromImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate FromImage (Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineCustomImage image);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate FromImage(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineCustomImage image) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithOSSnapshotFromImage.FromImage(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineCustomImage)" />
      <MemberSignature Language="VB.NET" Value="Public Function FromImage (image As IVirtualMachineCustomImage) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member FromImage : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineCustomImage -&gt; Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate" Usage="iWithOSSnapshotFromImage.FromImage image" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="image" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineCustomImage" />
      </Parameters>
      <Docs>
        <param name="image">イメージです。</param>
        <summary>
            オペレーティング システムを含むカスタム イメージを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="FromImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate FromImage (Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage image);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate FromImage(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage image) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithOSSnapshotFromImage.FromImage(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage)" />
      <MemberSignature Language="VB.NET" Value="Public Function FromImage (image As IVirtualMachineImage) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member FromImage : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage -&gt; Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate" Usage="iWithOSSnapshotFromImage.FromImage image" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="image" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage" />
      </Parameters>
      <Docs>
        <param name="image">イメージです。</param>
        <summary>
            オペレーティング システムを含むイメージを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="FromImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate FromImage (string imageId, Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes osType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate FromImage(string imageId, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes osType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithOSSnapshotFromImage.FromImage(System.String,Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function FromImage (imageId As String, osType As OperatingSystemTypes) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member FromImage : string * Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate" Usage="iWithOSSnapshotFromImage.FromImage (imageId, osType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="imageId" Type="System.String" />
        <Parameter Name="osType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes" />
      </Parameters>
      <Docs>
        <param name="imageId">イメージのリソース id です。</param>
        <param name="osType">オペレーティング システムの種類。</param>
        <summary>
            オペレーティング システムを含むイメージを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>