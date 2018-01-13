<Type Name="IWithDomainVerification" FullName="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithDomainVerification">
  <TypeSignature Language="C#" Value="public interface IWithDomainVerification" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDomainVerification" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithDomainVerification" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDomainVerification" />
  <TypeSignature Language="F#" Value="type IWithDomainVerification = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="4d25b-101">アプリケーション サービス証明書の順序の定義を設定するドメインの検証メソッドを許可します。</span><span class="sxs-lookup"><span data-stu-id="4d25b-101">An app service certificate order definition allowing domain verification method to be set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithDomainVerification">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithKeyVault WithDomainVerification (Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain domain);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithKeyVault WithDomainVerification(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain domain) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithDomainVerification.WithDomainVerification(Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDomainVerification (domain As IAppServiceDomain) As IWithKeyVault" />
      <MemberSignature Language="F#" Value="abstract member WithDomainVerification : Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain -&gt; Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithKeyVault" Usage="iWithDomainVerification.WithDomainVerification domain" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithKeyVault</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="domain" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain" />
      </Parameters>
      <Docs>
        <param name="domain"><span data-ttu-id="4d25b-102">Azure では、ドメインを管理します。</span><span class="sxs-lookup"><span data-stu-id="4d25b-102">The Azure managed domain.</span></span></param>
        <summary>
            <span data-ttu-id="4d25b-103">Azure を指定します。 管理対象のドメイン、ドメインの所有権を確認します。</span><span class="sxs-lookup"><span data-stu-id="4d25b-103">Specifies the Azure managed domain to verify the ownership of the domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="4d25b-104">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="4d25b-104">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>