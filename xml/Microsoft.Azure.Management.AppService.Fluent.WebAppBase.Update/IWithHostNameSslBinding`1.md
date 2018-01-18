<Type Name="IWithHostNameSslBinding&lt;FluentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithHostNameSslBinding&lt;FluentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithHostNameSslBinding&lt;FluentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithHostNameSslBinding`1&lt;FluentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithHostNameSslBinding`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithHostNameSslBinding(Of FluentT)" />
  <TypeSignature Language="F#" Value="type IWithHostNameSslBinding&lt;'FluentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="FluentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="FluentT"><span data-ttu-id="9caff-101">リソースの型。</span><span class="sxs-lookup"><span data-stu-id="9caff-101">The type of the resource.</span></span></typeparam>
    <summary>
            <span data-ttu-id="9caff-102">Web アプリのステージでは、設定する SSL バインドをすることができますを更新します。</span><span class="sxs-lookup"><span data-stu-id="9caff-102">The stage of the web app update allowing SSL binding to be set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineSslBinding">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;&gt; DefineSslBinding ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt;&gt; DefineSslBinding() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithHostNameSslBinding`1.DefineSslBinding" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineSslBinding () As IBlank(Of IUpdate(Of FluentT))" />
      <MemberSignature Language="F#" Value="abstract member DefineSslBinding : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;&gt;" Usage="iWithHostNameSslBinding.DefineSslBinding " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9caff-103">SSL バインドの定義を開始します。</span><span class="sxs-lookup"><span data-stu-id="9caff-103">Starts a definition of an SSL binding.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="9caff-104">SSL バインディング定義の最初の段階です。</span><span class="sxs-lookup"><span data-stu-id="9caff-104">The first stage of an SSL binding definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutSslBinding">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithoutSslBinding (string hostname);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithoutSslBinding(string hostname) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithHostNameSslBinding`1.WithoutSslBinding(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutSslBinding (hostname As String) As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithoutSslBinding : string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithHostNameSslBinding.WithoutSslBinding hostname" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="hostname" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="hostname"><span data-ttu-id="9caff-105">SSL 証明書を削除するホスト名です。</span><span class="sxs-lookup"><span data-stu-id="9caff-105">The hostname to remove SSL certificate from.</span></span></param>
        <summary>
            <span data-ttu-id="9caff-106">特定のホスト名の SSL バインドを削除します。</span><span class="sxs-lookup"><span data-stu-id="9caff-106">Removes an SSL binding for a specific hostname.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="9caff-107">Web アプリの更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="9caff-107">The next stage of web app update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>