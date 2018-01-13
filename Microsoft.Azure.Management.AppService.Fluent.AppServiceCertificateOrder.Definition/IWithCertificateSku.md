<Type Name="IWithCertificateSku" FullName="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithCertificateSku">
  <TypeSignature Language="C#" Value="public interface IWithCertificateSku" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithCertificateSku" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithCertificateSku" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithCertificateSku" />
  <TypeSignature Language="F#" Value="type IWithCertificateSku = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            アプリケーション サービス証明書の順序の定義を設定する SKU を許可します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithStandardSku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithDomainVerificationFromWebApp WithStandardSku ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithDomainVerificationFromWebApp WithStandardSku() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithCertificateSku.WithStandardSku" />
      <MemberSignature Language="VB.NET" Value="Public Function WithStandardSku () As IWithDomainVerificationFromWebApp" />
      <MemberSignature Language="F#" Value="abstract member WithStandardSku : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithDomainVerificationFromWebApp" Usage="iWithCertificateSku.WithStandardSku " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithDomainVerificationFromWebApp</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            標準である証明書の SKU を指定します。 ホスト名、および www.hostname に SSL のサポートのみ提供されます。 ワイルドカード型では、ホスト名の下にある任意のサブドメインに SSL のサポートを提供します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithWildcardSku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithDomainVerification WithWildcardSku ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithDomainVerification WithWildcardSku() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithCertificateSku.WithWildcardSku" />
      <MemberSignature Language="VB.NET" Value="Public Function WithWildcardSku () As IWithDomainVerification" />
      <MemberSignature Language="F#" Value="abstract member WithWildcardSku : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithDomainVerification" Usage="iWithCertificateSku.WithWildcardSku " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithDomainVerification</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            ワイルドカード証明書の SKU を指定します。 ホスト名の下にある任意のサブドメインに SSL のサポートが提供されます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>