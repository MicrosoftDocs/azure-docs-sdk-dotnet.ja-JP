<Type Name="IWithSslCert" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithSslCert">
  <TypeSignature Language="C#" Value="public interface IWithSslCert" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSslCert" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithSslCert" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSslCert" />
  <TypeSignature Language="F#" Value="type IWithSslCert = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            HTTPS リスナーで使用される SSL 証明書の追加を許可するアプリケーション ゲートウェイ定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineSslCertificate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaySslCertificate.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt; DefineSslCertificate (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaySslCertificate.Definition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt; DefineSslCertificate(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithSslCert.DefineSslCertificate(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineSslCertificate (name As String) As IBlank(Of IWithCreate)" />
      <MemberSignature Language="F#" Value="abstract member DefineSslCertificate : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaySslCertificate.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;" Usage="iWithSslCert.DefineSslCertificate name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaySslCertificate.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">証明書の一意の名前。</param>
        <summary>
            新しいアプリケーション ゲートウェイ SSL 証明書の HTTPS リスナーで使用するため、ゲートウェイに接続する定義を開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>証明書の定義の最初の段階です。</return>
      </Docs>
    </Member>
  </Members>
</Type>