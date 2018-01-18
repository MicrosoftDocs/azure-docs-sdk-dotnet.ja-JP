<Type Name="IWithSourceControl&lt;FluentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithSourceControl&lt;FluentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithSourceControl&lt;FluentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSourceControl`1&lt;FluentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithSourceControl`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSourceControl(Of FluentT)" />
  <TypeSignature Language="F#" Value="type IWithSourceControl&lt;'FluentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="FluentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="FluentT"><span data-ttu-id="53e1a-101">リソースの型。</span><span class="sxs-lookup"><span data-stu-id="53e1a-101">The type of the resource.</span></span></typeparam>
    <summary>
            <span data-ttu-id="53e1a-102">設定するソース管理を許可する、web アプリ定義段階です。</span><span class="sxs-lookup"><span data-stu-id="53e1a-102">A web app definition stage allowing source control to be set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineSourceControl">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IBlank&lt;Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt;&gt; DefineSourceControl ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IBlank`1&lt;class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate`1&lt;!FluentT&gt;&gt; DefineSourceControl() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithSourceControl`1.DefineSourceControl" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineSourceControl () As IBlank(Of IWithCreate(Of FluentT))" />
      <MemberSignature Language="F#" Value="abstract member DefineSourceControl : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IBlank&lt;Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;'FluentT&gt;&gt;" Usage="iWithSourceControl.DefineSourceControl " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IBlank&lt;Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="53e1a-103">新しいソース コントロールの定義を開始します。</span><span class="sxs-lookup"><span data-stu-id="53e1a-103">Starts the definition of a new source control.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="53e1a-104">ソース コントロールの定義の最初の段階です。</span><span class="sxs-lookup"><span data-stu-id="53e1a-104">The first stage of a source control definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithLocalGitSourceControl">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt; WithLocalGitSourceControl ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate`1&lt;!FluentT&gt; WithLocalGitSourceControl() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithSourceControl`1.WithLocalGitSourceControl" />
      <MemberSignature Language="VB.NET" Value="Public Function WithLocalGitSourceControl () As IWithCreate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithLocalGitSourceControl : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;'FluentT&gt;" Usage="iWithSourceControl.WithLocalGitSourceControl " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="53e1a-105">この web アプリでローカル Git リポジトリにソース管理を指定します。</span><span class="sxs-lookup"><span data-stu-id="53e1a-105">Specifies the source control to be a local Git repository on the web app.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="53e1a-106">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="53e1a-106">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>