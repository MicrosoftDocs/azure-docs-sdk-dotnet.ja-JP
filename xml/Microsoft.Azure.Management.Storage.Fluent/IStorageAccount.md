<Type Name="IStorageAccount" FullName="Microsoft.Azure.Management.Storage.Fluent.IStorageAccount">
  <TypeSignature Language="C#" Value="public interface IStorageAccount : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.Storage.Fluent.IStorageManager,Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Storage.Fluent.IStorageManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Storage.Fluent.IStorageAccount&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IUpdate&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStorageAccount implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource`2&lt;class Microsoft.Azure.Management.Storage.Fluent.IStorageManager, class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.Storage.Fluent.IStorageManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.Storage.Fluent.IStorageAccount&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable`1&lt;class Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IUpdate&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Fluent.IStorageAccount" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStorageAccount&#xA;Implements IGroupableResource(Of IStorageManager, StorageAccountInner), IHasInner(Of StorageAccountInner), IHasManager(Of IStorageManager), IRefreshable(Of IStorageAccount), IUpdatable(Of IUpdate)" />
  <TypeSignature Language="F#" Value="type IStorageAccount = interface&#xA;    interface IGroupableResource&lt;IStorageManager, StorageAccountInner&gt;&#xA;    interface IResource&#xA;    interface IIndexable&#xA;    interface IHasId&#xA;    interface IHasName&#xA;    interface IHasResourceGroup&#xA;    interface IHasManager&lt;IStorageManager&gt;&#xA;    interface IHasInner&lt;StorageAccountInner&gt;&#xA;    interface IRefreshable&lt;IStorageAccount&gt;&#xA;    interface IUpdatable&lt;IUpdate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.Storage.Fluent.IStorageManager,Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Storage.Fluent.IStorageManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Storage.Fluent.IStorageAccount&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IUpdate&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="8be89-101">Azure ストレージ アカウントの変更できないクライアント側表現。</span><span class="sxs-lookup"><span data-stu-id="8be89-101">An immutable client-side representation of an Azure storage account.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AccessTier">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier AccessTier { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier AccessTier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.AccessTier" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccessTier As AccessTier" />
      <MemberSignature Language="F#" Value="member this.AccessTier : Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier" Usage="Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.AccessTier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8be89-102">取得は、課金のために使用層にアクセスします。</span><span class="sxs-lookup"><span data-stu-id="8be89-102">Gets access tier used for billing.</span></span> <span data-ttu-id="8be89-103">アクセス層には、7 日に複数回の (168 時間) を変更できません。</span><span class="sxs-lookup"><span data-stu-id="8be89-103">Access tier cannot be changed more than once every 7 days (168 hours).</span></span> <span data-ttu-id="8be89-104">StandardLRS、StandardGRS、StandardRAGRS、または PremiumLRS 勘定科目の種類には、アクセス層を設定することはできません。</span><span class="sxs-lookup"><span data-stu-id="8be89-104">Access tier cannot be set for StandardLRS, StandardGRS, StandardRAGRS, or PremiumLRS account types.</span></span>
            <span data-ttu-id="8be89-105">使用可能な値が含まれます: 'ホット'、'ね' です。</span><span class="sxs-lookup"><span data-stu-id="8be89-105">Possible values include: 'Hot', 'Cool'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountStatuses">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.AccountStatuses AccountStatuses { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Fluent.AccountStatuses AccountStatuses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.AccountStatuses" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccountStatuses As AccountStatuses" />
      <MemberSignature Language="F#" Value="member this.AccountStatuses : Microsoft.Azure.Management.Storage.Fluent.AccountStatuses" Usage="Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.AccountStatuses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.AccountStatuses</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8be89-106">ストレージ アカウントのプライマリとセカンダリの場所が使用可能または利用できないかどうかを示すステータスを取得します。</span><span class="sxs-lookup"><span data-stu-id="8be89-106">Gets the status indicating whether the primary and secondary location of the storage account is available or unavailable.</span></span> <span data-ttu-id="8be89-107">使用可能な値が含まれます: 使用可能'、'を使用できません' です。</span><span class="sxs-lookup"><span data-stu-id="8be89-107">Possible values include: 'Available', 'Unavailable'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationTime">
      <MemberSignature Language="C#" Value="public DateTime CreationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime CreationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.CreationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreationTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.CreationTime : DateTime" Usage="Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.CreationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8be89-108">ストレージ アカウントの作成日時を UTC で取得します。</span><span class="sxs-lookup"><span data-stu-id="8be89-108">Gets the creation date and time of the storage account in UTC.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomDomain">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain CustomDomain { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain CustomDomain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.CustomDomain" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CustomDomain As CustomDomain" />
      <MemberSignature Language="F#" Value="member this.CustomDomain : Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain" Usage="Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.CustomDomain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8be89-109">このストレージ アカウントに割り当てられているカスタム ドメインを割り当てられているユーザーを取得します。</span><span class="sxs-lookup"><span data-stu-id="8be89-109">Gets the user assigned custom domain assigned to this storage account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Encryption">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.Models.Encryption Encryption { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Fluent.Models.Encryption Encryption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.Encryption" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Encryption As Encryption" />
      <MemberSignature Language="F#" Value="member this.Encryption : Microsoft.Azure.Management.Storage.Fluent.Models.Encryption" Usage="Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.Encryption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.Models.Encryption</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8be89-110">アカウントの暗号化の設定を取得します。</span><span class="sxs-lookup"><span data-stu-id="8be89-110">Gets the encryption settings on the account.</span></span> <span data-ttu-id="8be89-111">アカウントは暗号化されませんを指定しない場合。</span><span class="sxs-lookup"><span data-stu-id="8be89-111">If unspecified the account is unencrypted.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionKeySource">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.StorageAccountEncryptionKeySource EncryptionKeySource { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Fluent.StorageAccountEncryptionKeySource EncryptionKeySource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.EncryptionKeySource" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EncryptionKeySource As StorageAccountEncryptionKeySource" />
      <MemberSignature Language="F#" Value="member this.EncryptionKeySource : Microsoft.Azure.Management.Storage.Fluent.StorageAccountEncryptionKeySource" Usage="Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.EncryptionKeySource" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.StorageAccountEncryptionKeySource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionStatuses">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;Microsoft.Azure.Management.Storage.Fluent.StorageService,Microsoft.Azure.Management.Storage.Fluent.IStorageAccountEncryptionStatus&gt; EncryptionStatuses { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;class Microsoft.Azure.Management.Storage.Fluent.StorageService, class Microsoft.Azure.Management.Storage.Fluent.IStorageAccountEncryptionStatus&gt; EncryptionStatuses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.EncryptionStatuses" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EncryptionStatuses As IReadOnlyDictionary(Of StorageService, IStorageAccountEncryptionStatus)" />
      <MemberSignature Language="F#" Value="member this.EncryptionStatuses : System.Collections.Generic.IReadOnlyDictionary&lt;Microsoft.Azure.Management.Storage.Fluent.StorageService, Microsoft.Azure.Management.Storage.Fluent.IStorageAccountEncryptionStatus&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.EncryptionStatuses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;Microsoft.Azure.Management.Storage.Fluent.StorageService,Microsoft.Azure.Management.Storage.Fluent.IStorageAccountEncryptionStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndPoints">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.PublicEndpoints EndPoints { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Fluent.PublicEndpoints EndPoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.EndPoints" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EndPoints As PublicEndpoints" />
      <MemberSignature Language="F#" Value="member this.EndPoints : Microsoft.Azure.Management.Storage.Fluent.PublicEndpoints" Usage="Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.EndPoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.PublicEndpoints</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8be89-112">パブリック blob、キュー、またはテーブル オブジェクトの取得する際に使用する Url を取得します。</span><span class="sxs-lookup"><span data-stu-id="8be89-112">Gets the URLs that are used to perform a retrieval of a public blob, queue or table object.</span></span> <span data-ttu-id="8be89-113">StandardZRS および PremiumLRS アカウントは、blob エンドポイントのみを返すことに注意してください。</span><span class="sxs-lookup"><span data-stu-id="8be89-113">Note that StandardZRS and PremiumLRS accounts only return the blob endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetKeys">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountKey&gt; GetKeys ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountKey&gt; GetKeys() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.GetKeys" />
      <MemberSignature Language="VB.NET" Value="Public Function GetKeys () As IReadOnlyList(Of StorageAccountKey)" />
      <MemberSignature Language="F#" Value="abstract member GetKeys : unit -&gt; System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountKey&gt;" Usage="iStorageAccount.GetKeys " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8be89-114">このストレージ アカウントを Azure からの最新の状態のアクセス キーを取得します。</span><span class="sxs-lookup"><span data-stu-id="8be89-114">Fetch the up-to-date access keys from Azure for this storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="8be89-115">このストレージ アカウントのアクセス キー。</span><span class="sxs-lookup"><span data-stu-id="8be89-115">The access keys for this storage account.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="GetKeysAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountKey&gt;&gt; GetKeysAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountKey&gt;&gt; GetKeysAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.GetKeysAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetKeysAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountKey&gt;&gt;" Usage="iStorageAccount.GetKeysAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountKey&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="8be89-116">最新の状態のアクセス キーを非同期的にこのストレージ アカウント Azure からフェッチします。</span><span class="sxs-lookup"><span data-stu-id="8be89-116">Fetch the up-to-date access keys from Azure for this storage account asynchronously.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="8be89-117">(ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。</span><span class="sxs-lookup"><span data-stu-id="8be89-117">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
        <return><span data-ttu-id="8be89-118">観測可能なオブジェクトへのアクセスには、このストレージ アカウントのキーします。</span><span class="sxs-lookup"><span data-stu-id="8be89-118">Observable to the access keys for this storage account.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.Models.Kind Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Storage.Fluent.Models.Kind Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As Kind" />
      <MemberSignature Language="F#" Value="member this.Kind : Microsoft.Azure.Management.Storage.Fluent.Models.Kind" Usage="Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.Models.Kind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8be89-119">ストレージ アカウントの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="8be89-119">Gets the kind of the storage account.</span></span> <span data-ttu-id="8be89-120">使用可能な値は、'Storage'、'BlobStorage' です。</span><span class="sxs-lookup"><span data-stu-id="8be89-120">Possible values are 'Storage', 'BlobStorage'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastGeoFailoverTime">
      <MemberSignature Language="C#" Value="public DateTime LastGeoFailoverTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastGeoFailoverTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.LastGeoFailoverTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastGeoFailoverTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastGeoFailoverTime : DateTime" Usage="Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.LastGeoFailoverTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8be89-121">2 次拠点へのフェールオーバーの最新のインスタンスのタイムスタンプを取得します。</span><span class="sxs-lookup"><span data-stu-id="8be89-121">Gets the timestamp of the most recent instance of a failover to the secondary location.</span></span> <span data-ttu-id="8be89-122">最新のタイムスタンプのみが保持されます。</span><span class="sxs-lookup"><span data-stu-id="8be89-122">Only the most recent timestamp is retained.</span></span> <span data-ttu-id="8be89-123">フェールオーバー インスタンスなりました場合は、この要素は返されません。</span><span class="sxs-lookup"><span data-stu-id="8be89-123">This element is not returned if there has never been a failover instance.</span></span>
            <span data-ttu-id="8be89-124">StandardGRS または StandardRAGRS、accountType の場合にのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="8be89-124">Only available if the accountType is StandardGRS or StandardRAGRS.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.Models.ProvisioningState ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Storage.Fluent.Models.ProvisioningState ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As ProvisioningState" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Microsoft.Azure.Management.Storage.Fluent.Models.ProvisioningState" Usage="Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.Models.ProvisioningState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8be89-125">操作が呼び出された時点でストレージ アカウントの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="8be89-125">Gets the status of the storage account at the time the operation was called.</span></span> <span data-ttu-id="8be89-126">使用可能な値が含まれます: '作成中'、'ResolvingDNS'、'成功' です。</span><span class="sxs-lookup"><span data-stu-id="8be89-126">Possible values include: 'Creating', 'ResolvingDNS', 'Succeeded'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKey">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountKey&gt; RegenerateKey (string keyName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountKey&gt; RegenerateKey(string keyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.RegenerateKey(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegenerateKey (keyName As String) As IReadOnlyList(Of StorageAccountKey)" />
      <MemberSignature Language="F#" Value="abstract member RegenerateKey : string -&gt; System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountKey&gt;" Usage="iStorageAccount.RegenerateKey keyName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="keyName"><span data-ttu-id="8be89-127">場合、キー名。</span><span class="sxs-lookup"><span data-stu-id="8be89-127">If the key name.</span></span></param>
        <summary>
            <span data-ttu-id="8be89-128">このストレージ アカウントのアクセス キーを再生成します。</span><span class="sxs-lookup"><span data-stu-id="8be89-128">Regenerates the access keys for this storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="8be89-129">生成されたアクセスは、このストレージ アカウントをキーします。</span><span class="sxs-lookup"><span data-stu-id="8be89-129">The generated access keys for this storage account.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountKey&gt;&gt; RegenerateKeyAsync (string keyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountKey&gt;&gt; RegenerateKeyAsync(string keyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.RegenerateKeyAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RegenerateKeyAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountKey&gt;&gt;" Usage="iStorageAccount.RegenerateKeyAsync (keyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountKey&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="keyName"><span data-ttu-id="8be89-130">場合、キー名。</span><span class="sxs-lookup"><span data-stu-id="8be89-130">If the key name.</span></span></param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="8be89-131">非同期的に、このストレージ アカウントのアクセス キーを再生成します。</span><span class="sxs-lookup"><span data-stu-id="8be89-131">Regenerates the access keys for this storage account asynchronously.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="8be89-132">(ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。</span><span class="sxs-lookup"><span data-stu-id="8be89-132">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
        <return><span data-ttu-id="8be89-133">観測可能なオブジェクトへのアクセスには、このストレージ アカウントのキーします。</span><span class="sxs-lookup"><span data-stu-id="8be89-133">Observable to the access keys for this storage account.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.Models.Sku Sku { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Fluent.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.Sku" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Storage.Fluent.Models.Sku" Usage="Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8be89-134">このストレージ アカウントの sku を取得します。</span><span class="sxs-lookup"><span data-stu-id="8be89-134">Gets the sku of this storage account.</span></span> <span data-ttu-id="8be89-135">使用可能な名前が含まれます: 'Standard_LRS'、'が ' standard_zrs の場合、'Standard_GRS'、'Standard_RAGRS'、'Premium_LRS' です。</span><span class="sxs-lookup"><span data-stu-id="8be89-135">Possible names include: 'Standard_LRS', 'Standard_ZRS', 'Standard_GRS', 'Standard_RAGRS', 'Premium_LRS'.</span></span> <span data-ttu-id="8be89-136">可能な階層があります。: 'Standard'、'Premium' です。</span><span class="sxs-lookup"><span data-stu-id="8be89-136">Possible tiers include: 'Standard', 'Premium'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>