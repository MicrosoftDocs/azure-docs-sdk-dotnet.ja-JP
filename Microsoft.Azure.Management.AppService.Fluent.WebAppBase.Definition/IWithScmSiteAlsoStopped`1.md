<Type Name="IWithScmSiteAlsoStopped&lt;FluentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithScmSiteAlsoStopped&lt;FluentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithScmSiteAlsoStopped&lt;FluentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithScmSiteAlsoStopped`1&lt;FluentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithScmSiteAlsoStopped`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithScmSiteAlsoStopped(Of FluentT)" />
  <TypeSignature Language="F#" Value="type IWithScmSiteAlsoStopped&lt;'FluentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="FluentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="FluentT">リソースの型。</typeparam>
    <summary>
            Web アプリが停止されたときにも SCM サイトが停止している場合は、設定を許可する、web アプリ定義段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithScmSiteAlsoStopped">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt; WithScmSiteAlsoStopped (bool scmSiteAlsoStopped);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate`1&lt;!FluentT&gt; WithScmSiteAlsoStopped(bool scmSiteAlsoStopped) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithScmSiteAlsoStopped`1.WithScmSiteAlsoStopped(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithScmSiteAlsoStopped (scmSiteAlsoStopped As Boolean) As IWithCreate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithScmSiteAlsoStopped : bool -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;'FluentT&gt;" Usage="iWithScmSiteAlsoStopped.WithScmSiteAlsoStopped scmSiteAlsoStopped" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scmSiteAlsoStopped" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="scmSiteAlsoStopped">SCM サイトも停止している場合は true。</param>
        <summary>
            Web アプリが停止したときにも SCM サイトが停止かどうかを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>