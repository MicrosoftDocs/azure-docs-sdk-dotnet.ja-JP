<Type Name="IWithPrimaryNetworkSubnet" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryNetworkSubnet">
  <TypeSignature Language="C#" Value="public interface IWithPrimaryNetworkSubnet" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPrimaryNetworkSubnet" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryNetworkSubnet" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPrimaryNetworkSubnet" />
  <TypeSignature Language="F#" Value="type IWithPrimaryNetworkSubnet = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e34da-101">サブネットを指定するを許可するネットワーク インターフェイスの定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="e34da-101">The stage of the network interface definition allowing to specify subnet.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithSubnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPrivateIP WithSubnet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPrivateIP WithSubnet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryNetworkSubnet.WithSubnet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSubnet (name As String) As IWithPrimaryPrivateIP" />
      <MemberSignature Language="F#" Value="abstract member WithSubnet : string -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPrivateIP" Usage="iWithPrimaryNetworkSubnet.WithSubnet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPrivateIP</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="e34da-102">サブネットの名前です。</span><span class="sxs-lookup"><span data-stu-id="e34da-102">The subnet name.</span></span></param>
        <summary>
            <span data-ttu-id="e34da-103">ネットワーク インターフェイスのプライマリ IP 構成とサブネットを関連付けます。</span><span class="sxs-lookup"><span data-stu-id="e34da-103">Associate a subnet with the network interface's primary IP configuration.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="e34da-104">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="e34da-104">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>