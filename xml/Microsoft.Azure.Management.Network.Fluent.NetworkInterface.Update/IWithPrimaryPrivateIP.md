<Type Name="IWithPrimaryPrivateIP" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IWithPrimaryPrivateIP">
  <TypeSignature Language="C#" Value="public interface IWithPrimaryPrivateIP" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPrimaryPrivateIP" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IWithPrimaryPrivateIP" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPrimaryPrivateIP" />
  <TypeSignature Language="F#" Value="type IWithPrimaryPrivateIP = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="200e1-101">ネットワーク インターフェイスの更新を許可する仮想ネットワーク サブネット内のプライベート IP アドレスを指定の段階です。</span><span class="sxs-lookup"><span data-stu-id="200e1-101">The stage of the network interface update allowing to specify private IP address within a virtual network subnet.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithPrimaryPrivateIPAddressDynamic">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithPrimaryPrivateIPAddressDynamic ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithPrimaryPrivateIPAddressDynamic() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IWithPrimaryPrivateIP.WithPrimaryPrivateIPAddressDynamic" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPrimaryPrivateIPAddressDynamic () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithPrimaryPrivateIPAddressDynamic : unit -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate" Usage="iWithPrimaryPrivateIP.WithPrimaryPrivateIPAddressDynamic " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="200e1-102">動的なプライベート IP アドレスの割り当て、ネットワーク インターフェイスのプライマリ IP 構成の指定した既存仮想ネットワーク サブネット内で有効にします。</span><span class="sxs-lookup"><span data-stu-id="200e1-102">Enables dynamic private IP address allocation within the specified existing virtual network subnet for the network interface's primary IP configuration.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="200e1-103">ネットワーク インターフェイスの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="200e1-103">The next stage of network interface update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithPrimaryPrivateIPAddressStatic">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithPrimaryPrivateIPAddressStatic (string staticPrivateIPAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithPrimaryPrivateIPAddressStatic(string staticPrivateIPAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IWithPrimaryPrivateIP.WithPrimaryPrivateIPAddressStatic(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPrimaryPrivateIPAddressStatic (staticPrivateIPAddress As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithPrimaryPrivateIPAddressStatic : string -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate" Usage="iWithPrimaryPrivateIP.WithPrimaryPrivateIPAddressStatic staticPrivateIPAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="staticPrivateIPAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="staticPrivateIPAddress">
            <span data-ttu-id="200e1-104">割り当てるプライマリ IP 構成に指定されたサブネット内で静的 IP アドレス。</span><span class="sxs-lookup"><span data-stu-id="200e1-104">The static IP address within the specified subnet to assign to the primary IP configuration.</span></span>
            </param>
        <summary>
            <span data-ttu-id="200e1-105">ネットワーク インターフェイスのプライマリ IP 構成に指定した既存の仮想ネットワーク サブネット内にある指定の静的のプライベート IP アドレスを割り当てます。</span><span class="sxs-lookup"><span data-stu-id="200e1-105">Assigns the specified static private IP address within the specified existing virtual network subnet to the network interface's primary IP configuration.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="200e1-106">ネットワーク インターフェイスの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="200e1-106">The next stage of network interface update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>