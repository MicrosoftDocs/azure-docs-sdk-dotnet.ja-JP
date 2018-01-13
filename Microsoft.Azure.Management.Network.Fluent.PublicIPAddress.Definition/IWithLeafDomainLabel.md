<Type Name="IWithLeafDomainLabel" FullName="Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithLeafDomainLabel">
  <TypeSignature Language="C#" Value="public interface IWithLeafDomainLabel" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithLeafDomainLabel" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithLeafDomainLabel" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithLeafDomainLabel" />
  <TypeSignature Language="F#" Value="type IWithLeafDomainLabel = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            パブリック IP アドレス定義存在する場合は、リーフ ドメイン ラベルを指定できるようにします。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithLeafDomainLabel">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithCreate WithLeafDomainLabel (string dnsName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithCreate WithLeafDomainLabel(string dnsName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithLeafDomainLabel.WithLeafDomainLabel(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithLeafDomainLabel (dnsName As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithLeafDomainLabel : string -&gt; Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithCreate" Usage="iWithLeafDomainLabel.WithLeafDomainLabel dnsName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithCreate</ReturnType>
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
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutLeafDomainLabel">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithCreate WithoutLeafDomainLabel ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithCreate WithoutLeafDomainLabel() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithLeafDomainLabel.WithoutLeafDomainLabel" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutLeafDomainLabel () As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithoutLeafDomainLabel : unit -&gt; Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithCreate" Usage="iWithLeafDomainLabel.WithoutLeafDomainLabel " />
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
            リーフ ドメインのラベルを使用しないことをによりします。
            これは、このパブリック IP アドレスはしないようにドメイン名に関連付けられていることを意味します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>