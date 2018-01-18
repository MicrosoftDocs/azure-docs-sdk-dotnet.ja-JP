<Type Name="IWithReverseFQDN" FullName="Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IWithReverseFQDN">
  <TypeSignature Language="C#" Value="public interface IWithReverseFQDN" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithReverseFQDN" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IWithReverseFQDN" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithReverseFQDN" />
  <TypeSignature Language="F#" Value="type IWithReverseFQDN = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3eda6-101">パブリック IP アドレスは、逆方向 FQDN を変更する許可を更新します。</span><span class="sxs-lookup"><span data-stu-id="3eda6-101">A public IP address update allowing the reverse FQDN to be changed.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithoutReverseFqdn">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IUpdate WithoutReverseFqdn ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IUpdate WithoutReverseFqdn() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IWithReverseFQDN.WithoutReverseFqdn" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutReverseFqdn () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutReverseFqdn : unit -&gt; Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IUpdate" Usage="iWithReverseFQDN.WithoutReverseFqdn " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3eda6-102">により、逆引き FQDN を使用しないことです。</span><span class="sxs-lookup"><span data-stu-id="3eda6-102">Ensures that no reverse FQDN will be used.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="3eda6-103">リソースの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="3eda6-103">The next stage of the resource update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithReverseFqdn">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IUpdate WithReverseFqdn (string reverseFQDN);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IUpdate WithReverseFqdn(string reverseFQDN) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IWithReverseFQDN.WithReverseFqdn(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithReverseFqdn (reverseFQDN As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithReverseFqdn : string -&gt; Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IUpdate" Usage="iWithReverseFQDN.WithReverseFqdn reverseFQDN" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reverseFQDN" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="reverseFQDN"><span data-ttu-id="3eda6-104">割り当てる逆引き FQDN。</span><span class="sxs-lookup"><span data-stu-id="3eda6-104">The reverse FQDN to assign.</span></span></param>
        <summary>
            <span data-ttu-id="3eda6-105">このパブリック IP アドレスに割り当てる逆引き FQDN を指定します。</span><span class="sxs-lookup"><span data-stu-id="3eda6-105">Specifies the reverse FQDN to assign to this public IP address.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="3eda6-106">リソースの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="3eda6-106">The next stage of the resource update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>