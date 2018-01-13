<Type Name="IWithSslCert" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithSslCert">
  <TypeSignature Language="C#" Value="public interface IWithSslCert" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSslCert" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithSslCert" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSslCert" />
  <TypeSignature Language="F#" Value="type IWithSslCert = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            アプリケーション ゲートウェイの更新を許可する SSL 証明書を変更する段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineSslCertificate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaySslCertificate.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt; DefineSslCertificate (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaySslCertificate.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt; DefineSslCertificate(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithSslCert.DefineSslCertificate(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineSslCertificate (name As String) As IBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineSslCertificate : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaySslCertificate.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt;" Usage="iWithSslCert.DefineSslCertificate name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaySslCertificate.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">証明書の一意の名前。</param>
        <summary>
            新しいアプリケーション ゲートウェイ SSL 証明書の HTTPS リスナーのフロント エンドで使用するため、ゲートウェイに接続する定義を開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>証明書の定義の最初の段階です。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutCertificate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutCertificate (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutCertificate(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithSslCert.WithoutCertificate(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutCertificate (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutCertificate : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate" Usage="iWithSslCert.WithoutCertificate name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">削除する証明書の名前。</param>
        <summary>
            アプリケーション ゲートウェイから指定された SSL 証明書を削除します。
            他の設定で参照されている証明書を削除すると、アプリケーション ゲートウェイが分割することに注意してください。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutSslCertificate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutSslCertificate (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutSslCertificate(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithSslCert.WithoutSslCertificate(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutSslCertificate (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutSslCertificate : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate" Usage="iWithSslCert.WithoutSslCertificate name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>