<Type Name="IWithDomainPrivacy" FullName="Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Definition.IWithDomainPrivacy">
  <TypeSignature Language="C#" Value="public interface IWithDomainPrivacy" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDomainPrivacy" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Definition.IWithDomainPrivacy" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDomainPrivacy" />
  <TypeSignature Language="F#" Value="type IWithDomainPrivacy = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            設定するドメインのプライバシーを許可するドメインの定義。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithDomainPrivacyEnabled">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Definition.IWithCreate WithDomainPrivacyEnabled (bool domainPrivacy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Definition.IWithCreate WithDomainPrivacyEnabled(bool domainPrivacy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Definition.IWithDomainPrivacy.WithDomainPrivacyEnabled(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDomainPrivacyEnabled (domainPrivacy As Boolean) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithDomainPrivacyEnabled : bool -&gt; Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Definition.IWithCreate" Usage="iWithDomainPrivacy.WithDomainPrivacyEnabled domainPrivacy" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="domainPrivacy" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="domainPrivacy">ドメインのプライバシーがオンになっている場合は true。</param>
        <summary>
            登録者の連絡先に関する情報がパブリックに公開されているかどうかを指定します。
            ドメイン プライバシーが有効な場合は連絡先情報できなくパブリックにします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>ドメイン定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>