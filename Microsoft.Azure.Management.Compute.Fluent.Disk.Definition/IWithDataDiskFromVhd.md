<Type Name="IWithDataDiskFromVhd" FullName="Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithDataDiskFromVhd">
  <TypeSignature Language="C#" Value="public interface IWithDataDiskFromVhd" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDataDiskFromVhd" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithDataDiskFromVhd" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDataDiskFromVhd" />
  <TypeSignature Language="F#" Value="type IWithDataDiskFromVhd = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="bf63f-101">ソース データを選択できるように、管理対象ディスク定義のステージでは、VHD をディスクします。</span><span class="sxs-lookup"><span data-stu-id="bf63f-101">The stage of the managed disk definition allowing to choose source data disk VHD.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="FromVhd">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithCreateAndSize FromVhd (string vhdUrl);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithCreateAndSize FromVhd(string vhdUrl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithDataDiskFromVhd.FromVhd(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function FromVhd (vhdUrl As String) As IWithCreateAndSize" />
      <MemberSignature Language="F#" Value="abstract member FromVhd : string -&gt; Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithCreateAndSize" Usage="iWithDataDiskFromVhd.FromVhd vhdUrl" />
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
        <param name="vhdUrl"><span data-ttu-id="bf63f-102">ソース VHD の URL です。</span><span class="sxs-lookup"><span data-stu-id="bf63f-102">The source VHD URL.</span></span></param>
        <summary>
            <span data-ttu-id="bf63f-103">ソース データ VHD を指定します。</span><span class="sxs-lookup"><span data-stu-id="bf63f-103">Specifies the source data VHD.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="bf63f-104">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="bf63f-104">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>