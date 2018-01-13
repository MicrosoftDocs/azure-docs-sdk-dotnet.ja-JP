<Type Name="IWithLeafDomainLabel" FullName="Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IWithLeafDomainLabel">
  <TypeSignature Language="C#" Value="public interface IWithLeafDomainLabel" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithLeafDomainLabel" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IWithLeafDomainLabel" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithLeafDomainLabel" />
  <TypeSignature Language="F#" Value="type IWithLeafDomainLabel = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5a5e8-101">パブリック IP アドレスの更新を許可するラベルを変更して、リーフ ドメイン、存在する場合。</span><span class="sxs-lookup"><span data-stu-id="5a5e8-101">A public IP address update allowing to change the leaf domain label, if any.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithLeafDomainLabel">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IUpdate WithLeafDomainLabel (string dnsName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IUpdate WithLeafDomainLabel(string dnsName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IWithLeafDomainLabel.WithLeafDomainLabel(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithLeafDomainLabel (dnsName As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithLeafDomainLabel : string -&gt; Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IUpdate" Usage="iWithLeafDomainLabel.WithLeafDomainLabel dnsName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="dnsName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="dnsName"><span data-ttu-id="5a5e8-102">使用するリーフ ドメイン ラベルです。</span><span class="sxs-lookup"><span data-stu-id="5a5e8-102">The leaf domain label to use.</span></span> <span data-ttu-id="5a5e8-103">リーフのドメイン名の必要な命名規則に従ってこの必要があります。</span><span class="sxs-lookup"><span data-stu-id="5a5e8-103">This must follow the required naming convention for leaf domain names.</span></span></param>
        <summary>
            <span data-ttu-id="5a5e8-104">このパブリック IP アドレスに関連付けるリーフ ドメイン ラベルを指定します。</span><span class="sxs-lookup"><span data-stu-id="5a5e8-104">Specifies the leaf domain label to associate with this public IP address.</span></span>
            <span data-ttu-id="5a5e8-105">完全修飾ドメイン名 (FQDN) は、このラベルに、ドメインの残りの部分を追加することによって自動的に構築されます。</span><span class="sxs-lookup"><span data-stu-id="5a5e8-105">The fully qualified domain name (FQDN) will be constructed automatically by appending the rest of the domain to this label.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="5a5e8-106">リソースの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="5a5e8-106">The next stage of the resource update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutLeafDomainLabel">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IUpdate WithoutLeafDomainLabel ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IUpdate WithoutLeafDomainLabel() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IWithLeafDomainLabel.WithoutLeafDomainLabel" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutLeafDomainLabel () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutLeafDomainLabel : unit -&gt; Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IUpdate" Usage="iWithLeafDomainLabel.WithoutLeafDomainLabel " />
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
            <span data-ttu-id="5a5e8-107">リーフ ドメインのラベルを使用しないことをによりします。</span><span class="sxs-lookup"><span data-stu-id="5a5e8-107">Ensures that no leaf domain label will be used.</span></span>
            <span data-ttu-id="5a5e8-108">これは、このパブリック IP アドレスはしないようにドメイン名に関連付けられていることを意味します。</span><span class="sxs-lookup"><span data-stu-id="5a5e8-108">This means that this public IP address will not be associated with a domain name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="5a5e8-109">リソースの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="5a5e8-109">The next stage of the resource update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>