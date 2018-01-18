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
            <span data-ttu-id="a4225-101">Linux OS ソースを選択できるようにマネージ スナップショット定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="a4225-101">The stage of the managed snapshot definition allowing to choose a Linux OS source.</span></span>
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
        <param name="sourceDisk"><span data-ttu-id="a4225-102">ソースは、ディスクを管理します。</span><span class="sxs-lookup"><span data-stu-id="a4225-102">A source managed disk.</span></span></param>
        <summary>
            <span data-ttu-id="a4225-103">ソース Linux OS の管理対象ディスクを指定します。</span><span class="sxs-lookup"><span data-stu-id="a4225-103">Specifies the source Linux OS managed disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a4225-104">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="a4225-104">The next stage of the definition.</span></span></return>
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
        <param name="sourceDiskId"><span data-ttu-id="a4225-105">ソース管理されているディスク リソース id です。</span><span class="sxs-lookup"><span data-stu-id="a4225-105">A source managed disk resource ID.</span></span></param>
        <summary>
            <span data-ttu-id="a4225-106">ソース Linux OS の管理対象ディスクを指定します。</span><span class="sxs-lookup"><span data-stu-id="a4225-106">Specifies the source Linux OS managed disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a4225-107">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="a4225-107">The next stage of the definition.</span></span></return>
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
        <param name="sourceSnapshot"><span data-ttu-id="a4225-108">ソースのスナップショットです。</span><span class="sxs-lookup"><span data-stu-id="a4225-108">A source snapshot.</span></span></param>
        <summary>
            <span data-ttu-id="a4225-109">Linux OS のソース管理されているスナップショットを指定します。</span><span class="sxs-lookup"><span data-stu-id="a4225-109">Specifies the source Linux OS managed snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a4225-110">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="a4225-110">The next stage of the definition.</span></span></return>
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
        <param name="sourceSnapshotId"><span data-ttu-id="a4225-111">スナップショットのリソース id です。</span><span class="sxs-lookup"><span data-stu-id="a4225-111">A snapshot resource ID.</span></span></param>
        <summary>
            <span data-ttu-id="a4225-112">Linux OS のソース管理されているスナップショットを指定します。</span><span class="sxs-lookup"><span data-stu-id="a4225-112">Specifies the source Linux OS managed snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a4225-113">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="a4225-113">The next stage of the definition.</span></span></return>
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
        <param name="vhdUrl"><span data-ttu-id="a4225-114">ソース VHD の URL です。</span><span class="sxs-lookup"><span data-stu-id="a4225-114">The source VHD URL.</span></span></param>
        <summary>
            <span data-ttu-id="a4225-115">元の特化または Linux OS VHD を汎用化を指定します。</span><span class="sxs-lookup"><span data-stu-id="a4225-115">Specifies the source specialized or generalized Linux OS VHD.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a4225-116">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="a4225-116">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>