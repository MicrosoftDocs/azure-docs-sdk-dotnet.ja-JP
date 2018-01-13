<Type Name="IWithPrimaryPrivateIP" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPrivateIP">
  <TypeSignature Language="C#" Value="public interface IWithPrimaryPrivateIP" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPrimaryPrivateIP" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPrivateIP" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPrimaryPrivateIP" />
  <TypeSignature Language="F#" Value="type IWithPrimaryPrivateIP = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="46c42-101">仮想ネットワーク サブネット内のプライベート IP アドレスを指定できるように、ネットワーク インターフェイス定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="46c42-101">The stage of the network interface definition allowing to specify private IP address within a virtual network subnet.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithPrimaryPrivateIPAddressDynamic">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate WithPrimaryPrivateIPAddressDynamic ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate WithPrimaryPrivateIPAddressDynamic() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPrivateIP.WithPrimaryPrivateIPAddressDynamic" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPrimaryPrivateIPAddressDynamic () As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithPrimaryPrivateIPAddressDynamic : unit -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate" Usage="iWithPrimaryPrivateIP.WithPrimaryPrivateIPAddressDynamic " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="46c42-102">動的なプライベート IP アドレスの割り当て、ネットワーク インターフェイスのプライマリ IP 構成の指定した既存仮想ネットワーク サブネット内で有効にします。</span><span class="sxs-lookup"><span data-stu-id="46c42-102">Enables dynamic private IP address allocation within the specified existing virtual network subnet for the network interface's primary IP configuration.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="46c42-103">ネットワーク インターフェイスの定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="46c42-103">The next stage of network interface definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithPrimaryPrivateIPAddressStatic">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate WithPrimaryPrivateIPAddressStatic (string staticPrivateIPAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate WithPrimaryPrivateIPAddressStatic(string staticPrivateIPAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPrivateIP.WithPrimaryPrivateIPAddressStatic(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPrimaryPrivateIPAddressStatic (staticPrivateIPAddress As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithPrimaryPrivateIPAddressStatic : string -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate" Usage="iWithPrimaryPrivateIP.WithPrimaryPrivateIPAddressStatic staticPrivateIPAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="staticPrivateIPAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="staticPrivateIPAddress">
            <span data-ttu-id="46c42-104">ネットワーク インターフェイスに代入する指定されたサブネット内で静的 IP アドレス。</span><span class="sxs-lookup"><span data-stu-id="46c42-104">The static IP address within the specified subnet to assign to the network interface.</span></span>
            </param>
        <summary>
            <span data-ttu-id="46c42-105">ネットワーク インターフェイスのプライマリ IP 構成に指定した既存の仮想ネットワーク サブネット内にある指定の静的のプライベート IP アドレスを割り当てます。</span><span class="sxs-lookup"><span data-stu-id="46c42-105">Assigns the specified static private IP address within the specified existing virtual network subnet to the network interface's primary IP configuration.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="46c42-106">ネットワーク インターフェイスの定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="46c42-106">The next stage of network interface definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>