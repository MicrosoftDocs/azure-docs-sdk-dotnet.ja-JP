<Type Name="IWithAutoUpgradeMinorVersion&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.UpdateDefinition.IWithAutoUpgradeMinorVersion&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithAutoUpgradeMinorVersion&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAutoUpgradeMinorVersion`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.UpdateDefinition.IWithAutoUpgradeMinorVersion`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAutoUpgradeMinorVersion(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithAutoUpgradeMinorVersion&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT">この定義をアタッチした後に戻るに親の更新の段階です。</typeparam>
    <summary>
            仮想マシン拡張機能の定義を有効にするか、新しい仮想マシン拡張機能のイメージのマイナー バージョンがパブリッシュを取得する場合は、拡張機能の自動アップグレードを無効にする段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithMinorVersionAutoUpgrade">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.UpdateDefinition.IWithAttach&lt;ParentT&gt; WithMinorVersionAutoUpgrade ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; WithMinorVersionAutoUpgrade() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.UpdateDefinition.IWithAutoUpgradeMinorVersion`1.WithMinorVersionAutoUpgrade" />
      <MemberSignature Language="VB.NET" Value="Public Function WithMinorVersionAutoUpgrade () As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithMinorVersionAutoUpgrade : unit -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithAutoUpgradeMinorVersion.WithMinorVersionAutoUpgrade " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            自動拡張機能のアップグレードを有効にします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutMinorVersionAutoUpgrade">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.UpdateDefinition.IWithAttach&lt;ParentT&gt; WithoutMinorVersionAutoUpgrade ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; WithoutMinorVersionAutoUpgrade() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.UpdateDefinition.IWithAutoUpgradeMinorVersion`1.WithoutMinorVersionAutoUpgrade" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutMinorVersionAutoUpgrade () As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithoutMinorVersionAutoUpgrade : unit -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithAutoUpgradeMinorVersion.WithoutMinorVersionAutoUpgrade " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            拡張機能の自動アップグレードを無効にします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>