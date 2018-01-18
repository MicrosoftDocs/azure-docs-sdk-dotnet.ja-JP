<Type Name="IWithLinuxRootPasswordOrPublicKeyManaged" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootPasswordOrPublicKeyManaged">
  <TypeSignature Language="C#" Value="public interface IWithLinuxRootPasswordOrPublicKeyManaged" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithLinuxRootPasswordOrPublicKeyManaged" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootPasswordOrPublicKeyManaged" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithLinuxRootPasswordOrPublicKeyManaged" />
  <TypeSignature Language="F#" Value="type IWithLinuxRootPasswordOrPublicKeyManaged = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1c605-101">Linux 仮想マシンのスケールのステージでは、SSH ルート パスワードまたは公開キーを指定できるように定義を設定します。</span><span class="sxs-lookup"><span data-stu-id="1c605-101">The stage of the Linux virtual machine scale set definition allowing to specify SSH root password or public key.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithRootPassword">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxCreateManaged WithRootPassword (string rootPassword);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxCreateManaged WithRootPassword(string rootPassword) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootPasswordOrPublicKeyManaged.WithRootPassword(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRootPassword (rootPassword As String) As IWithLinuxCreateManaged" />
      <MemberSignature Language="F#" Value="abstract member WithRootPassword : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxCreateManaged" Usage="iWithLinuxRootPasswordOrPublicKeyManaged.WithRootPassword rootPassword" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxCreateManaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="rootPassword" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="rootPassword"><span data-ttu-id="1c605-102">Azure Linux VM のパスワードの複雑さの条件を次のパスワード。</span><span class="sxs-lookup"><span data-stu-id="1c605-102">A password following the complexity criteria for Azure Linux VM passwords.</span></span></param>
        <summary>
            <span data-ttu-id="1c605-103">Linux 仮想マシンの SSH ルート パスワードを指定します。</span><span class="sxs-lookup"><span data-stu-id="1c605-103">Specifies the SSH root password for the Linux virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="1c605-104">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="1c605-104">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithSsh">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxCreateManaged WithSsh (string publicKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxCreateManaged WithSsh(string publicKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootPasswordOrPublicKeyManaged.WithSsh(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSsh (publicKey As String) As IWithLinuxCreateManaged" />
      <MemberSignature Language="F#" Value="abstract member WithSsh : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxCreateManaged" Usage="iWithLinuxRootPasswordOrPublicKeyManaged.WithSsh publicKey" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxCreateManaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="publicKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="publicKey"><span data-ttu-id="1c605-105">PEM 形式で SSH 公開キー。</span><span class="sxs-lookup"><span data-stu-id="1c605-105">The SSH public key in PEM format.</span></span></param>
        <summary>
            <span data-ttu-id="1c605-106">SSH 公開キーを指定します。</span><span class="sxs-lookup"><span data-stu-id="1c605-106">Specifies the SSH public key.</span></span>
            <span data-ttu-id="1c605-107">このメソッドを呼び出すたびでは、VM のパブリック キーの一覧に指定されたパブリック キーを追加します。</span><span class="sxs-lookup"><span data-stu-id="1c605-107">Each call to this method adds the given public key to the list of VM's public keys.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="1c605-108">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="1c605-108">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>