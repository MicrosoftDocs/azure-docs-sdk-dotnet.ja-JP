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
    <typeparam name="FluentT"><span data-ttu-id="9e262-101">リソースの型。</span><span class="sxs-lookup"><span data-stu-id="9e262-101">The type of the resource.</span></span></typeparam>
    <summary>
            <span data-ttu-id="9e262-102">設定への認証を許可する、web アプリ定義段階です。</span><span class="sxs-lookup"><span data-stu-id="9e262-102">A web app definition stage allowing authentication to be set.</span></span>
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
            <span data-ttu-id="9e262-103">新しい認証構成の定義を指定します。</span><span class="sxs-lookup"><span data-stu-id="9e262-103">Specifies the definition of a new authentication configuration.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="9e262-104">認証定義の最初の段階です。</span><span class="sxs-lookup"><span data-stu-id="9e262-104">The first stage of an authentication definition.</span></span></return>
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
            <span data-ttu-id="9e262-105">この web アプリで認証をオフにします。</span><span class="sxs-lookup"><span data-stu-id="9e262-105">Turns off the authentication on the web app.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="9e262-106">Web アプリの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="9e262-106">The next stage of the web app update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>