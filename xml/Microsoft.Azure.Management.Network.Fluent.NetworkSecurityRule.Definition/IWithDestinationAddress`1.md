<Type Name="IWithDestinationAddress&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithDestinationAddress&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithDestinationAddress&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDestinationAddress`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithDestinationAddress`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDestinationAddress(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithDestinationAddress&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="ce892-101">この定義をアタッチした後に戻るに親の定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="ce892-101">The stage of the parent definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="ce892-102">指定する宛先アドレスを許可するネットワーク ルールの定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="ce892-102">The stage of the network rule definition allowing the destination address to be specified.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ToAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithDestinationPort&lt;ParentT&gt; ToAddress (string cidr);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithDestinationPort`1&lt;!ParentT&gt; ToAddress(string cidr) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithDestinationAddress`1.ToAddress(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ToAddress (cidr As String) As IWithDestinationPort(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member ToAddress : string -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithDestinationPort&lt;'ParentT&gt;" Usage="iWithDestinationAddress.ToAddress cidr" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithDestinationPort&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cidr" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="cidr"><span data-ttu-id="ce892-103">CIDR 表記で表される IP アドレスの範囲です。</span><span class="sxs-lookup"><span data-stu-id="ce892-103">An IP address range expressed in the CIDR notation.</span></span></param>
        <summary>
            <span data-ttu-id="ce892-104">この規則を適用するトラフィックの宛先アドレス範囲を指定します。</span><span class="sxs-lookup"><span data-stu-id="ce892-104">Specifies the traffic destination address range to which this rule applies.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="ce892-105">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="ce892-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="ToAnyAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithDestinationPort&lt;ParentT&gt; ToAnyAddress ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithDestinationPort`1&lt;!ParentT&gt; ToAnyAddress() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithDestinationAddress`1.ToAnyAddress" />
      <MemberSignature Language="VB.NET" Value="Public Function ToAnyAddress () As IWithDestinationPort(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member ToAnyAddress : unit -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithDestinationPort&lt;'ParentT&gt;" Usage="iWithDestinationAddress.ToAnyAddress " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithDestinationPort&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ce892-106">すべてのトラフィックの宛先アドレスに適用するルールは、します。</span><span class="sxs-lookup"><span data-stu-id="ce892-106">Makes the rule apply to any traffic destination address.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="ce892-107">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="ce892-107">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>