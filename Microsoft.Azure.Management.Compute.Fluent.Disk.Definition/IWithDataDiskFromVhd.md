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
            ソース データを選択できるように、管理対象ディスク定義のステージでは、VHD をディスクします。
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
        <param name="vhdUrl">ソース VHD の URL です。</param>
        <summary>
            ソース データ VHD を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>