<Type Name="IWithIPAddress" FullName="Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithIPAddress">
  <TypeSignature Language="C#" Value="public interface IWithIPAddress" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithIPAddress" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithIPAddress" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithIPAddress" />
  <TypeSignature Language="F#" Value="type IWithIPAddress = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0cc61-101">パブリック IP アドレス定義を (静的または動的) に IP の割り当て方法を設定できるようにします。</span><span class="sxs-lookup"><span data-stu-id="0cc61-101">A public IP address definition allowing to set the IP allocation method (static or dynamic).</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithDynamicIP">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithCreate WithDynamicIP ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithCreate WithDynamicIP() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithIPAddress.WithDynamicIP" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDynamicIP () As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithDynamicIP : unit -&gt; Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithCreate" Usage="iWithIPAddress.WithDynamicIP " />
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
            <span data-ttu-id="0cc61-102">動的 IP アドレスの割り当てを有効にします。</span><span class="sxs-lookup"><span data-stu-id="0cc61-102">Enables dynamic IP address allocation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="0cc61-103">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="0cc61-103">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithStaticIP">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithCreate WithStaticIP ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithCreate WithStaticIP() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithIPAddress.WithStaticIP" />
      <MemberSignature Language="VB.NET" Value="Public Function WithStaticIP () As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithStaticIP : unit -&gt; Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithCreate" Usage="iWithIPAddress.WithStaticIP " />
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
            <span data-ttu-id="0cc61-104">静的 IP アドレスの割り当てを有効にします。</span><span class="sxs-lookup"><span data-stu-id="0cc61-104">Enables static IP address allocation.</span></span>
            <span data-ttu-id="0cc61-105">このリソースに対する Azure によって割り当てられる実際の IP アドレスを取得するパブリック IP アドレスを作成した後は、PublicIPAddress.ipAddress() を使用します。</span><span class="sxs-lookup"><span data-stu-id="0cc61-105">Use  PublicIPAddress.ipAddress() after the public IP address is created to obtain the actual IP address allocated for this resource by Azure.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="0cc61-106">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="0cc61-106">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>