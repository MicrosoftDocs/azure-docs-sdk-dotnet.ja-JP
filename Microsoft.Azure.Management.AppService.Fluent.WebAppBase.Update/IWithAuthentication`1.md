<Type Name="IWithAuthentication&lt;FluentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithAuthentication&lt;FluentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithAuthentication&lt;FluentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAuthentication`1&lt;FluentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithAuthentication`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAuthentication(Of FluentT)" />
  <TypeSignature Language="F#" Value="type IWithAuthentication&lt;'FluentT&gt; = interface" />
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
            設定への認証を許可する、web アプリ定義段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineAuthentication">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;&gt; DefineAuthentication ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt;&gt; DefineAuthentication() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithAuthentication`1.DefineAuthentication" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineAuthentication () As IBlank(Of IUpdate(Of FluentT))" />
      <MemberSignature Language="F#" Value="abstract member DefineAuthentication : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;&gt;" Usage="iWithAuthentication.DefineAuthentication " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            新しい認証構成の定義を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>認証定義の最初の段階です。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutAuthentication">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithoutAuthentication ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithoutAuthentication() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithAuthentication`1.WithoutAuthentication" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutAuthentication () As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithoutAuthentication : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithAuthentication.WithoutAuthentication " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            この web アプリで認証をオフにします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Web アプリの更新の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>