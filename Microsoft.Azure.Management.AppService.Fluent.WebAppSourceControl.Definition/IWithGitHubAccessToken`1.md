<Type Name="IWithGitHubAccessToken&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IWithGitHubAccessToken&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithGitHubAccessToken&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithGitHubAccessToken`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IWithGitHubAccessToken`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithGitHubAccessToken(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithGitHubAccessToken&lt;'ParentT&gt; = interface" />
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
            Web アプリ ソース コントロールの定義を指定する GitHub のアクセス トークンを許可します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithGitHubAccessToken">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IGitHubWithAttach&lt;ParentT&gt; WithGitHubAccessToken (string personalAccessToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IGitHubWithAttach`1&lt;!ParentT&gt; WithGitHubAccessToken(string personalAccessToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IWithGitHubAccessToken`1.WithGitHubAccessToken(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithGitHubAccessToken (personalAccessToken As String) As IGitHubWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithGitHubAccessToken : string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IGitHubWithAttach&lt;'ParentT&gt;" Usage="iWithGitHubAccessToken.WithGitHubAccessToken personalAccessToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IGitHubWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="personalAccessToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="personalAccessToken">GitHub から個人用アクセス トークンです。</param>
        <summary>
            GitHub 個人用アクセス トークンを指定します。 Https://github.com/settings/tokens からいずれかを取得することができます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>