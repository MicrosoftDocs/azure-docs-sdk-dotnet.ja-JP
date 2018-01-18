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
            <span data-ttu-id="41bc4-101">アプリケーション サービス証明書の順序の定義を設定する SKU を許可します。</span><span class="sxs-lookup"><span data-stu-id="41bc4-101">An app service certificate order definition allowing SKU to be set.</span></span>
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
            <span data-ttu-id="41bc4-102">標準である証明書の SKU を指定します。</span><span class="sxs-lookup"><span data-stu-id="41bc4-102">Specifies the SKU of the certificate to be standard.</span></span> <span data-ttu-id="41bc4-103">ホスト名、および www.hostname に SSL のサポートのみ提供されます。</span><span class="sxs-lookup"><span data-stu-id="41bc4-103">It will only provide SSL support to the hostname, and www.hostname.</span></span> <span data-ttu-id="41bc4-104">ワイルドカード型では、ホスト名の下にある任意のサブドメインに SSL のサポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="41bc4-104">Wildcard type will provide SSL support to any sub-domain under the hostname.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="41bc4-105">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="41bc4-105">The next stage of the definition.</span></span></return>
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
            <span data-ttu-id="41bc4-106">ワイルドカード証明書の SKU を指定します。</span><span class="sxs-lookup"><span data-stu-id="41bc4-106">Specifies the SKU of the certificate to be wildcard.</span></span> <span data-ttu-id="41bc4-107">ホスト名の下にある任意のサブドメインに SSL のサポートが提供されます。</span><span class="sxs-lookup"><span data-stu-id="41bc4-107">It will provide SSL support to any sub-domain under the hostname.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="41bc4-108">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="41bc4-108">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>