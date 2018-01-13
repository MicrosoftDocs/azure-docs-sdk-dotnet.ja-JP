<Type Name="IWithWindowsDiskSource" FullName="Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithWindowsDiskSource">
  <TypeSignature Language="C#" Value="public interface IWithWindowsDiskSource" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithWindowsDiskSource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithWindowsDiskSource" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithWindowsDiskSource" />
  <TypeSignature Language="F#" Value="type IWithWindowsDiskSource = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Windows OS ソースを選択できるように、管理対象ディスク定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithWindowsFromDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithCreateAndSize WithWindowsFromDisk (Microsoft.Azure.Management.Compute.Fluent.IDisk sourceDisk);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithCreateAndSize WithWindowsFromDisk(class Microsoft.Azure.Management.Compute.Fluent.IDisk sourceDisk) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithWindowsDiskSource.WithWindowsFromDisk(Microsoft.Azure.Management.Compute.Fluent.IDisk)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithWindowsFromDisk (sourceDisk As IDisk) As IWithCreateAndSize" />
      <MemberSignature Language="F#" Value="abstract member WithWindowsFromDisk : Microsoft.Azure.Management.Compute.Fluent.IDisk -&gt; Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithCreateAndSize" Usage="iWithWindowsDiskSource.WithWindowsFromDisk sourceDisk" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithCreateAndSize</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceDisk" Type="Microsoft.Azure.Management.Compute.Fluent.IDisk" />
      </Parameters>
      <Docs>
        <param name="sourceDisk">ソースは、ディスクを管理します。</param>
        <summary>
            元の Windows OS の管理対象ディスクを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithWindowsFromDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithCreateAndSize WithWindowsFromDisk (string sourceDiskId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithCreateAndSize WithWindowsFromDisk(string sourceDiskId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithWindowsDiskSource.WithWindowsFromDisk(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithWindowsFromDisk (sourceDiskId As String) As IWithCreateAndSize" />
      <MemberSignature Language="F#" Value="abstract member WithWindowsFromDisk : string -&gt; Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithCreateAndSize" Usage="iWithWindowsDiskSource.WithWindowsFromDisk sourceDiskId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithCreateAndSize</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceDiskId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sourceDiskId">ソースの管理対象ディスクのリソース id です。</param>
        <summary>
            元の Windows OS の管理対象ディスクを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithWindowsFromSnapshot">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithCreateAndSize WithWindowsFromSnapshot (Microsoft.Azure.Management.Compute.Fluent.ISnapshot sourceSnapshot);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithCreateAndSize WithWindowsFromSnapshot(class Microsoft.Azure.Management.Compute.Fluent.ISnapshot sourceSnapshot) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithWindowsDiskSource.WithWindowsFromSnapshot(Microsoft.Azure.Management.Compute.Fluent.ISnapshot)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithWindowsFromSnapshot (sourceSnapshot As ISnapshot) As IWithCreateAndSize" />
      <MemberSignature Language="F#" Value="abstract member WithWindowsFromSnapshot : Microsoft.Azure.Management.Compute.Fluent.ISnapshot -&gt; Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithCreateAndSize" Usage="iWithWindowsDiskSource.WithWindowsFromSnapshot sourceSnapshot" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithCreateAndSize</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceSnapshot" Type="Microsoft.Azure.Management.Compute.Fluent.ISnapshot" />
      </Parameters>
      <Docs>
        <param name="sourceSnapshot">ソースのスナップショットです。</param>
        <summary>
            ソースの Windows OS マネージ スナップショットを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithWindowsFromSnapshot">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithCreateAndSize WithWindowsFromSnapshot (string sourceSnapshotId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithCreateAndSize WithWindowsFromSnapshot(string sourceSnapshotId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithWindowsDiskSource.WithWindowsFromSnapshot(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithWindowsFromSnapshot (sourceSnapshotId As String) As IWithCreateAndSize" />
      <MemberSignature Language="F#" Value="abstract member WithWindowsFromSnapshot : string -&gt; Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithCreateAndSize" Usage="iWithWindowsDiskSource.WithWindowsFromSnapshot sourceSnapshotId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithCreateAndSize</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceSnapshotId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sourceSnapshotId">スナップショットのリソース id です。</param>
        <summary>
            ソースの Windows OS マネージ スナップショットを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithWindowsFromVhd">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithCreateAndSize WithWindowsFromVhd (string vhdUrl);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithCreateAndSize WithWindowsFromVhd(string vhdUrl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithWindowsDiskSource.WithWindowsFromVhd(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithWindowsFromVhd (vhdUrl As String) As IWithCreateAndSize" />
      <MemberSignature Language="F#" Value="abstract member WithWindowsFromVhd : string -&gt; Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithCreateAndSize" Usage="iWithWindowsDiskSource.WithWindowsFromVhd vhdUrl" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithCreateAndSize</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vhdUrl" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="vhdUrl">ソース VHD の URL です。</param>
        <summary>
            特殊な変換元または Windows OS VHD を汎用化を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>