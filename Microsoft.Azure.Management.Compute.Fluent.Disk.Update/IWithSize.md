<Type Name="IWithSize" FullName="Microsoft.Azure.Management.Compute.Fluent.Disk.Update.IWithSize">
  <TypeSignature Language="C#" Value="public interface IWithSize" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSize" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Disk.Update.IWithSize" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSize" />
  <TypeSignature Language="F#" Value="type IWithSize = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            新しいサイズを指定できるように、管理対象ディスク定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithSizeInGB">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Disk.Update.IUpdate WithSizeInGB (int sizeInGB);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.Disk.Update.IUpdate WithSizeInGB(int32 sizeInGB) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Disk.Update.IWithSize.WithSizeInGB(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSizeInGB (sizeInGB As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithSizeInGB : int -&gt; Microsoft.Azure.Management.Compute.Fluent.Disk.Update.IUpdate" Usage="iWithSize.WithSizeInGB sizeInGB" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Disk.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sizeInGB" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="sizeInGB">GB のディスク サイズです。</param>
        <summary>
            ディスクのサイズを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>