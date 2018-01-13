<Type Name="IWithCertificate&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithCertificate&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithCertificate&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithCertificate`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithCertificate`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithCertificate(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithCertificate&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT">この定義をアタッチした後に戻るに親の定義の段階です。</typeparam>
    <summary>
            証明書情報を指定するホスト名の SSL バインディング定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingAppServiceCertificateOrder">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithSslType&lt;ParentT&gt; WithExistingAppServiceCertificateOrder (Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder certificateOrder);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithSslType`1&lt;!ParentT&gt; WithExistingAppServiceCertificateOrder(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder certificateOrder) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithCertificate`1.WithExistingAppServiceCertificateOrder(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingAppServiceCertificateOrder (certificateOrder As IAppServiceCertificateOrder) As IWithSslType(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithExistingAppServiceCertificateOrder : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder -&gt; Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithSslType&lt;'ParentT&gt;" Usage="iWithCertificate.WithExistingAppServiceCertificateOrder certificateOrder" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithSslType&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="certificateOrder" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder" />
      </Parameters>
      <Docs>
        <param name="certificateOrder">すぐに使用できる証明書の順序です。</param>
        <summary>
            使用にすぐに使用できる証明書の順序を指定します。 これは、ワイルドカード証明書を再利用するために便利です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewStandardSslCertificateOrder">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithKeyVault&lt;ParentT&gt; WithNewStandardSslCertificateOrder (string certificateOrderName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithKeyVault`1&lt;!ParentT&gt; WithNewStandardSslCertificateOrder(string certificateOrderName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithCertificate`1.WithNewStandardSslCertificateOrder(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewStandardSslCertificateOrder (certificateOrderName As String) As IWithKeyVault(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithNewStandardSslCertificateOrder : string -&gt; Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithKeyVault&lt;'ParentT&gt;" Usage="iWithCertificate.WithNewStandardSslCertificateOrder certificateOrderName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithKeyVault&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="certificateOrderName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="certificateOrderName">証明書の順序の名前。</param>
        <summary>
            ホスト名を使用する新しい App Service 証明書の順序に配置します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithPfxCertificateToUpload">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithSslType&lt;ParentT&gt; WithPfxCertificateToUpload (string pfxFile, string password);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithSslType`1&lt;!ParentT&gt; WithPfxCertificateToUpload(string pfxFile, string password) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithCertificate`1.WithPfxCertificateToUpload(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPfxCertificateToUpload (pfxFile As String, password As String) As IWithSslType(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithPfxCertificateToUpload : string * string -&gt; Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithSslType&lt;'ParentT&gt;" Usage="iWithCertificate.WithPfxCertificateToUpload (pfxFile, password)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithSslType&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="pfxFile" Type="System.String" />
        <Parameter Name="password" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="pfxFile">アップロードする PFX 証明書ファイル。</param>
        <param name="password">証明書のパスワード。</param>
        <summary>
            PFX 証明書をアップロードします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>