<Type Name="IAppServiceCertificateOrder" FullName="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder">
  <TypeSignature Language="C#" Value="public interface IAppServiceCertificateOrder : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager,Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Update.IUpdate&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IAppServiceCertificateOrder implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource`2&lt;class Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager, class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable`1&lt;class Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Update.IUpdate&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder" />
  <TypeSignature Language="VB.NET" Value="Public Interface IAppServiceCertificateOrder&#xA;Implements IBeta, IGroupableResource(Of IAppServiceManager, AppServiceCertificateOrderInner), IHasInner(Of AppServiceCertificateOrderInner), IHasManager(Of IAppServiceManager), IRefreshable(Of IAppServiceCertificateOrder), IUpdatable(Of IUpdate)" />
  <TypeSignature Language="F#" Value="type IAppServiceCertificateOrder = interface&#xA;    interface IBeta&#xA;    interface IGroupableResource&lt;IAppServiceManager, AppServiceCertificateOrderInner&gt;&#xA;    interface IResource&#xA;    interface IIndexable&#xA;    interface IHasId&#xA;    interface IHasName&#xA;    interface IHasResourceGroup&#xA;    interface IHasManager&lt;IAppServiceManager&gt;&#xA;    interface IHasInner&lt;AppServiceCertificateOrderInner&gt;&#xA;    interface IRefreshable&lt;IAppServiceCertificateOrder&gt;&#xA;    interface IUpdatable&lt;IUpdate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager,Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Update.IUpdate&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="2ca1d-101">Azure App Service 証明書の順序の変更できないクライアント側表現。</span><span class="sxs-lookup"><span data-stu-id="2ca1d-101">An immutable client-side representation of an Azure App Service certificate order.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="2ca1d-102">(ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。</span><span class="sxs-lookup"><span data-stu-id="2ca1d-102">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="AutoRenew">
      <MemberSignature Language="C#" Value="public bool AutoRenew { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool AutoRenew" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.AutoRenew" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AutoRenew As Boolean" />
      <MemberSignature Language="F#" Value="member this.AutoRenew : bool" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.AutoRenew" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ca1d-103">証明書は有効期限に自動的に更新する必要がある場合を取得します。</span><span class="sxs-lookup"><span data-stu-id="2ca1d-103">Gets if the certificate should be automatically renewed upon expiration.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateSigningRequest">
      <MemberSignature Language="C#" Value="public string CertificateSigningRequest { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CertificateSigningRequest" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.CertificateSigningRequest" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CertificateSigningRequest As String" />
      <MemberSignature Language="F#" Value="member this.CertificateSigningRequest : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.CertificateSigningRequest" />
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
            <span data-ttu-id="2ca1d-104">この注文に対して作成された要求を署名最後の証明書を取得します。</span><span class="sxs-lookup"><span data-stu-id="2ca1d-104">Gets last certificate signing request that was created for this order.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateKeyVaultBinding">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateKeyVaultBinding CreateKeyVaultBinding (string certificateName, Microsoft.Azure.Management.KeyVault.Fluent.IVault vault);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateKeyVaultBinding CreateKeyVaultBinding(string certificateName, class Microsoft.Azure.Management.KeyVault.Fluent.IVault vault) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.CreateKeyVaultBinding(System.String,Microsoft.Azure.Management.KeyVault.Fluent.IVault)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateKeyVaultBinding (certificateName As String, vault As IVault) As IAppServiceCertificateKeyVaultBinding" />
      <MemberSignature Language="F#" Value="abstract member CreateKeyVaultBinding : string * Microsoft.Azure.Management.KeyVault.Fluent.IVault -&gt; Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateKeyVaultBinding" Usage="iAppServiceCertificateOrder.CreateKeyVaultBinding (certificateName, vault)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateKeyVaultBinding</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="vault" Type="Microsoft.Azure.Management.KeyVault.Fluent.IVault" />
      </Parameters>
      <Docs>
        <param name="certificateName"><span data-ttu-id="2ca1d-105">Key Vault シークレットの名前。</span><span class="sxs-lookup"><span data-stu-id="2ca1d-105">The name of the Key Vault Secret.</span></span></param>
        <param name="vault"><span data-ttu-id="2ca1d-106">証明書を格納する資格情報コンテナー キー。</span><span class="sxs-lookup"><span data-stu-id="2ca1d-106">The key vault to store the certificate.</span></span></param>
        <summary>
            <span data-ttu-id="2ca1d-107">準備が整ったら、証明書を格納するために使用される証明書ストアに Key Vault のシークレットをバインドします。</span><span class="sxs-lookup"><span data-stu-id="2ca1d-107">Bind a Key Vault secret to a certificate store that will be used for storing the certificate once it's ready.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="2ca1d-108">キー コンテナーの情報を格納しているバインディング。</span><span class="sxs-lookup"><span data-stu-id="2ca1d-108">A binding containing the key vault information.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="CreateKeyVaultBindingAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateKeyVaultBinding&gt; CreateKeyVaultBindingAsync (string certificateName, Microsoft.Azure.Management.KeyVault.Fluent.IVault vault, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateKeyVaultBinding&gt; CreateKeyVaultBindingAsync(string certificateName, class Microsoft.Azure.Management.KeyVault.Fluent.IVault vault, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.CreateKeyVaultBindingAsync(System.String,Microsoft.Azure.Management.KeyVault.Fluent.IVault,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateKeyVaultBindingAsync : string * Microsoft.Azure.Management.KeyVault.Fluent.IVault * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateKeyVaultBinding&gt;" Usage="iAppServiceCertificateOrder.CreateKeyVaultBindingAsync (certificateName, vault, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateKeyVaultBinding&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="vault" Type="Microsoft.Azure.Management.KeyVault.Fluent.IVault" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="certificateName"><span data-ttu-id="2ca1d-109">Key Vault シークレットの名前。</span><span class="sxs-lookup"><span data-stu-id="2ca1d-109">The name of the Key Vault Secret.</span></span></param>
        <param name="vault"><span data-ttu-id="2ca1d-110">証明書を格納する資格情報コンテナー キー。</span><span class="sxs-lookup"><span data-stu-id="2ca1d-110">The key vault to store the certificate.</span></span></param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="2ca1d-111">準備が整ったら、証明書を格納するために使用される証明書ストアに Key Vault のシークレットをバインドします。</span><span class="sxs-lookup"><span data-stu-id="2ca1d-111">Bind a Key Vault secret to a certificate store that will be used for storing the certificate once it's ready.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="2ca1d-112">キー コンテナーの情報を格納しているバインディング。</span><span class="sxs-lookup"><span data-stu-id="2ca1d-112">A binding containing the key vault information.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="DistinguishedName">
      <MemberSignature Language="C#" Value="public string DistinguishedName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DistinguishedName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.DistinguishedName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DistinguishedName As String" />
      <MemberSignature Language="F#" Value="member this.DistinguishedName : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.DistinguishedName" />
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
            <span data-ttu-id="2ca1d-113">証明書の識別名を取得します。</span><span class="sxs-lookup"><span data-stu-id="2ca1d-113">Gets certificate's distinguished name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DomainVerificationToken">
      <MemberSignature Language="C#" Value="public string DomainVerificationToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DomainVerificationToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.DomainVerificationToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DomainVerificationToken As String" />
      <MemberSignature Language="F#" Value="member this.DomainVerificationToken : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.DomainVerificationToken" />
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
            <span data-ttu-id="2ca1d-114">ドメインの確認トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="2ca1d-114">Gets the domain verification token.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpirationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ExpirationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ExpirationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.ExpirationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpirationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ExpirationTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.ExpirationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ca1d-115">有効期限を取得します。</span><span class="sxs-lookup"><span data-stu-id="2ca1d-115">Gets expiration time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetKeyVaultBinding">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateKeyVaultBinding GetKeyVaultBinding ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateKeyVaultBinding GetKeyVaultBinding() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.GetKeyVaultBinding" />
      <MemberSignature Language="VB.NET" Value="Public Function GetKeyVaultBinding () As IAppServiceCertificateKeyVaultBinding" />
      <MemberSignature Language="F#" Value="abstract member GetKeyVaultBinding : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateKeyVaultBinding" Usage="iAppServiceCertificateOrder.GetKeyVaultBinding " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateKeyVaultBinding</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="2ca1d-116">Key Vault シークレットの状態。</span><span class="sxs-lookup"><span data-stu-id="2ca1d-116">The state of the Key Vault secret.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="GetKeyVaultBindingAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateKeyVaultBinding&gt; GetKeyVaultBindingAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateKeyVaultBinding&gt; GetKeyVaultBindingAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.GetKeyVaultBindingAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetKeyVaultBindingAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateKeyVaultBinding&gt;" Usage="iAppServiceCertificateOrder.GetKeyVaultBindingAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateKeyVaultBinding&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="2ca1d-117">Key Vault シークレットの状態。</span><span class="sxs-lookup"><span data-stu-id="2ca1d-117">The state of the Key Vault secret.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="Intermediate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails Intermediate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails Intermediate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.Intermediate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Intermediate As CertificateDetails" />
      <MemberSignature Language="F#" Value="member this.Intermediate : Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.Intermediate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ca1d-118">中間証明書を取得します。</span><span class="sxs-lookup"><span data-stu-id="2ca1d-118">Gets the intermediate certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeySize">
      <MemberSignature Language="C#" Value="public int KeySize { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 KeySize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.KeySize" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property KeySize As Integer" />
      <MemberSignature Language="F#" Value="member this.KeySize : int" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.KeySize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ca1d-119">証明書のキー サイズを取得します。</span><span class="sxs-lookup"><span data-stu-id="2ca1d-119">Gets the certificate key size.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastCertificateIssuanceTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastCertificateIssuanceTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastCertificateIssuanceTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.LastCertificateIssuanceTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastCertificateIssuanceTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastCertificateIssuanceTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.LastCertificateIssuanceTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ca1d-120">最終発行時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="2ca1d-120">Gets last issuance time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProductType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.CertificateProductType ProductType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.AppService.Fluent.Models.CertificateProductType ProductType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.ProductType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProductType As CertificateProductType" />
      <MemberSignature Language="F#" Value="member this.ProductType : Microsoft.Azure.Management.AppService.Fluent.Models.CertificateProductType" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.ProductType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.CertificateProductType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ca1d-121">証明書の製品の種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="2ca1d-121">Gets the certificate product type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Root">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails Root { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails Root" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.Root" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Root As CertificateDetails" />
      <MemberSignature Language="F#" Value="member this.Root : Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.Root" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ca1d-122">ルート証明書を取得します。</span><span class="sxs-lookup"><span data-stu-id="2ca1d-122">Gets the root certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerialNumber">
      <MemberSignature Language="C#" Value="public string SerialNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SerialNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.SerialNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerialNumber As String" />
      <MemberSignature Language="F#" Value="member this.SerialNumber : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.SerialNumber" />
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
            <span data-ttu-id="2ca1d-123">証明書の現在のシリアル番号を取得します。</span><span class="sxs-lookup"><span data-stu-id="2ca1d-123">Gets current serial number of the certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SignedCertificate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails SignedCertificate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails SignedCertificate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.SignedCertificate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SignedCertificate As CertificateDetails" />
      <MemberSignature Language="F#" Value="member this.SignedCertificate : Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.SignedCertificate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ca1d-124">署名証明書を取得します。</span><span class="sxs-lookup"><span data-stu-id="2ca1d-124">Gets the signed certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.CertificateOrderStatus Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.AppService.Fluent.Models.CertificateOrderStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As CertificateOrderStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.Azure.Management.AppService.Fluent.Models.CertificateOrderStatus" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.CertificateOrderStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ca1d-125">現在の注文ステータスを取得します。</span><span class="sxs-lookup"><span data-stu-id="2ca1d-125">Gets current order status.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidityInYears">
      <MemberSignature Language="C#" Value="public int ValidityInYears { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ValidityInYears" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.ValidityInYears" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ValidityInYears As Integer" />
      <MemberSignature Language="F#" Value="member this.ValidityInYears : int" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.ValidityInYears" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ca1d-126">年 (1 ~ 3 の範囲である必要があります) に含まれる期間を取得します。</span><span class="sxs-lookup"><span data-stu-id="2ca1d-126">Gets duration in years (must be between 1 and 3).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VerifyDomainOwnership">
      <MemberSignature Language="C#" Value="public void VerifyDomainOwnership (Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain domain);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void VerifyDomainOwnership(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain domain) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.VerifyDomainOwnership(Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain)" />
      <MemberSignature Language="VB.NET" Value="Public Sub VerifyDomainOwnership (domain As IAppServiceDomain)" />
      <MemberSignature Language="F#" Value="abstract member VerifyDomainOwnership : Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain -&gt; unit" Usage="iAppServiceCertificateOrder.VerifyDomainOwnership domain" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="domain" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain" />
      </Parameters>
      <Docs>
        <param name="domain"><span data-ttu-id="2ca1d-127">Azure では、ドメインを管理します。</span><span class="sxs-lookup"><span data-stu-id="2ca1d-127">The Azure managed domain.</span></span></param>
        <summary>
            <span data-ttu-id="2ca1d-128">購入した Azure が提供することによってドメインの所有権を確認するドメインです。</span><span class="sxs-lookup"><span data-stu-id="2ca1d-128">Verifies the ownership of the domain by providing the Azure purchased domain.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VerifyDomainOwnershipAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task VerifyDomainOwnershipAsync (Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain domain, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task VerifyDomainOwnershipAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain domain, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.VerifyDomainOwnershipAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member VerifyDomainOwnershipAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iAppServiceCertificateOrder.VerifyDomainOwnershipAsync (domain, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="domain" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="domain"><span data-ttu-id="2ca1d-129">Azure では、ドメインを管理します。</span><span class="sxs-lookup"><span data-stu-id="2ca1d-129">The Azure managed domain.</span></span></param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="2ca1d-130">購入した Azure が提供することによってドメインの所有権を確認するドメインです。</span><span class="sxs-lookup"><span data-stu-id="2ca1d-130">Verifies the ownership of the domain by providing the Azure purchased domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="2ca1d-131">結果を監視します。</span><span class="sxs-lookup"><span data-stu-id="2ca1d-131">An Observable to the result.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>