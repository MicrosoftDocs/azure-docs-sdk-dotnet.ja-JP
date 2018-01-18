<Type Name="IWithSslPassword&lt;ReturnT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.HasSslCertificate.UpdateDefinition.IWithSslPassword&lt;ReturnT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithSslPassword&lt;ReturnT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSslPassword`1&lt;ReturnT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.HasSslCertificate.UpdateDefinition.IWithSslPassword`1" />
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
    <typeparam name="ReturnT"><span data-ttu-id="5fc73-101">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="5fc73-101">The next stage of the definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="5fc73-102">インポートした SSL 証明書の秘密キーのパスワードを指定できるように、リソース定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="5fc73-102">The stage of a resource definition allowing to specify the password for the private key of the imported SSL certificate.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithSslCertificatePassword">
      <MemberSignature Language="C#" Value="public ReturnT WithSslCertificatePassword (string password);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !ReturnT WithSslCertificatePassword(string password) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.HasSslCertificate.UpdateDefinition.IWithSslPassword`1.WithSslCertificatePassword(System.String)" />
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
        <param name="password"><span data-ttu-id="5fc73-103">インポートされた PFX ファイルのパスワードです。</span><span class="sxs-lookup"><span data-stu-id="5fc73-103">The password of the imported PFX file.</span></span></param>
        <summary>
            <span data-ttu-id="5fc73-104">インポートした SSL 証明書の秘密キーを含む指定された PFX ファイルのパスワードを指定します。</span><span class="sxs-lookup"><span data-stu-id="5fc73-104">Specifies the password for the specified PFX file containing the private key of the imported SSL certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="5fc73-105">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="5fc73-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>