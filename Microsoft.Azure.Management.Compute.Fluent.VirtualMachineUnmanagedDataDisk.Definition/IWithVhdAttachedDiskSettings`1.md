<Type Name="IWithVhdAttachedDiskSettings&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithVhdAttachedDiskSettings&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithVhdAttachedDiskSettings&lt;ParentT&gt; : Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithAttach&lt;ParentT&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Definition.IInDefinition&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithVhdAttachedDiskSettings`1&lt;ParentT&gt; implements class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithAttach`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Definition.IInDefinition`1&lt;!ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithVhdAttachedDiskSettings`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithVhdAttachedDiskSettings(Of ParentT)&#xA;Implements IInDefinition(Of ParentT), IWithAttach(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithVhdAttachedDiskSettings&lt;'ParentT&gt; = interface&#xA;    interface IWithAttach&lt;'ParentT&gt;&#xA;    interface IInDefinition&lt;'ParentT&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithAttach&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Definition.IInDefinition&lt;ParentT&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="ParentT">この定義をアタッチした後に戻るに親の定義の段階です。</typeparam>
    <summary>
            により、ステージは、既存の VHD にベース ディスクを構成します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithCaching">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithVhdAttachedDiskSettings&lt;ParentT&gt; WithCaching (Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithVhdAttachedDiskSettings`1&lt;!ParentT&gt; WithCaching(valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithVhdAttachedDiskSettings`1.WithCaching(Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithCaching (cachingType As CachingTypes) As IWithVhdAttachedDiskSettings(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithCaching : Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithVhdAttachedDiskSettings&lt;'ParentT&gt;" Usage="iWithVhdAttachedDiskSettings.WithCaching cachingType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithVhdAttachedDiskSettings&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cachingType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes" />
      </Parameters>
      <Docs>
        <param name="cachingType">型のキャッシュ ディスク。 使用可能な値が含まれます。 'None'、'ReadOnly'、'ReadWrite' です。</param>
        <summary>
            データ ディスクのキャッシュの種類を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>データ ディスクの定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithLun">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithVhdAttachedDiskSettings&lt;ParentT&gt; WithLun (int lun);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithVhdAttachedDiskSettings`1&lt;!ParentT&gt; WithLun(int32 lun) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithVhdAttachedDiskSettings`1.WithLun(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithLun (lun As Integer) As IWithVhdAttachedDiskSettings(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithLun : int -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithVhdAttachedDiskSettings&lt;'ParentT&gt;" Usage="iWithVhdAttachedDiskSettings.WithLun lun" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithVhdAttachedDiskSettings&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lun" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="lun">論理ユニットの数です。</param>
        <summary>
            データ ディスクの論理ユニット番号を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>データ ディスクの定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithSizeInGB">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithVhdAttachedDiskSettings&lt;ParentT&gt; WithSizeInGB (int sizeInGB);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithVhdAttachedDiskSettings`1&lt;!ParentT&gt; WithSizeInGB(int32 sizeInGB) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithVhdAttachedDiskSettings`1.WithSizeInGB(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSizeInGB (sizeInGB As Integer) As IWithVhdAttachedDiskSettings(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithSizeInGB : int -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithVhdAttachedDiskSettings&lt;'ParentT&gt;" Usage="iWithVhdAttachedDiskSettings.WithSizeInGB sizeInGB" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithVhdAttachedDiskSettings&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sizeInGB" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="sizeInGB">GB のディスク サイズです。</param>
        <summary>
            GB のサイズを変更する必要があるディスクのサイズを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>データ ディスクの定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>