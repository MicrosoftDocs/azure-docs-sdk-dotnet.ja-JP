<Type Name="IWithDestinationAddress" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithDestinationAddress">
  <TypeSignature Language="C#" Value="public interface IWithDestinationAddress" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDestinationAddress" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithDestinationAddress" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDestinationAddress" />
  <TypeSignature Language="F#" Value="type IWithDestinationAddress = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            指定する宛先アドレスを許可するネットワーク規則の説明の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ToAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate ToAddress (string cidr);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate ToAddress(string cidr) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithDestinationAddress.ToAddress(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ToAddress (cidr As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member ToAddress : string -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate" Usage="iWithDestinationAddress.ToAddress cidr" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cidr" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="cidr">CIDR 表記で表される IP アドレスの範囲です。</param>
        <summary>
            この規則を適用するトラフィックの宛先アドレス範囲を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="ToAnyAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate ToAnyAddress ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate ToAnyAddress() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithDestinationAddress.ToAnyAddress" />
      <MemberSignature Language="VB.NET" Value="Public Function ToAnyAddress () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member ToAnyAddress : unit -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate" Usage="iWithDestinationAddress.ToAnyAddress " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            すべてのトラフィックの宛先アドレスに適用するルールは、します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>