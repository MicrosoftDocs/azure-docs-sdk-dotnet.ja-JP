<Type Name="IAppServiceCertificateKeyVaultBinding" FullName="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateKeyVaultBinding">
  <TypeSignature Language="C#" Value="public interface IAppServiceCertificateKeyVaultBinding : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager,Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChild&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChildResource&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager,Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IAppServiceCertificateKeyVaultBinding implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource`2&lt;class Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager, class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChild`1&lt;class Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChildResource`2&lt;class Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager, class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateKeyVaultBinding" />
  <TypeSignature Language="VB.NET" Value="Public Interface IAppServiceCertificateKeyVaultBinding&#xA;Implements IBeta, IGroupableResource(Of IAppServiceManager, AppServiceCertificateResourceInner), IHasInner(Of AppServiceCertificateResourceInner), IHasManager(Of IAppServiceManager), IIndependentChild(Of IAppServiceManager), IIndependentChildResource(Of IAppServiceManager, AppServiceCertificateResourceInner)" />
  <TypeSignature Language="F#" Value="type IAppServiceCertificateKeyVaultBinding = interface&#xA;    interface IBeta&#xA;    interface IIndependentChildResource&lt;IAppServiceManager, AppServiceCertificateResourceInner&gt;&#xA;    interface IGroupableResource&lt;IAppServiceManager, AppServiceCertificateResourceInner&gt;&#xA;    interface IResource&#xA;    interface IIndexable&#xA;    interface IHasId&#xA;    interface IHasName&#xA;    interface IHasResourceGroup&#xA;    interface IHasManager&lt;IAppServiceManager&gt;&#xA;    interface IHasInner&lt;AppServiceCertificateResourceInner&gt;&#xA;    interface IIndependentChild&lt;IAppServiceManager&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager,Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChild&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChildResource&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager,Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="1de80-101">Azure App Service の Key Vault バインディングの変更できないクライアント側表現。</span><span class="sxs-lookup"><span data-stu-id="1de80-101">An immutable client-side representation of an Azure App Service Key Vault binding.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="1de80-102">(ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。</span><span class="sxs-lookup"><span data-stu-id="1de80-102">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="KeyVaultId">
      <MemberSignature Language="C#" Value="public string KeyVaultId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyVaultId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateKeyVaultBinding.KeyVaultId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property KeyVaultId As String" />
      <MemberSignature Language="F#" Value="member this.KeyVaultId : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateKeyVaultBinding.KeyVaultId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1de80-103">リソースを取得しますキー資格情報コンテナー id。</span><span class="sxs-lookup"><span data-stu-id="1de80-103">Gets the key vault resource Id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyVaultSecretName">
      <MemberSignature Language="C#" Value="public string KeyVaultSecretName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyVaultSecretName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateKeyVaultBinding.KeyVaultSecretName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property KeyVaultSecretName As String" />
      <MemberSignature Language="F#" Value="member this.KeyVaultSecretName : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateKeyVaultBinding.KeyVaultSecretName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1de80-104">Key vault のシークレット名を取得します。</span><span class="sxs-lookup"><span data-stu-id="1de80-104">Gets the key vault secret name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.KeyVaultSecretStatus ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.AppService.Fluent.Models.KeyVaultSecretStatus ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateKeyVaultBinding.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As KeyVaultSecretStatus" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Microsoft.Azure.Management.AppService.Fluent.Models.KeyVaultSecretStatus" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateKeyVaultBinding.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.KeyVaultSecretStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1de80-105">秘密キー コンテナーの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="1de80-105">Gets the status of the Key Vault secret.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>