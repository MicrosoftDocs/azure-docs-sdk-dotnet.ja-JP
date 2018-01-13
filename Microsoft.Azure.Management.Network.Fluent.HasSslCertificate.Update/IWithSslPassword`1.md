<Type Name="IWithSslPassword&lt;ReturnT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.HasSslCertificate.Update.IWithSslPassword&lt;ReturnT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithSslPassword&lt;ReturnT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSslPassword`1&lt;ReturnT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.HasSslCertificate.Update.IWithSslPassword`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSslPassword(Of ReturnT)" />
  <TypeSignature Language="F#" Value="type IWithSslPassword&lt;'ReturnT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ReturnT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ReturnT">更新プログラムの次のステージ。</typeparam>
    <summary>
            インポートした SSL 証明書の秘密キーのパスワードを指定できるようにリソース更新の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithSslCertificatePassword">
      <MemberSignature Language="C#" Value="public ReturnT WithSslCertificatePassword (string password);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !ReturnT WithSslCertificatePassword(string password) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.HasSslCertificate.Update.IWithSslPassword`1.WithSslCertificatePassword(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSslCertificatePassword (password As String) As ReturnT" />
      <MemberSignature Language="F#" Value="abstract member WithSslCertificatePassword : string -&gt; 'ReturnT" Usage="iWithSslPassword.WithSslCertificatePassword password" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>ReturnT</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="password" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="password">インポートされた PFX ファイルのパスワードです。</param>
        <summary>
            インポートした SSL 証明書の秘密キーを含む指定された PFX ファイルのパスワードを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>