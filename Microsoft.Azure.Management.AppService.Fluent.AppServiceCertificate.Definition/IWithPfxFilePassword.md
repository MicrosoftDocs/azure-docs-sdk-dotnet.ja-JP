<Type Name="IWithPfxFilePassword" FullName="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithPfxFilePassword">
  <TypeSignature Language="C#" Value="public interface IWithPfxFilePassword" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPfxFilePassword" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithPfxFilePassword" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPfxFilePassword" />
  <TypeSignature Language="F#" Value="type IWithPfxFilePassword = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            設定する PFX 証明書のパスワードを許可するアプリ サービスの証明書定義します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithPfxPassword">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithCreate WithPfxPassword (string password);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithCreate WithPfxPassword(string password) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithPfxFilePassword.WithPfxPassword(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPfxPassword (password As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithPfxPassword : string -&gt; Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithCreate" Usage="iWithPfxFilePassword.WithPfxPassword password" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="password" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="password">PFX 証明書のパスワード。</param>
        <summary>
            PFX 証明書にパスワードを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>