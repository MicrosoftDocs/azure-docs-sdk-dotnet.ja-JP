<Type Name="IWithDiskSource&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IWithDiskSource&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithDiskSource&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDiskSource`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IWithDiskSource`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDiskSource(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithDiskSource&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="9a5f4-101">この定義をアタッチした後に戻るに親の更新の段階です。</span><span class="sxs-lookup"><span data-stu-id="9a5f4-101">The stage of the parent update to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="9a5f4-102">データ ディスク定義できるようにする、ソースの選択の段階です。</span><span class="sxs-lookup"><span data-stu-id="9a5f4-102">The stage of the data disk definition allowing to choose the source.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingVhd">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IWithVhdAttachedDiskSettings&lt;ParentT&gt; WithExistingVhd (string storageAccountName, string containerName, string vhdName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IWithVhdAttachedDiskSettings`1&lt;!ParentT&gt; WithExistingVhd(string storageAccountName, string containerName, string vhdName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IWithDiskSource`1.WithExistingVhd(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingVhd (storageAccountName As String, containerName As String, vhdName As String) As IWithVhdAttachedDiskSettings(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithExistingVhd : string * string * string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IWithVhdAttachedDiskSettings&lt;'ParentT&gt;" Usage="iWithDiskSource.WithExistingVhd (storageAccountName, containerName, vhdName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IWithVhdAttachedDiskSettings&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="vhdName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="storageAccountName"><span data-ttu-id="9a5f4-103">ストレージ アカウント名。</span><span class="sxs-lookup"><span data-stu-id="9a5f4-103">The storage account name.</span></span></param>
        <param name="containerName"><span data-ttu-id="9a5f4-104">VHD ファイルを保持するコンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="9a5f4-104">The name of the container holding VHD file.</span></span></param>
        <param name="vhdName"><span data-ttu-id="9a5f4-105">アタッチする VHD ファイルの名前。</span><span class="sxs-lookup"><span data-stu-id="9a5f4-105">The name of the VHD file to attach.</span></span></param>
        <summary>
            <span data-ttu-id="9a5f4-106">既存のソース ディスクの VHD を指定します。</span><span class="sxs-lookup"><span data-stu-id="9a5f4-106">Specifies the existing source VHD of the disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="9a5f4-107">データ ディスクの定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="9a5f4-107">The next stage of data disk definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewVhd">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IWithNewVhdDiskSettings&lt;ParentT&gt; WithNewVhd (int sizeInGB);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IWithNewVhdDiskSettings`1&lt;!ParentT&gt; WithNewVhd(int32 sizeInGB) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IWithDiskSource`1.WithNewVhd(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewVhd (sizeInGB As Integer) As IWithNewVhdDiskSettings(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithNewVhd : int -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IWithNewVhdDiskSettings&lt;'ParentT&gt;" Usage="iWithDiskSource.WithNewVhd sizeInGB" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IWithNewVhdDiskSettings&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sizeInGB" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="sizeInGB"><span data-ttu-id="9a5f4-108">最初のディスク サイズ GB です。</span><span class="sxs-lookup"><span data-stu-id="9a5f4-108">The initial disk size in GB.</span></span></param>
        <summary>
            <span data-ttu-id="9a5f4-109">新しい VHD で作成する必要があるそのディスクを指定サイズを指定します。</span><span class="sxs-lookup"><span data-stu-id="9a5f4-109">Specifies that disk needs to be created with a new VHD of given size.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="9a5f4-110">データ ディスクの定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="9a5f4-110">The next stage of data disk definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>