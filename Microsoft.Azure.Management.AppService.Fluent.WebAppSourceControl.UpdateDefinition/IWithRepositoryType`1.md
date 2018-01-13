<Type Name="IWithRepositoryType&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.UpdateDefinition.IWithRepositoryType&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithRepositoryType&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithRepositoryType`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.UpdateDefinition.IWithRepositoryType`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithRepositoryType(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithRepositoryType&lt;'ParentT&gt; = interface" />
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
            Web アプリのソースは、定義を指定する許可するリポジトリの種類を制御します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithContinuouslyIntegratedGitHubRepository">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.UpdateDefinition.IWithGitHubBranch&lt;ParentT&gt; WithContinuouslyIntegratedGitHubRepository (string url);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.UpdateDefinition.IWithGitHubBranch`1&lt;!ParentT&gt; WithContinuouslyIntegratedGitHubRepository(string url) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.UpdateDefinition.IWithRepositoryType`1.WithContinuouslyIntegratedGitHubRepository(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithContinuouslyIntegratedGitHubRepository (url As String) As IWithGitHubBranch(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithContinuouslyIntegratedGitHubRepository : string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.UpdateDefinition.IWithGitHubBranch&lt;'ParentT&gt;" Usage="iWithRepositoryType.WithContinuouslyIntegratedGitHubRepository url" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.UpdateDefinition.IWithGitHubBranch&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="url" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="url">例: https://github.com/Azure/azure-sdk-for-java、リポジトリを指す URL です。</param>
        <summary>
            GitHub リポジトリにリポジトリを指定します。 継続的インテグレーション有効になります。
            このリポジトリは、パブリックまたはプライベートのいずれかを指定できますが、GitHub のアクセス トークンは、webhook をリポジトリに追加するための十分な特権を持つ必要があります。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithContinuouslyIntegratedGitHubRepository">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.UpdateDefinition.IWithGitHubBranch&lt;ParentT&gt; WithContinuouslyIntegratedGitHubRepository (string organization, string repository);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.UpdateDefinition.IWithGitHubBranch`1&lt;!ParentT&gt; WithContinuouslyIntegratedGitHubRepository(string organization, string repository) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.UpdateDefinition.IWithRepositoryType`1.WithContinuouslyIntegratedGitHubRepository(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithContinuouslyIntegratedGitHubRepository (organization As String, repository As String) As IWithGitHubBranch(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithContinuouslyIntegratedGitHubRepository : string * string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.UpdateDefinition.IWithGitHubBranch&lt;'ParentT&gt;" Usage="iWithRepositoryType.WithContinuouslyIntegratedGitHubRepository (organization, repository)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.UpdateDefinition.IWithGitHubBranch&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="organization" Type="System.String" />
        <Parameter Name="repository" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="organization">ユーザー名または GitHub リポジトリが属する Azure などの組織名。</param>
        <param name="repository">例: azure sdk-を java、リポジトリの名前。</param>
        <summary>
            GitHub リポジトリにリポジトリを指定します。 継続的インテグレーション有効になります。
            このリポジトリは、パブリックまたはプライベートのいずれかを指定できますが、GitHub のアクセス トークンは、webhook をリポジトリに追加するための十分な特権を持つ必要があります。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithPublicGitRepository">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.UpdateDefinition.IWithBranch&lt;ParentT&gt; WithPublicGitRepository (string url);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.UpdateDefinition.IWithBranch`1&lt;!ParentT&gt; WithPublicGitRepository(string url) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.UpdateDefinition.IWithRepositoryType`1.WithPublicGitRepository(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPublicGitRepository (url As String) As IWithBranch(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithPublicGitRepository : string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.UpdateDefinition.IWithBranch&lt;'ParentT&gt;" Usage="iWithRepositoryType.WithPublicGitRepository url" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.UpdateDefinition.IWithBranch&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="url" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="url">Git リポジトリの url です。</param>
        <summary>
            リポジトリであるパブリック外部、Git または Mercurial リポジトリを指定します。
            継続的インテグレーションは入っていません。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithPublicMercurialRepository">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.UpdateDefinition.IWithBranch&lt;ParentT&gt; WithPublicMercurialRepository (string url);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.UpdateDefinition.IWithBranch`1&lt;!ParentT&gt; WithPublicMercurialRepository(string url) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.UpdateDefinition.IWithRepositoryType`1.WithPublicMercurialRepository(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPublicMercurialRepository (url As String) As IWithBranch(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithPublicMercurialRepository : string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.UpdateDefinition.IWithBranch&lt;'ParentT&gt;" Usage="iWithRepositoryType.WithPublicMercurialRepository url" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.UpdateDefinition.IWithBranch&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="url" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="url">Mercurial リポジトリの url です。</param>
        <summary>
            リポジトリであるパブリック外部、Git または Mercurial リポジトリを指定します。
            継続的インテグレーションは入っていません。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>