<Type Name="IWithPassword&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaySslCertificate.Definition.IWithPassword&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithPassword&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPassword`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaySslCertificate.Definition.IWithPassword`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPassword(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithPassword&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT">アタッチした後に戻るに親アプリケーション ゲートウェイの段階です。</typeparam>
    <summary>
            SSL のステージでは、定義できるように、秘密キー (PFX) 証明書のコンテンツのパスワードを指定する証明書します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithPfxPassword">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaySslCertificate.Definition.IWithAttach&lt;ParentT&gt; WithPfxPassword (string password);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaySslCertificate.Definition.IWithAttach`1&lt;!ParentT&gt; WithPfxPassword(string password) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaySslCertificate.Definition.IWithPassword`1.WithPfxPassword(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPfxPassword (password As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithPfxPassword : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaySslCertificate.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithPassword.WithPfxPassword password" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaySslCertificate.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="password" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="password">パスワード。</param>
        <summary>
            現在の SSL 証明書の指定された PFX コンテンツの保護に使用するパスワードを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>