<Type Name="IWithLinuxSnapshotSource" FullName="Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithLinuxSnapshotSource">
  <TypeSignature Language="C#" Value="public interface IWithLinuxSnapshotSource" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithLinuxSnapshotSource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithLinuxSnapshotSource" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithLinuxSnapshotSource" />
  <TypeSignature Language="F#" Value="type IWithLinuxSnapshotSource = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Linux OS ソースを選択できるようにマネージ スナップショット定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithLinuxFromDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate WithLinuxFromDisk (Microsoft.Azure.Management.Compute.Fluent.IDisk sourceDisk);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate WithLinuxFromDisk(class Microsoft.Azure.Management.Compute.Fluent.IDisk sourceDisk) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithLinuxSnapshotSource.WithLinuxFromDisk(Microsoft.Azure.Management.Compute.Fluent.IDisk)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithLinuxFromDisk (sourceDisk As IDisk) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithLinuxFromDisk : Microsoft.Azure.Management.Compute.Fluent.IDisk -&gt; Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate" Usage="iWithLinuxSnapshotSource.WithLinuxFromDisk sourceDisk" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceDisk" Type="Microsoft.Azure.Management.Compute.Fluent.IDisk" />
      </Parameters>
      <Docs>
        <param name="sourceDisk">ソースは、ディスクを管理します。</param>
        <summary>
            ソース Linux OS の管理対象ディスクを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithLinuxFromDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate WithLinuxFromDisk (string sourceDiskId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate WithLinuxFromDisk(string sourceDiskId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithLinuxSnapshotSource.WithLinuxFromDisk(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithLinuxFromDisk (sourceDiskId As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithLinuxFromDisk : string -&gt; Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate" Usage="iWithLinuxSnapshotSource.WithLinuxFromDisk sourceDiskId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceDiskId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sourceDiskId">ソース管理されているディスク リソース id です。</param>
        <summary>
            ソース Linux OS の管理対象ディスクを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithLinuxFromSnapshot">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate WithLinuxFromSnapshot (Microsoft.Azure.Management.Compute.Fluent.ISnapshot sourceSnapshot);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate WithLinuxFromSnapshot(class Microsoft.Azure.Management.Compute.Fluent.ISnapshot sourceSnapshot) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithLinuxSnapshotSource.WithLinuxFromSnapshot(Microsoft.Azure.Management.Compute.Fluent.ISnapshot)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithLinuxFromSnapshot (sourceSnapshot As ISnapshot) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithLinuxFromSnapshot : Microsoft.Azure.Management.Compute.Fluent.ISnapshot -&gt; Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate" Usage="iWithLinuxSnapshotSource.WithLinuxFromSnapshot sourceSnapshot" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceSnapshot" Type="Microsoft.Azure.Management.Compute.Fluent.ISnapshot" />
      </Parameters>
      <Docs>
        <param name="sourceSnapshot">ソースのスナップショットです。</param>
        <summary>
            Linux OS のソース管理されているスナップショットを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithLinuxFromSnapshot">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate WithLinuxFromSnapshot (string sourceSnapshotId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate WithLinuxFromSnapshot(string sourceSnapshotId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithLinuxSnapshotSource.WithLinuxFromSnapshot(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithLinuxFromSnapshot (sourceSnapshotId As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithLinuxFromSnapshot : string -&gt; Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate" Usage="iWithLinuxSnapshotSource.WithLinuxFromSnapshot sourceSnapshotId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceSnapshotId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sourceSnapshotId">スナップショットのリソース id です。</param>
        <summary>
            Linux OS のソース管理されているスナップショットを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithLinuxFromVhd">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate WithLinuxFromVhd (string vhdUrl);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate WithLinuxFromVhd(string vhdUrl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithLinuxSnapshotSource.WithLinuxFromVhd(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithLinuxFromVhd (vhdUrl As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithLinuxFromVhd : string -&gt; Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate" Usage="iWithLinuxSnapshotSource.WithLinuxFromVhd vhdUrl" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vhdUrl" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="vhdUrl">ソース VHD の URL です。</param>
        <summary>
            元の特化または Linux OS VHD を汎用化を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>