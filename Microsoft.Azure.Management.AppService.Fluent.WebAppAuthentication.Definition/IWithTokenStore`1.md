<Type Name="IWithTokenStore&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithTokenStore&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithTokenStore&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithTokenStore`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithTokenStore`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithTokenStore(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithTokenStore&lt;'ParentT&gt; = interface" />
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
            指定するトークンを許可する、web アプリの認証の定義を格納します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithTokenStore">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAttach&lt;ParentT&gt; WithTokenStore (bool enabled);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAttach`1&lt;!ParentT&gt; WithTokenStore(bool enabled) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithTokenStore`1.WithTokenStore(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithTokenStore (enabled As Boolean) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithTokenStore : bool -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithTokenStore.WithTokenStore enabled" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="enabled" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="enabled">トークン ストアを有効にする場合は true。</param>
        <summary>
            トークン ストアを有効にするかどうかを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>