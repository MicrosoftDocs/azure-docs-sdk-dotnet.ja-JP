<Type Name="IWithDestinationPort" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithDestinationPort">
  <TypeSignature Language="C#" Value="public interface IWithDestinationPort" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDestinationPort" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithDestinationPort" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDestinationPort" />
  <TypeSignature Language="F#" Value="type IWithDestinationPort = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7375d-101">指定する宛先のポートを許可するネットワーク規則の説明の段階です。</span><span class="sxs-lookup"><span data-stu-id="7375d-101">The stage of the network rule description allowing the destination port(s) to be specified.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ToAnyPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate ToAnyPort ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate ToAnyPort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithDestinationPort.ToAnyPort" />
      <MemberSignature Language="VB.NET" Value="Public Function ToAnyPort () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member ToAnyPort : unit -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate" Usage="iWithDestinationPort.ToAnyPort " />
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
            <span data-ttu-id="7375d-102">任意の宛先ポートに適用するこのルールは、します。</span><span class="sxs-lookup"><span data-stu-id="7375d-102">Makes this rule apply to any destination port.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="7375d-103">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="7375d-103">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="ToPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate ToPort (int port);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate ToPort(int32 port) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithDestinationPort.ToPort(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function ToPort (port As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member ToPort : int -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate" Usage="iWithDestinationPort.ToPort port" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="port" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="port"><span data-ttu-id="7375d-104">送信先のポート番号。</span><span class="sxs-lookup"><span data-stu-id="7375d-104">The destination port number.</span></span></param>
        <summary>
            <span data-ttu-id="7375d-105">この規則を適用する宛先のポートを指定します。</span><span class="sxs-lookup"><span data-stu-id="7375d-105">Specifies the destination port to which this rule applies.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="7375d-106">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="7375d-106">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="ToPortRange">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate ToPortRange (int from, int to);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate ToPortRange(int32 from, int32 to) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithDestinationPort.ToPortRange(System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function ToPortRange (from As Integer, to As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member ToPortRange : int * int -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate" Usage="iWithDestinationPort.ToPortRange (from, to)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="from" Type="System.Int32" />
        <Parameter Name="to" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="from"><span data-ttu-id="7375d-107">開始ポート番号。</span><span class="sxs-lookup"><span data-stu-id="7375d-107">The starting port number.</span></span></param>
        <param name="to"><span data-ttu-id="7375d-108">終了ポート番号。</span><span class="sxs-lookup"><span data-stu-id="7375d-108">The ending port number.</span></span></param>
        <summary>
            <span data-ttu-id="7375d-109">この規則を適用する宛先ポートの範囲を指定します。</span><span class="sxs-lookup"><span data-stu-id="7375d-109">Specifies the destination port range to which this rule applies.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="7375d-110">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="7375d-110">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>