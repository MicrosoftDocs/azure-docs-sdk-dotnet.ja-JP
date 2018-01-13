<Type Name="IWithDiskLun&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.CustomImageDataDisk.Definition.IWithDiskLun&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithDiskLun&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDiskLun`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.CustomImageDataDisk.Definition.IWithDiskLun`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDiskLun(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithDiskLun&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="73c1c-101">この定義をアタッチした後に戻るに親の定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="73c1c-101">The stage of the parent definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="73c1c-102">ディスク イメージの LUN を指定できるように、イメージ定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="73c1c-102">The stage of the image definition allowing to specify the LUN for the disk image.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithLun">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.CustomImageDataDisk.Definition.IWithImageSource&lt;ParentT&gt; WithLun (int lun);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.CustomImageDataDisk.Definition.IWithImageSource`1&lt;!ParentT&gt; WithLun(int32 lun) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.CustomImageDataDisk.Definition.IWithDiskLun`1.WithLun(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithLun (lun As Integer) As IWithImageSource(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithLun : int -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.CustomImageDataDisk.Definition.IWithImageSource&lt;'ParentT&gt;" Usage="iWithDiskLun.WithLun lun" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.CustomImageDataDisk.Definition.IWithImageSource&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lun" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="lun"><span data-ttu-id="73c1c-103">データ ディスクの一意の LUN です。</span><span class="sxs-lookup"><span data-stu-id="73c1c-103">The unique LUN for the data disk.</span></span></param>
        <summary>
            <span data-ttu-id="73c1c-104">ディスク イメージから作成するデータ ディスクの LUN を指定します。</span><span class="sxs-lookup"><span data-stu-id="73c1c-104">Specifies the LUN for the data disk to be created from the disk image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="73c1c-105">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="73c1c-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>