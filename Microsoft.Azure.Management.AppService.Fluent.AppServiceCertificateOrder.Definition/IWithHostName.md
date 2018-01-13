<Type Name="IWithHostName" FullName="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithHostName">
  <TypeSignature Language="C#" Value="public interface IWithHostName" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithHostName" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithHostName" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithHostName" />
  <TypeSignature Language="F#" Value="type IWithHostName = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            アプリケーション サービス証明書の順序の定義を設定するホスト名を許可します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithHostName">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithCertificateSku WithHostName (string hostName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithCertificateSku WithHostName(string hostName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithHostName.WithHostName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithHostName (hostName As String) As IWithCertificateSku" />
      <MemberSignature Language="F#" Value="abstract member WithHostName : string -&gt; Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithCertificateSku" Usage="iWithHostName.WithHostName hostName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithCertificateSku</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="hostName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="hostName">ベアのホスト名、"www"なし。 使用します。 ワイルドカード証明書である場合のプレフィックスです。</param>
        <summary>
            証明書のバインドにホスト名を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>