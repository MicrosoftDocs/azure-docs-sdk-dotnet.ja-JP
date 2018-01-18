<Type Name="IWithDataSnapshotFromSnapshot" FullName="Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithDataSnapshotFromSnapshot">
  <TypeSignature Language="C#" Value="public interface IWithDataSnapshotFromSnapshot" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDataSnapshotFromSnapshot" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithDataSnapshotFromSnapshot" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDataSnapshotFromSnapshot" />
  <TypeSignature Language="F#" Value="type IWithDataSnapshotFromSnapshot = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8ac48-101">マネージを選択できるように、管理対象ディスク定義のステージは、スナップショットのデータを格納します。</span><span class="sxs-lookup"><span data-stu-id="8ac48-101">The stage of the managed disk definition allowing to choose managed snapshot containing data.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithDataFromSnapshot">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate WithDataFromSnapshot (Microsoft.Azure.Management.Compute.Fluent.ISnapshot snapshot);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate WithDataFromSnapshot(class Microsoft.Azure.Management.Compute.Fluent.ISnapshot snapshot) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithDataSnapshotFromSnapshot.WithDataFromSnapshot(Microsoft.Azure.Management.Compute.Fluent.ISnapshot)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDataFromSnapshot (snapshot As ISnapshot) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithDataFromSnapshot : Microsoft.Azure.Management.Compute.Fluent.ISnapshot -&gt; Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate" Usage="iWithDataSnapshotFromSnapshot.WithDataFromSnapshot snapshot" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="snapshot" Type="Microsoft.Azure.Management.Compute.Fluent.ISnapshot" />
      </Parameters>
      <Docs>
        <param name="snapshot"><span data-ttu-id="8ac48-102">スナップショットのリソースです。</span><span class="sxs-lookup"><span data-stu-id="8ac48-102">A snapshot resource.</span></span></param>
        <summary>
            <span data-ttu-id="8ac48-103">ソース データの管理されているスナップショットを指定します。</span><span class="sxs-lookup"><span data-stu-id="8ac48-103">Specifies the source data managed snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="8ac48-104">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="8ac48-104">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithDataFromSnapshot">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate WithDataFromSnapshot (string snapshotId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate WithDataFromSnapshot(string snapshotId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithDataSnapshotFromSnapshot.WithDataFromSnapshot(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDataFromSnapshot (snapshotId As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithDataFromSnapshot : string -&gt; Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate" Usage="iWithDataSnapshotFromSnapshot.WithDataFromSnapshot snapshotId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="snapshotId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="snapshotId"><span data-ttu-id="8ac48-105">スナップショットのリソース id です。</span><span class="sxs-lookup"><span data-stu-id="8ac48-105">A snapshot resource ID.</span></span></param>
        <summary>
            <span data-ttu-id="8ac48-106">ソース データの管理されているスナップショットを指定します。</span><span class="sxs-lookup"><span data-stu-id="8ac48-106">Specifies the source data managed snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="8ac48-107">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="8ac48-107">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>