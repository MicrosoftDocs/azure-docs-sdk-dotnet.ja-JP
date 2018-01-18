<Type Name="IWithDomainPrivacy" FullName="Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Update.IWithDomainPrivacy">
  <TypeSignature Language="C#" Value="public interface IWithDomainPrivacy" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDomainPrivacy" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Update.IWithDomainPrivacy" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDomainPrivacy" />
  <TypeSignature Language="F#" Value="type IWithDomainPrivacy = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="59f29-101">設定するドメインのプライバシーを許可するドメインの定義。</span><span class="sxs-lookup"><span data-stu-id="59f29-101">A domain definition allowing domain privacy to be set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithDomainPrivacyEnabled">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Update.IUpdate WithDomainPrivacyEnabled (bool domainPrivacy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Update.IUpdate WithDomainPrivacyEnabled(bool domainPrivacy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Update.IWithDomainPrivacy.WithDomainPrivacyEnabled(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDomainPrivacyEnabled (domainPrivacy As Boolean) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithDomainPrivacyEnabled : bool -&gt; Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Update.IUpdate" Usage="iWithDomainPrivacy.WithDomainPrivacyEnabled domainPrivacy" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="domainPrivacy" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="domainPrivacy"><span data-ttu-id="59f29-102">ドメインのプライバシーがオンになっている場合は true。</span><span class="sxs-lookup"><span data-stu-id="59f29-102">True if domain privacy is turned on.</span></span></param>
        <summary>
            <span data-ttu-id="59f29-103">登録者の連絡先に関する情報がパブリックに公開されているかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="59f29-103">Specifies if the registrant contact information is exposed publicly.</span></span>
            <span data-ttu-id="59f29-104">ドメイン プライバシーが有効な場合は連絡先情報できなくパブリックにします。</span><span class="sxs-lookup"><span data-stu-id="59f29-104">If domain privacy is turned on, the contact information will NOT be available publicly.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="59f29-105">ドメイン定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="59f29-105">The next stage of domain definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>