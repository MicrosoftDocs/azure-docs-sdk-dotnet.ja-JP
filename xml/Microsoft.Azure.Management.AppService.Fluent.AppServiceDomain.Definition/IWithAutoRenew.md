<Type Name="IWithAutoRenew" FullName="Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Definition.IWithAutoRenew">
  <TypeSignature Language="C#" Value="public interface IWithAutoRenew" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAutoRenew" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Definition.IWithAutoRenew" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAutoRenew" />
  <TypeSignature Language="F#" Value="type IWithAutoRenew = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e6658-101">ドメイン定義ように自動更新設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="e6658-101">A domain definition allowing auto-renew setting to be set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithAutoRenewEnabled">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Definition.IWithCreate WithAutoRenewEnabled (bool autoRenew);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Definition.IWithCreate WithAutoRenewEnabled(bool autoRenew) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Definition.IWithAutoRenew.WithAutoRenewEnabled(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithAutoRenewEnabled (autoRenew As Boolean) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithAutoRenewEnabled : bool -&gt; Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Definition.IWithCreate" Usage="iWithAutoRenew.WithAutoRenewEnabled autoRenew" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="autoRenew" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="autoRenew"><span data-ttu-id="e6658-102">True の場合は、ドメインが自動的に更新する必要があります。</span><span class="sxs-lookup"><span data-stu-id="e6658-102">True if the domain should be automatically renewed.</span></span></param>
        <summary>
            <span data-ttu-id="e6658-103">かどうか、ドメイン書き換える必要がありますに自動的にあるときに指定します。 まもなく期限切れにします。</span><span class="sxs-lookup"><span data-stu-id="e6658-103">Specifies if the domain should be automatically renewed when it's about to expire.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="e6658-104">ドメイン定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="e6658-104">The next stage of domain definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>