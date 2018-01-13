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
            ネットワーク インターフェイスの更新を許可する仮想ネットワーク サブネット内のプライベート IP アドレスを指定の段階です。
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
            動的なプライベート IP アドレスの割り当て、ネットワーク インターフェイスのプライマリ IP 構成の指定した既存仮想ネットワーク サブネット内で有効にします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>ネットワーク インターフェイスの更新の次のステージ。</return>
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
            割り当てるプライマリ IP 構成に指定されたサブネット内で静的 IP アドレス。
            </param>
        <summary>
            ネットワーク インターフェイスのプライマリ IP 構成に指定した既存の仮想ネットワーク サブネット内にある指定の静的のプライベート IP アドレスを割り当てます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>ネットワーク インターフェイスの更新の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>