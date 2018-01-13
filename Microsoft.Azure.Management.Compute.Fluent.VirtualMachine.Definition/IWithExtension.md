<Type Name="IWithExtension" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithExtension">
  <TypeSignature Language="C#" Value="public interface IWithExtension" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithExtension" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithExtension" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithExtension" />
  <TypeSignature Language="F#" Value="type IWithExtension = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            拡張子を指定できるように、仮想マシンの定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineNewExtension">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IBlank&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate&gt; DefineNewExtension (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IBlank`1&lt;class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate&gt; DefineNewExtension(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithExtension.DefineNewExtension(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineNewExtension (name As String) As IBlank(Of IWithCreate)" />
      <MemberSignature Language="F#" Value="abstract member DefineNewExtension : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IBlank&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate&gt;" Usage="iWithExtension.DefineNewExtension name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IBlank&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">拡張機能の参照名。</param>
        <summary>
            仮想マシンにアタッチされている拡張機能の定義を開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>拡張機能定義の最初のステージ段階です。</return>
      </Docs>
    </Member>
  </Members>
</Type>