<Type Name="IWithDataSnapshotFromImage" FullName="Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithDataSnapshotFromImage">
  <TypeSignature Language="C#" Value="public interface IWithDataSnapshotFromImage" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDataSnapshotFromImage" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithDataSnapshotFromImage" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDataSnapshotFromImage" />
  <TypeSignature Language="F#" Value="type IWithDataSnapshotFromImage = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d5697-101">ソース データのディスク イメージを選択できるように管理対象ディスクの定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="d5697-101">The stage of the managed disk definition allowing to choose source data disk image.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="FromImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate FromImage (Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineCustomImage image, int diskLun);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate FromImage(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineCustomImage image, int32 diskLun) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithDataSnapshotFromImage.FromImage(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineCustomImage,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function FromImage (image As IVirtualMachineCustomImage, diskLun As Integer) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member FromImage : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineCustomImage * int -&gt; Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate" Usage="iWithDataSnapshotFromImage.FromImage (image, diskLun)" />
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
        <Parameter Name="diskLun" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="image"><span data-ttu-id="d5697-102">イメージです。</span><span class="sxs-lookup"><span data-stu-id="d5697-102">The image.</span></span></param>
        <param name="diskLun"><span data-ttu-id="d5697-103">ディスク イメージの LUN です。</span><span class="sxs-lookup"><span data-stu-id="d5697-103">LUN of the disk image.</span></span></param>
        <summary>
            <span data-ttu-id="d5697-104">ソース データのディスク イメージを含むカスタム イメージを指定します。</span><span class="sxs-lookup"><span data-stu-id="d5697-104">Specifies a custom image containing a source data disk image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d5697-105">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="d5697-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="FromImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate FromImage (Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage image, int diskLun);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate FromImage(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage image, int32 diskLun) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithDataSnapshotFromImage.FromImage(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function FromImage (image As IVirtualMachineImage, diskLun As Integer) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member FromImage : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage * int -&gt; Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate" Usage="iWithDataSnapshotFromImage.FromImage (image, diskLun)" />
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
        <Parameter Name="diskLun" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="image"><span data-ttu-id="d5697-106">イメージです。</span><span class="sxs-lookup"><span data-stu-id="d5697-106">An image.</span></span></param>
        <param name="diskLun"><span data-ttu-id="d5697-107">ディスク イメージの LUN です。</span><span class="sxs-lookup"><span data-stu-id="d5697-107">LUN of the disk image.</span></span></param>
        <summary>
            <span data-ttu-id="d5697-108">ソース データのディスク イメージを含むイメージを指定します。</span><span class="sxs-lookup"><span data-stu-id="d5697-108">Specifies an image containing a source data disk image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d5697-109">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="d5697-109">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="FromImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate FromImage (string imageId, int diskLun);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate FromImage(string imageId, int32 diskLun) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithDataSnapshotFromImage.FromImage(System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function FromImage (imageId As String, diskLun As Integer) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member FromImage : string * int -&gt; Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate" Usage="iWithDataSnapshotFromImage.FromImage (imageId, diskLun)" />
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
        <Parameter Name="diskLun" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="imageId"><span data-ttu-id="d5697-110">イメージのリソース ID</span><span class="sxs-lookup"><span data-stu-id="d5697-110">An image resource ID.</span></span></param>
        <param name="diskLun"><span data-ttu-id="d5697-111">ディスク イメージの LUN です。</span><span class="sxs-lookup"><span data-stu-id="d5697-111">LUN of the disk image.</span></span></param>
        <summary>
            <span data-ttu-id="d5697-112">ソース データのディスク イメージを含むイメージを指定します。</span><span class="sxs-lookup"><span data-stu-id="d5697-112">Specifies an image containing source data disk image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d5697-113">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="d5697-113">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>