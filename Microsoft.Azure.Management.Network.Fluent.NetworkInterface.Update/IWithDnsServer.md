<Type Name="IWithDnsServer" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IWithDnsServer">
  <TypeSignature Language="C#" Value="public interface IWithDnsServer" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDnsServer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IWithDnsServer" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDnsServer" />
  <TypeSignature Language="F#" Value="type IWithDnsServer = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            ネットワーク インターフェイスの更新を許可する DNS サーバーを指定の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithAzureDnsServer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithAzureDnsServer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithAzureDnsServer() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IWithDnsServer.WithAzureDnsServer" />
      <MemberSignature Language="VB.NET" Value="Public Function WithAzureDnsServer () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithAzureDnsServer : unit -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate" Usage="iWithDnsServer.WithAzureDnsServer " />
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
            ネットワーク インターフェイスの既定の Azure の DNS サーバーを使用するように指定します。
            Azure DNS を使用してサーバーではこのネットワーク インターフェイスに関連付けられているカスタム DNS サーバーが削除されます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>ネットワーク インターフェイスの更新の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithDnsServer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithDnsServer (string ipAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithDnsServer(string ipAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IWithDnsServer.WithDnsServer(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDnsServer (ipAddress As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithDnsServer : string -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate" Usage="iWithDnsServer.WithDnsServer ipAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ipAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ipAddress">DNS サーバーの IP アドレス。</param>
        <summary>
            ネットワーク インターフェイスに関連付けるカスタムの DNS サーバーの IP アドレスを指定します。
            このメソッドの効果は加法、つまりたびにこれを使用すると、新しい dns サーバーは追加ネットワーク インターフェイスにします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>ネットワーク インターフェイスの更新の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutDnsServer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithoutDnsServer (string ipAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithoutDnsServer(string ipAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IWithDnsServer.WithoutDnsServer(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutDnsServer (ipAddress As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutDnsServer : string -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate" Usage="iWithDnsServer.WithoutDnsServer ipAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ipAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ipAddress">DNS サーバーの IP アドレス。</param>
        <summary>
            ネットワーク インターフェイスに関連付けられている DNS サーバーを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>ネットワーク インターフェイスの更新の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>