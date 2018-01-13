<Type Name="IWithGitHubAccessToken&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.UpdateDefinition.IWithGitHubAccessToken&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithGitHubAccessToken&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithGitHubAccessToken`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.UpdateDefinition.IWithGitHubAccessToken`1" />
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
    <typeparam name="ParentT"><span data-ttu-id="39f4b-101">この定義をアタッチした後に戻るに親の定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="39f4b-101">The stage of the parent definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="39f4b-102">Web アプリ ソース コントロールの定義を指定する GitHub のアクセス トークンを許可します。</span><span class="sxs-lookup"><span data-stu-id="39f4b-102">A web app source control definition allowing GitHub access token to be specified.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithGitHubAccessToken">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.UpdateDefinition.IGitHubWithAttach&lt;ParentT&gt; WithGitHubAccessToken (string personalAccessToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.UpdateDefinition.IGitHubWithAttach`1&lt;!ParentT&gt; WithGitHubAccessToken(string personalAccessToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.UpdateDefinition.IWithGitHubAccessToken`1.WithGitHubAccessToken(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithGitHubAccessToken (personalAccessToken As String) As IGitHubWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithGitHubAccessToken : string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.UpdateDefinition.IGitHubWithAttach&lt;'ParentT&gt;" Usage="iWithGitHubAccessToken.WithGitHubAccessToken personalAccessToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.UpdateDefinition.IGitHubWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="personalAccessToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="personalAccessToken"><span data-ttu-id="39f4b-103">GitHub から個人用アクセス トークンです。</span><span class="sxs-lookup"><span data-stu-id="39f4b-103">The personal access token from GitHub.</span></span></param>
        <summary>
            <span data-ttu-id="39f4b-104">GitHub 個人用アクセス トークンを指定します。</span><span class="sxs-lookup"><span data-stu-id="39f4b-104">Specifies the GitHub personal access token.</span></span> <span data-ttu-id="39f4b-105">Https://github.com/settings/tokens からいずれかを取得することができます。</span><span class="sxs-lookup"><span data-stu-id="39f4b-105">You can acquire one from https://github.com/settings/tokens.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="39f4b-106">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="39f4b-106">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>