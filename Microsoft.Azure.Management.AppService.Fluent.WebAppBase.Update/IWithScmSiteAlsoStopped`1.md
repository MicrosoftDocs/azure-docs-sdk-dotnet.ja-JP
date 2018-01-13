<Type Name="IWithScmSiteAlsoStopped&lt;FluentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithScmSiteAlsoStopped&lt;FluentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithScmSiteAlsoStopped&lt;FluentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithScmSiteAlsoStopped`1&lt;FluentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithScmSiteAlsoStopped`1" />
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
    <typeparam name="FluentT"><span data-ttu-id="7e530-101">リソースの型。</span><span class="sxs-lookup"><span data-stu-id="7e530-101">The type of the resource.</span></span></typeparam>
    <summary>
            <span data-ttu-id="7e530-102">Web アプリが停止されたときにも SCM サイトが停止している場合は、設定を許可する web アプリの更新の段階です。</span><span class="sxs-lookup"><span data-stu-id="7e530-102">The stage of the web app update allowing setting if SCM site is also stopped when the web app is stopped.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithScmSiteAlsoStopped">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithScmSiteAlsoStopped (bool scmSiteAlsoStopped);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithScmSiteAlsoStopped(bool scmSiteAlsoStopped) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithScmSiteAlsoStopped`1.WithScmSiteAlsoStopped(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithScmSiteAlsoStopped (scmSiteAlsoStopped As Boolean) As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithScmSiteAlsoStopped : bool -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithScmSiteAlsoStopped.WithScmSiteAlsoStopped scmSiteAlsoStopped" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scmSiteAlsoStopped" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="scmSiteAlsoStopped"><span data-ttu-id="7e530-103">SCM サイトも停止している場合は true。</span><span class="sxs-lookup"><span data-stu-id="7e530-103">True if SCM site is also stopped.</span></span></param>
        <summary>
            <span data-ttu-id="7e530-104">Web アプリが停止したときにも SCM サイトが停止かどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="7e530-104">Specifies if SCM site is also stopped when the web app is stopped.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="7e530-105">Web アプリの更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="7e530-105">The next stage of web app update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>