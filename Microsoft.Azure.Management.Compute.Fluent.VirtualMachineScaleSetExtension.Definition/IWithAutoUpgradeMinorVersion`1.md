<Type Name="IWithAutoUpgradeMinorVersion&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.Definition.IWithAutoUpgradeMinorVersion&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithAutoUpgradeMinorVersion&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAutoUpgradeMinorVersion`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.Definition.IWithAutoUpgradeMinorVersion`1" />
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
    <typeparam name="ParentT"><span data-ttu-id="ca017-101">この定義をアタッチした後に戻るに親の定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="ca017-101">The stage of the parent definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="ca017-102">ステージ、仮想マシン スケール セット拡張機能定義できるように有効にするにまたは新しいのマイナー バージョンの仮想マシン スケール セットの拡張イメージとは、拡張機能の自動アップグレードを無効にするは発行を取得します。</span><span class="sxs-lookup"><span data-stu-id="ca017-102">The stage of a virtual machine scale set extension definition allowing to enable or disable auto upgrade of the extension when when a new minor version of virtual machine scale set extension image gets published.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithMinorVersionAutoUpgrade">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.Definition.IWithAttach&lt;ParentT&gt; WithMinorVersionAutoUpgrade ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.Definition.IWithAttach`1&lt;!ParentT&gt; WithMinorVersionAutoUpgrade() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.Definition.IWithAutoUpgradeMinorVersion`1.WithMinorVersionAutoUpgrade" />
      <MemberSignature Language="VB.NET" Value="Public Function WithMinorVersionAutoUpgrade () As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithMinorVersionAutoUpgrade : unit -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithAutoUpgradeMinorVersion.WithMinorVersionAutoUpgrade " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ca017-103">自動のマイナー バージョンを持つ拡張機能のアップグレードを有効にします。</span><span class="sxs-lookup"><span data-stu-id="ca017-103">Enables auto upgrading of the extension with minor versions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="ca017-104">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="ca017-104">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutMinorVersionAutoUpgrade">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.Definition.IWithAttach&lt;ParentT&gt; WithoutMinorVersionAutoUpgrade ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.Definition.IWithAttach`1&lt;!ParentT&gt; WithoutMinorVersionAutoUpgrade() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.Definition.IWithAutoUpgradeMinorVersion`1.WithoutMinorVersionAutoUpgrade" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutMinorVersionAutoUpgrade () As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithoutMinorVersionAutoUpgrade : unit -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithAutoUpgradeMinorVersion.WithoutMinorVersionAutoUpgrade " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ca017-105">無効に自動的にマイナー バージョンを持つ拡張機能をアップグレードします。</span><span class="sxs-lookup"><span data-stu-id="ca017-105">Disables auto upgrading the extension with minor versions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="ca017-106">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="ca017-106">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>