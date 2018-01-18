<Type Name="IWithSourceControl&lt;FluentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithSourceControl&lt;FluentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithSourceControl&lt;FluentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSourceControl`1&lt;FluentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithSourceControl`1" />
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
    <typeparam name="FluentT"><span data-ttu-id="a9515-101">リソースの型。</span><span class="sxs-lookup"><span data-stu-id="a9515-101">The type of the resource.</span></span></typeparam>
    <summary>
            <span data-ttu-id="a9515-102">Web アプリを設定するソース管理を許可するステージを更新します。</span><span class="sxs-lookup"><span data-stu-id="a9515-102">A web app update stage allowing source control to be set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineSourceControl">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;&gt; DefineSourceControl ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt;&gt; DefineSourceControl() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithSourceControl`1.DefineSourceControl" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineSourceControl () As IBlank(Of IUpdate(Of FluentT))" />
      <MemberSignature Language="F#" Value="abstract member DefineSourceControl : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;&gt;" Usage="iWithSourceControl.DefineSourceControl " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a9515-103">新しいソース コントロールの定義を開始します。</span><span class="sxs-lookup"><span data-stu-id="a9515-103">Starts the definition of a new source control.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a9515-104">ソース コントロールの定義の最初の段階です。</span><span class="sxs-lookup"><span data-stu-id="a9515-104">The first stage of a source control definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithLocalGitSourceControl">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithLocalGitSourceControl ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithLocalGitSourceControl() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithSourceControl`1.WithLocalGitSourceControl" />
      <MemberSignature Language="VB.NET" Value="Public Function WithLocalGitSourceControl () As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithLocalGitSourceControl : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithSourceControl.WithLocalGitSourceControl " />
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
            <span data-ttu-id="a9515-105">この web アプリでローカル Git リポジトリにソース管理を指定します。</span><span class="sxs-lookup"><span data-stu-id="a9515-105">Specifies the source control to be a local Git repository on the web app.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a9515-106">Web アプリの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="a9515-106">The next stage of the web app update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutSourceControl">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithoutSourceControl ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithoutSourceControl() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithSourceControl`1.WithoutSourceControl" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutSourceControl () As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithoutSourceControl : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithSourceControl.WithoutSourceControl " />
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
            <span data-ttu-id="a9515-107">Web アプリからソース管理の展開を削除します。</span><span class="sxs-lookup"><span data-stu-id="a9515-107">Removes source control for deployment from the web app.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a9515-108">Web アプリの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="a9515-108">The next stage of the web app update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>