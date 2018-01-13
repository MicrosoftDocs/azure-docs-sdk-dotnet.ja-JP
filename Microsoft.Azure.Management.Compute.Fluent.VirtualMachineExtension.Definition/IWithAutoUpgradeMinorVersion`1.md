<Type Name="IWithAutoUpgradeMinorVersion&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAutoUpgradeMinorVersion&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithAutoUpgradeMinorVersion&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAutoUpgradeMinorVersion`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAutoUpgradeMinorVersion`1" />
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
    <typeparam name="ParentT"><span data-ttu-id="2dc26-101">この定義をアタッチした後に戻るに親の定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="2dc26-101">The stage of the parent definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="2dc26-102">仮想マシン拡張機能の定義を有効にするか、新しい仮想マシン拡張機能のイメージのマイナー バージョンがパブリッシュを取得する場合は、拡張機能の自動アップグレードを無効にする段階です。</span><span class="sxs-lookup"><span data-stu-id="2dc26-102">The stage of the virtual machine extension definition allowing to enable or disable auto upgrade of the extension when when a new minor version of virtual machine extension image gets published.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithMinorVersionAutoUpgrade">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAttach&lt;ParentT&gt; WithMinorVersionAutoUpgrade ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAttach`1&lt;!ParentT&gt; WithMinorVersionAutoUpgrade() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAutoUpgradeMinorVersion`1.WithMinorVersionAutoUpgrade" />
      <MemberSignature Language="VB.NET" Value="Public Function WithMinorVersionAutoUpgrade () As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithMinorVersionAutoUpgrade : unit -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithAutoUpgradeMinorVersion.WithMinorVersionAutoUpgrade " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2dc26-103">自動拡張機能のアップグレードを有効にします。</span><span class="sxs-lookup"><span data-stu-id="2dc26-103">Enables auto upgrade of the extension.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="2dc26-104">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="2dc26-104">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutMinorVersionAutoUpgrade">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAttach&lt;ParentT&gt; WithoutMinorVersionAutoUpgrade ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAttach`1&lt;!ParentT&gt; WithoutMinorVersionAutoUpgrade() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAutoUpgradeMinorVersion`1.WithoutMinorVersionAutoUpgrade" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutMinorVersionAutoUpgrade () As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithoutMinorVersionAutoUpgrade : unit -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithAutoUpgradeMinorVersion.WithoutMinorVersionAutoUpgrade " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2dc26-105">拡張機能の自動アップグレードを無効にします。</span><span class="sxs-lookup"><span data-stu-id="2dc26-105">Disables auto upgrade of the extension.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="2dc26-106">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="2dc26-106">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>