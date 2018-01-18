<Type Name="IDeploymentSlots" FullName="Microsoft.Azure.Management.AppService.Fluent.IDeploymentSlots">
  <TypeSignature Language="C#" Value="public interface IDeploymentSlots : Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsCreating&lt;Microsoft.Azure.Management.AppService.Fluent.DeploymentSlot.Definition.IBlank&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingById, Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingByName, Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingById&lt;Microsoft.Azure.Management.AppService.Fluent.IDeploymentSlot&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingByName&lt;Microsoft.Azure.Management.AppService.Fluent.IDeploymentSlot&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListing&lt;Microsoft.Azure.Management.AppService.Fluent.IDeploymentSlot&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.AppService.Fluent.IWebApp&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDeploymentSlots implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsCreating`1&lt;class Microsoft.Azure.Management.AppService.Fluent.DeploymentSlot.Definition.IBlank&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingById, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingByName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingById`1&lt;class Microsoft.Azure.Management.AppService.Fluent.IDeploymentSlot&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingByName`1&lt;class Microsoft.Azure.Management.AppService.Fluent.IDeploymentSlot&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListing`1&lt;class Microsoft.Azure.Management.AppService.Fluent.IDeploymentSlot&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent`1&lt;class Microsoft.Azure.Management.AppService.Fluent.IWebApp&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.IDeploymentSlots" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDeploymentSlots&#xA;Implements IBeta, IHasManager(Of IAppServiceManager), IHasParent(Of IWebApp), ISupportsCreating(Of IBlank), ISupportsDeletingById, ISupportsDeletingByName, ISupportsGettingById(Of IDeploymentSlot), ISupportsGettingByName(Of IDeploymentSlot), ISupportsListing(Of IDeploymentSlot)" />
  <TypeSignature Language="F#" Value="type IDeploymentSlots = interface&#xA;    interface IBeta&#xA;    interface ISupportsCreating&lt;IBlank&gt;&#xA;    interface ISupportsListing&lt;IDeploymentSlot&gt;&#xA;    interface ISupportsGettingByName&lt;IDeploymentSlot&gt;&#xA;    interface ISupportsGettingById&lt;IDeploymentSlot&gt;&#xA;    interface ISupportsDeletingById&#xA;    interface ISupportsDeletingByName&#xA;    interface IHasManager&lt;IAppServiceManager&gt;&#xA;    interface IHasParent&lt;IWebApp&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsCreating&lt;Microsoft.Azure.Management.AppService.Fluent.DeploymentSlot.Definition.IBlank&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingById</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingByName</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingById&lt;Microsoft.Azure.Management.AppService.Fluent.IDeploymentSlot&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingByName&lt;Microsoft.Azure.Management.AppService.Fluent.IDeploymentSlot&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListing&lt;Microsoft.Azure.Management.AppService.Fluent.IDeploymentSlot&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.AppService.Fluent.IWebApp&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="2edb2-101">Azure web アプリの展開スロット管理 API のエントリ ポイントです。</span><span class="sxs-lookup"><span data-stu-id="2edb2-101">Entry point for Azure web app deployment slot management API.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="2edb2-102">(ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。</span><span class="sxs-lookup"><span data-stu-id="2edb2-102">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
  </Docs>
  <Members />
</Type>