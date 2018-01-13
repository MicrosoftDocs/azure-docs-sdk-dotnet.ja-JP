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
            <span data-ttu-id="8d61f-101">仮想ネットワーク サブネット内でプライベート IP アドレスを指定できるように、仮想マシンの定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="8d61f-101">The stage of a virtual machine definition allowing to specify a private IP address within a virtual network subnet.</span></span>
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
            <span data-ttu-id="8d61f-102">動的なプライベート IP アドレスの割り当て、VM のプライマリ ネットワーク インターフェイスの指定した既存仮想ネットワーク サブネット内で有効にします。</span><span class="sxs-lookup"><span data-stu-id="8d61f-102">Enables dynamic private IP address allocation within the specified existing virtual network subnet for the VM's primary network interface.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="8d61f-103">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="8d61f-103">The next stage of the definition.</span></span></return>
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
        <param name="staticPrivateIPAddress"><span data-ttu-id="8d61f-104">指定されたサブネット内で静的 IP アドレス。</span><span class="sxs-lookup"><span data-stu-id="8d61f-104">A static IP address within the specified subnet.</span></span></param>
        <summary>
            <span data-ttu-id="8d61f-105">VM のプライマリ ネットワーク インターフェイスに指定した既存の仮想ネットワーク サブネット内にある指定の静的のプライベート IP アドレスを割り当てます。</span><span class="sxs-lookup"><span data-stu-id="8d61f-105">Assigns the specified static private IP address within the specified existing virtual network subnet to the VM's primary network interface.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="8d61f-106">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="8d61f-106">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>