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
            <span data-ttu-id="0ca8b-101">指定する発信元アドレスを許可するネットワーク規則の説明の段階です。</span><span class="sxs-lookup"><span data-stu-id="0ca8b-101">The stage of the network rule description allowing the source address to be specified.</span></span>
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
        <param name="cidr"><span data-ttu-id="0ca8b-102">CIDR 表記で表される IP アドレスのプレフィックス。</span><span class="sxs-lookup"><span data-stu-id="0ca8b-102">An IP address prefix expressed in the CIDR notation.</span></span></param>
        <summary>
            <span data-ttu-id="0ca8b-103">この規則を適用するトラフィックの発信元アドレス プレフィックスを指定します。</span><span class="sxs-lookup"><span data-stu-id="0ca8b-103">Specifies the traffic source address prefix to which this rule applies.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="0ca8b-104">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="0ca8b-104">The next stage of the definition.</span></span></return>
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
            <span data-ttu-id="0ca8b-105">すべてのトラフィックの発信元アドレスにルールが適用されることを指定します。</span><span class="sxs-lookup"><span data-stu-id="0ca8b-105">Specifies that the rule applies to any traffic source address.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="0ca8b-106">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="0ca8b-106">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>