<Type Name="IWithPrivateIP" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPrivateIP">
  <TypeSignature Language="C#" Value="public interface IWithPrivateIP" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPrivateIP" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPrivateIP" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPrivateIP" />
  <TypeSignature Language="F#" Value="type IWithPrivateIP = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            仮想ネットワーク サブネット内でプライベート IP アドレスを指定できるように、仮想マシンの定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithPrimaryPrivateIPAddressDynamic">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPublicIPAddress WithPrimaryPrivateIPAddressDynamic ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPublicIPAddress WithPrimaryPrivateIPAddressDynamic() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPrivateIP.WithPrimaryPrivateIPAddressDynamic" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPrimaryPrivateIPAddressDynamic () As IWithPublicIPAddress" />
      <MemberSignature Language="F#" Value="abstract member WithPrimaryPrivateIPAddressDynamic : unit -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPublicIPAddress" Usage="iWithPrivateIP.WithPrimaryPrivateIPAddressDynamic " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPublicIPAddress</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            動的なプライベート IP アドレスの割り当て、VM のプライマリ ネットワーク インターフェイスの指定した既存仮想ネットワーク サブネット内で有効にします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithPrimaryPrivateIPAddressStatic">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPublicIPAddress WithPrimaryPrivateIPAddressStatic (string staticPrivateIPAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPublicIPAddress WithPrimaryPrivateIPAddressStatic(string staticPrivateIPAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPrivateIP.WithPrimaryPrivateIPAddressStatic(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPrimaryPrivateIPAddressStatic (staticPrivateIPAddress As String) As IWithPublicIPAddress" />
      <MemberSignature Language="F#" Value="abstract member WithPrimaryPrivateIPAddressStatic : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPublicIPAddress" Usage="iWithPrivateIP.WithPrimaryPrivateIPAddressStatic staticPrivateIPAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPublicIPAddress</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="staticPrivateIPAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="staticPrivateIPAddress">指定されたサブネット内で静的 IP アドレス。</param>
        <summary>
            VM のプライマリ ネットワーク インターフェイスに指定した既存の仮想ネットワーク サブネット内にある指定の静的のプライベート IP アドレスを割り当てます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>