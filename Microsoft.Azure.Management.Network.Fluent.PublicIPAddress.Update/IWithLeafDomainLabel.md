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
            パブリック IP アドレスの更新を許可するラベルを変更して、リーフ ドメイン、存在する場合。
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
        <param name="dnsName">使用するリーフ ドメイン ラベルです。 リーフのドメイン名の必要な命名規則に従ってこの必要があります。</param>
        <summary>
            このパブリック IP アドレスに関連付けるリーフ ドメイン ラベルを指定します。
            完全修飾ドメイン名 (FQDN) は、このラベルに、ドメインの残りの部分を追加することによって自動的に構築されます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>リソースの更新の次のステージ。</return>
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
            リーフ ドメインのラベルを使用しないことをによりします。
            これは、このパブリック IP アドレスはしないようにドメイン名に関連付けられていることを意味します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>リソースの更新の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>