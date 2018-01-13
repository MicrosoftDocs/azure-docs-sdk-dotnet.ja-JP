<Type Name="IWithSourceAddress" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithSourceAddress">
  <TypeSignature Language="C#" Value="public interface IWithSourceAddress" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSourceAddress" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithSourceAddress" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSourceAddress" />
  <TypeSignature Language="F#" Value="type IWithSourceAddress = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            指定する発信元アドレスを許可するネットワーク規則の説明の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="FromAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate FromAddress (string cidr);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate FromAddress(string cidr) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithSourceAddress.FromAddress(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function FromAddress (cidr As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member FromAddress : string -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate" Usage="iWithSourceAddress.FromAddress cidr" />
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
        <param name="cidr">CIDR 表記で表される IP アドレスのプレフィックス。</param>
        <summary>
            この規則を適用するトラフィックの発信元アドレス プレフィックスを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="FromAnyAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate FromAnyAddress ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate FromAnyAddress() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithSourceAddress.FromAnyAddress" />
      <MemberSignature Language="VB.NET" Value="Public Function FromAnyAddress () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member FromAnyAddress : unit -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate" Usage="iWithSourceAddress.FromAnyAddress " />
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
            すべてのトラフィックの発信元アドレスにルールが適用されることを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>