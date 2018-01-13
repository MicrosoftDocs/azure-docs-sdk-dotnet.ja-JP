<Type Name="IWithClientCertEnabled&lt;FluentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithClientCertEnabled&lt;FluentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithClientCertEnabled&lt;FluentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithClientCertEnabled`1&lt;FluentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithClientCertEnabled`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithClientCertEnabled(Of FluentT)" />
  <TypeSignature Language="F#" Value="type IWithClientCertEnabled&lt;'FluentT&gt; = interface" />
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
            クライアント証明書が有効になっている場合は、設定を許可する web アプリの更新の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithClientCertEnabled">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithClientCertEnabled (bool enabled);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithClientCertEnabled(bool enabled) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithClientCertEnabled`1.WithClientCertEnabled(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithClientCertEnabled (enabled As Boolean) As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithClientCertEnabled : bool -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithClientCertEnabled.WithClientCertEnabled enabled" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="enabled" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="enabled">クライアント証明書が有効になっている場合は true。</param>
        <summary>
            クライアント証明書が有効かどうかを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Web アプリの更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>