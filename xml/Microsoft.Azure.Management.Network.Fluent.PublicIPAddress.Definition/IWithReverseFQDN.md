<Type Name="IWithReverseFQDN" FullName="Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithReverseFQDN">
  <TypeSignature Language="C#" Value="public interface IWithReverseFQDN" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithReverseFQDN" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithReverseFQDN" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithReverseFQDN" />
  <TypeSignature Language="F#" Value="type IWithReverseFQDN = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e1c55-101">パブリック IP アドレス定義を指定する逆引き FQDN を許可します。</span><span class="sxs-lookup"><span data-stu-id="e1c55-101">A public IP address definition allowing the reverse FQDN to be specified.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithoutReverseFqdn">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithCreate WithoutReverseFqdn ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithCreate WithoutReverseFqdn() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithReverseFQDN.WithoutReverseFqdn" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutReverseFqdn () As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithoutReverseFqdn : unit -&gt; Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithCreate" Usage="iWithReverseFQDN.WithoutReverseFqdn " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e1c55-102">により、逆引き FQDN を使用しないことです。</span><span class="sxs-lookup"><span data-stu-id="e1c55-102">Ensures that no reverse FQDN will be used.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="e1c55-103">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="e1c55-103">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithReverseFqdn">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithCreate WithReverseFqdn (string reverseFQDN);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithCreate WithReverseFqdn(string reverseFQDN) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithReverseFQDN.WithReverseFqdn(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithReverseFqdn (reverseFQDN As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithReverseFqdn : string -&gt; Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithCreate" Usage="iWithReverseFQDN.WithReverseFqdn reverseFQDN" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reverseFQDN" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="reverseFQDN"><span data-ttu-id="e1c55-104">割り当てる逆引き FQDN。</span><span class="sxs-lookup"><span data-stu-id="e1c55-104">The reverse FQDN to assign.</span></span></param>
        <summary>
            <span data-ttu-id="e1c55-105">このパブリック IP アドレスに割り当てる逆引き FQDN を指定します。</span><span class="sxs-lookup"><span data-stu-id="e1c55-105">Specifies the reverse FQDN to assign to this public IP address.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="e1c55-106">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="e1c55-106">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>