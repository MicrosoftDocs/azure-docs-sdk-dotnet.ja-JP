<Type Name="IWithDomainVerificationFromWebApp" FullName="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithDomainVerificationFromWebApp">
  <TypeSignature Language="C#" Value="public interface IWithDomainVerificationFromWebApp : Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithDomainVerification" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDomainVerificationFromWebApp implements class Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithDomainVerification" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithDomainVerificationFromWebApp" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDomainVerificationFromWebApp&#xA;Implements IWithDomainVerification" />
  <TypeSignature Language="F#" Value="type IWithDomainVerificationFromWebApp = interface&#xA;    interface IWithDomainVerification" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithDomainVerification</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            アプリケーション サービス証明書の順序の定義以上のドメインを設定する検証メソッドを許可します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithWebAppVerification">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithKeyVault WithWebAppVerification (Microsoft.Azure.Management.AppService.Fluent.IWebAppBase webApp);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithKeyVault WithWebAppVerification(class Microsoft.Azure.Management.AppService.Fluent.IWebAppBase webApp) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithDomainVerificationFromWebApp.WithWebAppVerification(Microsoft.Azure.Management.AppService.Fluent.IWebAppBase)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithWebAppVerification (webApp As IWebAppBase) As IWithKeyVault" />
      <MemberSignature Language="F#" Value="abstract member WithWebAppVerification : Microsoft.Azure.Management.AppService.Fluent.IWebAppBase -&gt; Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithKeyVault" Usage="iWithDomainVerificationFromWebApp.WithWebAppVerification webApp" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithKeyVault</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="webApp" Type="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase" />
      </Parameters>
      <Docs>
        <param name="webApp">Web アプリは、ホスト名にバインドされます。</param>
        <summary>
            ドメインの所有権を確認する web アプリを指定します。 Web アプリは、証明書のホスト名にバインドする必要があります。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>