<Type Name="IWithSubnet&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.UpdateDefinition.IWithSubnet&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithSubnet&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSubnet`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.UpdateDefinition.IWithSubnet`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSubnet(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithSubnet&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="a80f7-101">最終的な Attachable.attach() の戻り値の型。</span><span class="sxs-lookup"><span data-stu-id="a80f7-101">The return type of the final  Attachable.attach().</span></span></typeparam>
    <summary>
            <span data-ttu-id="a80f7-102">サブネットを指定するを許可するネットワーク インターフェイス IP 構成定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="a80f7-102">The stage of the network interface IP configuration definition allowing to specify subnet.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithSubnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.UpdateDefinition.IWithPrivateIP&lt;ParentT&gt; WithSubnet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.UpdateDefinition.IWithPrivateIP`1&lt;!ParentT&gt; WithSubnet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.UpdateDefinition.IWithSubnet`1.WithSubnet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSubnet (name As String) As IWithPrivateIP(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithSubnet : string -&gt; Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.UpdateDefinition.IWithPrivateIP&lt;'ParentT&gt;" Usage="iWithSubnet.WithSubnet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.UpdateDefinition.IWithPrivateIP&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="a80f7-103">サブネットの名前です。</span><span class="sxs-lookup"><span data-stu-id="a80f7-103">The subnet name.</span></span></param>
        <summary>
            <span data-ttu-id="a80f7-104">ネットワーク インターフェイス IP 構成にサブネットを関連付けます。</span><span class="sxs-lookup"><span data-stu-id="a80f7-104">Associate a subnet with the network interface IP configuration.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a80f7-105">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="a80f7-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>