<Type Name="IWithRegistrantContact" FullName="Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Definition.IWithRegistrantContact">
  <TypeSignature Language="C#" Value="public interface IWithRegistrantContact" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithRegistrantContact" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Definition.IWithRegistrantContact" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithRegistrantContact" />
  <TypeSignature Language="F#" Value="type IWithRegistrantContact = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            設定にアクセスする登録を許可するドメインの定義。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineRegistrantContact">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.DomainContact.Definition.IBlank&lt;Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Definition.IWithCreate&gt; DefineRegistrantContact ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.DomainContact.Definition.IBlank`1&lt;class Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Definition.IWithCreate&gt; DefineRegistrantContact() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Definition.IWithRegistrantContact.DefineRegistrantContact" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineRegistrantContact () As IBlank(Of IWithCreate)" />
      <MemberSignature Language="F#" Value="abstract member DefineRegistrantContact : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.DomainContact.Definition.IBlank&lt;Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Definition.IWithCreate&gt;" Usage="iWithRegistrantContact.DefineRegistrantContact " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.DomainContact.Definition.IBlank&lt;Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Definition.IWithCreate&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            新しいドメインの連絡先の定義を開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>ドメインの最初の段階では、定義に問い合わせてください。</return>
      </Docs>
    </Member>
    <Member MemberName="WithRegistrantContact">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Definition.IWithCreate WithRegistrantContact (Microsoft.Azure.Management.AppService.Fluent.Models.Contact contact);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Definition.IWithCreate WithRegistrantContact(class Microsoft.Azure.Management.AppService.Fluent.Models.Contact contact) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Definition.IWithRegistrantContact.WithRegistrantContact(Microsoft.Azure.Management.AppService.Fluent.Models.Contact)" />
      <MemberSignature Language="F#" Value="abstract member WithRegistrantContact : Microsoft.Azure.Management.AppService.Fluent.Models.Contact -&gt; Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Definition.IWithCreate" Usage="iWithRegistrantContact.WithRegistrantContact contact" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="contact" Type="Microsoft.Azure.Management.AppService.Fluent.Models.Contact" />
      </Parameters>
      <Docs>
        <param name="contact">登録者に問い合わせてください。</param>
        <summary>
            登録者の連絡先を指定します。 既定では、これはまた、連絡先管理、課金、および技術です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>ドメイン定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>