<Type Name="IWithDnsServer" FullName="Microsoft.Azure.Management.Network.Fluent.Network.Update.IWithDnsServer">
  <TypeSignature Language="C#" Value="public interface IWithDnsServer" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDnsServer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Network.Update.IWithDnsServer" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDnsServer" />
  <TypeSignature Language="F#" Value="type IWithDnsServer = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            DNS サーバーを指定できるように仮想ネットワークの更新の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithDnsServer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate WithDnsServer (string ipAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate WithDnsServer(string ipAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Network.Update.IWithDnsServer.WithDnsServer(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDnsServer (ipAddress As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithDnsServer : string -&gt; Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate" Usage="iWithDnsServer.WithDnsServer ipAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ipAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ipAddress">DNS サーバーの IP アドレス。</param>
        <summary>
            仮想ネットワークに関連付ける DNS サーバーの IP アドレスを指定します。
            このメソッドの効果は加法、つまりそれを使用するたび、新しい DNS サーバーがネットワークに追加します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>仮想ネットワークの更新の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>