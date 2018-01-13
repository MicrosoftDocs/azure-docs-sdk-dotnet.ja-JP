<Type Name="IWithSslCertificate&lt;ReturnT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.HasSslCertificate.UpdateDefinition.IWithSslCertificate&lt;ReturnT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithSslCertificate&lt;ReturnT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSslCertificate`1&lt;ReturnT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.HasSslCertificate.UpdateDefinition.IWithSslCertificate`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSslCertificate(Of ReturnT)" />
  <TypeSignature Language="F#" Value="type IWithSslCertificate&lt;'ReturnT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ReturnT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ReturnT">定義の次のステージ。</typeparam>
    <summary>
            それに関連付ける SSL 証明書を指定できるように、リソース定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithSslCertificate">
      <MemberSignature Language="C#" Value="public ReturnT WithSslCertificate (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !ReturnT WithSslCertificate(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.HasSslCertificate.UpdateDefinition.IWithSslCertificate`1.WithSslCertificate(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSslCertificate (name As String) As ReturnT" />
      <MemberSignature Language="F#" Value="abstract member WithSslCertificate : string -&gt; 'ReturnT" Usage="iWithSslCertificate.WithSslCertificate name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>ReturnT</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">既存の SSL 証明書の名前。</param>
        <summary>
            このリソースに関連付ける SSL 証明書を指定します。
            証明書がまだ存在しない場合は、親のリソース定義のオプションの一部で定義する必要があります。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithSslCertificateFromPfxFile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.HasSslCertificate.UpdateDefinition.IWithSslPassword&lt;ReturnT&gt; WithSslCertificateFromPfxFile (System.IO.FileInfo pfxFile);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.HasSslCertificate.UpdateDefinition.IWithSslPassword`1&lt;!ReturnT&gt; WithSslCertificateFromPfxFile(class System.IO.FileInfo pfxFile) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.HasSslCertificate.UpdateDefinition.IWithSslCertificate`1.WithSslCertificateFromPfxFile(System.IO.FileInfo)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSslCertificateFromPfxFile (pfxFile As FileInfo) As IWithSslPassword(Of ReturnT)" />
      <MemberSignature Language="F#" Value="abstract member WithSslCertificateFromPfxFile : System.IO.FileInfo -&gt; Microsoft.Azure.Management.Network.Fluent.HasSslCertificate.UpdateDefinition.IWithSslPassword&lt;'ReturnT&gt;" Usage="iWithSslCertificate.WithSslCertificateFromPfxFile pfxFile" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.HasSslCertificate.UpdateDefinition.IWithSslPassword&lt;ReturnT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="pfxFile" Type="System.IO.FileInfo" />
      </Parameters>
      <Docs>
        <param name="pfxFile">既存の PFX ファイルです。</param>
        <summary>
            このリソースに関連付けられているから SSL 証明書をインポートする PFX ファイルを指定します。
            自動生成の名前を使用して、証明書の名前です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <throws>指定されたファイルに関する問題がある場合に io 例外。</throws>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>