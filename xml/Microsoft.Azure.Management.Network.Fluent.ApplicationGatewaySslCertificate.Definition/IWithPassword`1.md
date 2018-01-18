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
    <typeparam name="ParentT"><span data-ttu-id="1f985-101">アタッチした後に戻るに親アプリケーション ゲートウェイの段階です。</span><span class="sxs-lookup"><span data-stu-id="1f985-101">The stage of the parent application gateway to return to after attaching.</span></span></typeparam>
    <summary>
            <span data-ttu-id="1f985-102">SSL のステージでは、定義できるように、秘密キー (PFX) 証明書のコンテンツのパスワードを指定する証明書します。</span><span class="sxs-lookup"><span data-stu-id="1f985-102">The stage of an SSL certificate definition allowing to specify the password for the private key (PFX) content of the certificate.</span></span>
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
        <param name="password"><span data-ttu-id="1f985-103">パスワード。</span><span class="sxs-lookup"><span data-stu-id="1f985-103">A password.</span></span></param>
        <summary>
            <span data-ttu-id="1f985-104">現在の SSL 証明書の指定された PFX コンテンツの保護に使用するパスワードを指定します。</span><span class="sxs-lookup"><span data-stu-id="1f985-104">Specifies the password currently used to protect the provided PFX content of the SSL certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="1f985-105">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="1f985-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>