<Type Name="IWithType&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithType&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithType&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithType`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithType`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithType(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithType&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT">この定義をアタッチした後に戻るに親の定義の段階です。</typeparam>
    <summary>
            仮想マシン拡張機能のイメージの種類を指定できるように仮想マシン拡張機能の定義のステージは、この拡張機能に基づいています。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithVersion&lt;ParentT&gt; WithType (string extensionImageTypeName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithVersion`1&lt;!ParentT&gt; WithType(string extensionImageTypeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithType`1.WithType(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithType (extensionImageTypeName As String) As IWithVersion(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithType : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithVersion&lt;'ParentT&gt;" Usage="iWithType.WithType extensionImageTypeName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithVersion&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="extensionImageTypeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="extensionImageTypeName">イメージの種類の名前。</param>
        <summary>
            仮想マシン拡張機能のイメージの種類を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>