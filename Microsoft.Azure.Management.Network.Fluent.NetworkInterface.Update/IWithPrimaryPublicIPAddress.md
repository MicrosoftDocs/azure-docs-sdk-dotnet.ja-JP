<Type Name="IWithPrimaryPublicIPAddress" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IWithPrimaryPublicIPAddress">
  <TypeSignature Language="C#" Value="public interface IWithPrimaryPublicIPAddress" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPrimaryPublicIPAddress" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IWithPrimaryPublicIPAddress" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPrimaryPublicIPAddress" />
  <TypeSignature Language="F#" Value="type IWithPrimaryPublicIPAddress = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            ネットワーク インターフェイスのステージでは、パブリック IP アドレスを関連付けることのプライマリ IP 構成を許可するを更新します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingPrimaryPublicIPAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithExistingPrimaryPublicIPAddress (Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress publicIPAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithExistingPrimaryPublicIPAddress(class Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress publicIPAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IWithPrimaryPublicIPAddress.WithExistingPrimaryPublicIPAddress(Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingPrimaryPublicIPAddress (publicIPAddress As IPublicIPAddress) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingPrimaryPublicIPAddress : Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate" Usage="iWithPrimaryPublicIPAddress.WithExistingPrimaryPublicIPAddress publicIPAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="publicIPAddress" Type="Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress" />
      </Parameters>
      <Docs>
        <param name="publicIPAddress">既存のパブリック IP アドレス。</param>
        <summary>
            ネットワーク インターフェイスのプライマリ IP 構成を既存のパブリック IP アドレスを関連付けます。
            既存がある場合は、パブリック IP の関連付けをしは、このいる削除されます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>ネットワーク インターフェイスの更新の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewPrimaryPublicIPAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithNewPrimaryPublicIPAddress ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithNewPrimaryPublicIPAddress() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IWithPrimaryPublicIPAddress.WithNewPrimaryPublicIPAddress" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewPrimaryPublicIPAddress () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewPrimaryPublicIPAddress : unit -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate" Usage="iWithPrimaryPublicIPAddress.WithNewPrimaryPublicIPAddress " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            同じリージョンと、リソースとグループに新しいパブリック IP アドレスを作成し、ネットワーク インターフェイスのプライマリ IP 構成に関連付けます。
            ブックをこのいる削除される、既存のパブリック IP の関連付けがある場合、内部名とパブリック IP アドレスの DNS ラベルをネットワーク インターフェイスの名前から導き出されます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>ネットワーク インターフェイスの更新の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewPrimaryPublicIPAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithNewPrimaryPublicIPAddress (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress&gt; creatable);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithNewPrimaryPublicIPAddress(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress&gt; creatable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IWithPrimaryPublicIPAddress.WithNewPrimaryPublicIPAddress(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewPrimaryPublicIPAddress (creatable As ICreatable(Of IPublicIPAddress)) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewPrimaryPublicIPAddress : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress&gt; -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate" Usage="iWithPrimaryPublicIPAddress.WithNewPrimaryPublicIPAddress creatable" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="creatable" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress&gt;" />
      </Parameters>
      <Docs>
        <param name="creatable">新しいパブリック IP の作成可能な定義です。</param>
        <summary>
            指定された定義に基づくネットワーク インターフェイスのプライマリ IP 構成を関連付けるには新しいパブリック IP アドレスを作成します。
            パブリックがある場合は、プライマリ IP 構成に関連付けられている IP、このいる削除されます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>ネットワーク インターフェイスの更新の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewPrimaryPublicIPAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithNewPrimaryPublicIPAddress (string leafDnsLabel);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithNewPrimaryPublicIPAddress(string leafDnsLabel) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IWithPrimaryPublicIPAddress.WithNewPrimaryPublicIPAddress(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewPrimaryPublicIPAddress (leafDnsLabel As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewPrimaryPublicIPAddress : string -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate" Usage="iWithPrimaryPublicIPAddress.WithNewPrimaryPublicIPAddress leafDnsLabel" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="leafDnsLabel" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="leafDnsLabel">リーフ ドメイン ラベルです。</param>
        <summary>
            指定した DNS ラベルで、リソースと同じリージョンとグループに新しいパブリック IP アドレスを作成し、ネットワーク インターフェイスのプライマリ IP 構成に関連付けます。
            パブリック IP アドレスの内部名は、このいる削除される、既存のパブリック IP の関連付けがある場合、DNS ラベルから導き出されます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>ネットワーク インターフェイスの更新の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutPrimaryPublicIPAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithoutPrimaryPublicIPAddress ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithoutPrimaryPublicIPAddress() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IWithPrimaryPublicIPAddress.WithoutPrimaryPublicIPAddress" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutPrimaryPublicIPAddress () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutPrimaryPublicIPAddress : unit -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate" Usage="iWithPrimaryPublicIPAddress.WithoutPrimaryPublicIPAddress " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            ネットワーク インターフェイスのプライマリ IP 構成に関連付けられているすべてのパブリック IP を削除することを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>ネットワーク インターフェイスの更新の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>