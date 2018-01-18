<Type Name="ICdnProfile" FullName="Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile">
  <TypeSignature Language="C#" Value="public interface ICdnProfile : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.Cdn.Fluent.ICdnManager,Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Cdn.Fluent.ICdnManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IUpdate&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ICdnProfile implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource`2&lt;class Microsoft.Azure.Management.Cdn.Fluent.ICdnManager, class Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.ICdnManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IUpdate&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile" />
  <TypeSignature Language="VB.NET" Value="Public Interface ICdnProfile&#xA;Implements IGroupableResource(Of ICdnManager, ProfileInner), IHasInner(Of ProfileInner), IHasManager(Of ICdnManager), IRefreshable(Of ICdnProfile), IUpdatable(Of IUpdate)" />
  <TypeSignature Language="F#" Value="type ICdnProfile = interface&#xA;    interface IGroupableResource&lt;ICdnManager, ProfileInner&gt;&#xA;    interface IResource&#xA;    interface IIndexable&#xA;    interface IHasId&#xA;    interface IHasName&#xA;    interface IHasResourceGroup&#xA;    interface IHasManager&lt;ICdnManager&gt;&#xA;    interface IHasInner&lt;ProfileInner&gt;&#xA;    interface IRefreshable&lt;ICdnProfile&gt;&#xA;    interface IUpdatable&lt;IUpdate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.Cdn.Fluent.ICdnManager,Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Cdn.Fluent.ICdnManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IUpdate&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="f08a0-101">Azure CDN のプロファイルの変更できないクライアント側表現。</span><span class="sxs-lookup"><span data-stu-id="f08a0-101">An immutable client-side representation of an Azure CDN profile.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CheckEndpointNameAvailability">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CheckNameAvailabilityResult CheckEndpointNameAvailability (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CheckNameAvailabilityResult CheckEndpointNameAvailability(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile.CheckEndpointNameAvailability(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CheckEndpointNameAvailability (name As String) As CheckNameAvailabilityResult" />
      <MemberSignature Language="F#" Value="abstract member CheckEndpointNameAvailability : string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CheckNameAvailabilityResult" Usage="iCdnProfile.CheckEndpointNameAvailability name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CheckNameAvailabilityResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="f08a0-102">検証するエンドポイント リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="f08a0-102">The endpoint resource name to validate.</span></span></param>
        <summary>
            <span data-ttu-id="f08a0-103">CDN エンドポイントを作成せずには、エンドポイント名の可用性を確認します。</span><span class="sxs-lookup"><span data-stu-id="f08a0-103">Checks the availability of an endpoint name without creating the CDN endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="f08a0-104">正常終了した場合の結果。</span><span class="sxs-lookup"><span data-stu-id="f08a0-104">The result if successful.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="CheckEndpointNameAvailabilityAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.CheckNameAvailabilityResult&gt; CheckEndpointNameAvailabilityAsync (string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.CheckNameAvailabilityResult&gt; CheckEndpointNameAvailabilityAsync(string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile.CheckEndpointNameAvailabilityAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CheckEndpointNameAvailabilityAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.CheckNameAvailabilityResult&gt;" Usage="iCdnProfile.CheckEndpointNameAvailabilityAsync (name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.CheckNameAvailabilityResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="f08a0-105">検証するエンドポイント リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="f08a0-105">The endpoint resource name to validate.</span></span></param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="f08a0-106">CDN エンドポイントを非同期に作成しなくても、エンドポイントの名前の可用性を確認します。</span><span class="sxs-lookup"><span data-stu-id="f08a0-106">Checks the availability of an endpoint name without creating the CDN endpoint asynchronously.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f08a0-107">(ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。</span><span class="sxs-lookup"><span data-stu-id="f08a0-107">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
        <return><span data-ttu-id="f08a0-108">正常終了した場合、結果の観測可能なオブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="f08a0-108">The Observable of the result if successful.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="Endpoints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint&gt; Endpoints { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint&gt; Endpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile.Endpoints" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Endpoints As IReadOnlyDictionary(Of String, ICdnEndpoint)" />
      <MemberSignature Language="F#" Value="member this.Endpoints : System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile.Endpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f08a0-109">名前によってインデックス付けされた CDN マネージャーのプロファイルのエンドポイントを取得します。</span><span class="sxs-lookup"><span data-stu-id="f08a0-109">Gets endpoints in the CDN manager profile, indexed by name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateSsoUri">
      <MemberSignature Language="C#" Value="public string GenerateSsoUri ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string GenerateSsoUri() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile.GenerateSsoUri" />
      <MemberSignature Language="VB.NET" Value="Public Function GenerateSsoUri () As String" />
      <MemberSignature Language="F#" Value="abstract member GenerateSsoUri : unit -&gt; string" Usage="iCdnProfile.GenerateSsoUri " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f08a0-110">高度な管理タスクのために使用される、CDN 補助ポータルにサインインに使用される動的 SSO URI を生成します。</span><span class="sxs-lookup"><span data-stu-id="f08a0-110">Generates a dynamic SSO URI used to sign in to the CDN supplemental portal used for advanced management tasks.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="f08a0-111">URI を使用するサード パーティの web ポータルにログインします。</span><span class="sxs-lookup"><span data-stu-id="f08a0-111">URI used to login to the third party web portal.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="GenerateSsoUriAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GenerateSsoUriAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; GenerateSsoUriAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile.GenerateSsoUriAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GenerateSsoUriAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="iCdnProfile.GenerateSsoUriAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="f08a0-112">SSO の URI の高度な管理タスクに使用する CDN 補助ポータルにサインインするために使用する動的なを非同期に生成します。</span><span class="sxs-lookup"><span data-stu-id="f08a0-112">Asynchronously generates a dynamic SSO URI used to sign into the CDN supplemental portal used for advanced management tasks.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f08a0-113">(ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。</span><span class="sxs-lookup"><span data-stu-id="f08a0-113">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
        <return><span data-ttu-id="f08a0-114">使用される URI を監視可能なサード パーティの web ポータルにログインします。</span><span class="sxs-lookup"><span data-stu-id="f08a0-114">Observable to URI used to login to third party web portal.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="IsPremiumVerizon">
      <MemberSignature Language="C#" Value="public bool IsPremiumVerizon { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsPremiumVerizon" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile.IsPremiumVerizon" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsPremiumVerizon As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsPremiumVerizon : bool" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile.IsPremiumVerizon" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f08a0-115">CDN プロファイルの SKU は、Premium Verizon、偽の場合は true を取得します。</span><span class="sxs-lookup"><span data-stu-id="f08a0-115">Gets true if this CDN profile's SKU is of Premium Verizon, else false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListResourceUsage">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsage&gt; ListResourceUsage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsage&gt; ListResourceUsage() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile.ListResourceUsage" />
      <MemberSignature Language="VB.NET" Value="Public Function ListResourceUsage () As IEnumerable(Of ResourceUsage)" />
      <MemberSignature Language="F#" Value="abstract member ListResourceUsage : unit -&gt; seq&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsage&gt;" Usage="iCdnProfile.ListResourceUsage " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsage&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="f08a0-116">クォータと現在の CDN プロファイルでエンドポイントの実際の使用法です。</span><span class="sxs-lookup"><span data-stu-id="f08a0-116">Quotas and actual usages of endpoints under the current CDN profile.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="LoadEndpointContent">
      <MemberSignature Language="C#" Value="public void LoadEndpointContent (string endpointName, System.Collections.Generic.ISet&lt;string&gt; contentPaths);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void LoadEndpointContent(string endpointName, class System.Collections.Generic.ISet`1&lt;string&gt; contentPaths) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile.LoadEndpointContent(System.String,System.Collections.Generic.ISet{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub LoadEndpointContent (endpointName As String, contentPaths As ISet(Of String))" />
      <MemberSignature Language="F#" Value="abstract member LoadEndpointContent : string * System.Collections.Generic.ISet&lt;string&gt; -&gt; unit" Usage="iCdnProfile.LoadEndpointContent (endpointName, contentPaths)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="contentPaths" Type="System.Collections.Generic.ISet&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="endpointName">To be added.</param>
        <param name="contentPaths">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadEndpointContentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task LoadEndpointContentAsync (string endpointName, System.Collections.Generic.ISet&lt;string&gt; contentPaths, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task LoadEndpointContentAsync(string endpointName, class System.Collections.Generic.ISet`1&lt;string&gt; contentPaths, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile.LoadEndpointContentAsync(System.String,System.Collections.Generic.ISet{System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member LoadEndpointContentAsync : string * System.Collections.Generic.ISet&lt;string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iCdnProfile.LoadEndpointContentAsync (endpointName, contentPaths, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="contentPaths" Type="System.Collections.Generic.ISet&lt;System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="endpointName">To be added.</param>
        <param name="contentPaths">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeEndpointContent">
      <MemberSignature Language="C#" Value="public void PurgeEndpointContent (string endpointName, System.Collections.Generic.ISet&lt;string&gt; contentPaths);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void PurgeEndpointContent(string endpointName, class System.Collections.Generic.ISet`1&lt;string&gt; contentPaths) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile.PurgeEndpointContent(System.String,System.Collections.Generic.ISet{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub PurgeEndpointContent (endpointName As String, contentPaths As ISet(Of String))" />
      <MemberSignature Language="F#" Value="abstract member PurgeEndpointContent : string * System.Collections.Generic.ISet&lt;string&gt; -&gt; unit" Usage="iCdnProfile.PurgeEndpointContent (endpointName, contentPaths)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="contentPaths" Type="System.Collections.Generic.ISet&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="endpointName">To be added.</param>
        <param name="contentPaths">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeEndpointContentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PurgeEndpointContentAsync (string endpointName, System.Collections.Generic.ISet&lt;string&gt; contentPaths, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task PurgeEndpointContentAsync(string endpointName, class System.Collections.Generic.ISet`1&lt;string&gt; contentPaths, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile.PurgeEndpointContentAsync(System.String,System.Collections.Generic.ISet{System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PurgeEndpointContentAsync : string * System.Collections.Generic.ISet&lt;string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iCdnProfile.PurgeEndpointContentAsync (endpointName, contentPaths, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="contentPaths" Type="System.Collections.Generic.ISet&lt;System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="endpointName">To be added.</param>
        <param name="contentPaths">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceState">
      <MemberSignature Language="C#" Value="public string ResourceState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile.ResourceState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceState As String" />
      <MemberSignature Language="F#" Value="member this.ResourceState : string" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile.ResourceState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f08a0-117">CDN プロファイル状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="f08a0-117">Gets CDN profile state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.Models.Sku Sku { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Cdn.Fluent.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile.Sku" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Cdn.Fluent.Models.Sku" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f08a0-118">CDN プロファイルの SKU を取得します。</span><span class="sxs-lookup"><span data-stu-id="f08a0-118">Gets the SKU of the CDN profile.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartEndpoint">
      <MemberSignature Language="C#" Value="public void StartEndpoint (string endpointName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void StartEndpoint(string endpointName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile.StartEndpoint(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub StartEndpoint (endpointName As String)" />
      <MemberSignature Language="F#" Value="abstract member StartEndpoint : string -&gt; unit" Usage="iCdnProfile.StartEndpoint endpointName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="endpointName"><span data-ttu-id="f08a0-119">[プロファイル] で、エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="f08a0-119">A name of an endpoint under the profile.</span></span></param>
        <summary>
            <span data-ttu-id="f08a0-120">停止された CDN エンドポイントを開始します。</span><span class="sxs-lookup"><span data-stu-id="f08a0-120">Starts a stopped CDN endpoint.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartEndpointAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartEndpointAsync (string endpointName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task StartEndpointAsync(string endpointName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile.StartEndpointAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member StartEndpointAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iCdnProfile.StartEndpointAsync (endpointName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="endpointName"><span data-ttu-id="f08a0-121">[プロファイル] で、エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="f08a0-121">A name of an endpoint under the profile.</span></span></param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="f08a0-122">停止された CDN エンドポイントを非同期的に起動します。</span><span class="sxs-lookup"><span data-stu-id="f08a0-122">Starts a stopped CDN endpoint asynchronously.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f08a0-123">(ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。</span><span class="sxs-lookup"><span data-stu-id="f08a0-123">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
        <return><span data-ttu-id="f08a0-124">この呼び出しの遅延の計算の表現。</span><span class="sxs-lookup"><span data-stu-id="f08a0-124">A representation of the deferred computation of this call.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="StopEndpoint">
      <MemberSignature Language="C#" Value="public void StopEndpoint (string endpointName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void StopEndpoint(string endpointName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile.StopEndpoint(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub StopEndpoint (endpointName As String)" />
      <MemberSignature Language="F#" Value="abstract member StopEndpoint : string -&gt; unit" Usage="iCdnProfile.StopEndpoint endpointName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="endpointName"><span data-ttu-id="f08a0-125">[プロファイル] で、エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="f08a0-125">A name of an endpoint under the profile.</span></span></param>
        <summary>
            <span data-ttu-id="f08a0-126">実行中の CDN エンドポイントを停止します。</span><span class="sxs-lookup"><span data-stu-id="f08a0-126">Stops a running CDN endpoint.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StopEndpointAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StopEndpointAsync (string endpointName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task StopEndpointAsync(string endpointName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile.StopEndpointAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member StopEndpointAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iCdnProfile.StopEndpointAsync (endpointName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="endpointName"><span data-ttu-id="f08a0-127">[プロファイル] で、エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="f08a0-127">A name of an endpoint under the profile.</span></span></param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="f08a0-128">非同期的に実行中の CDN エンドポイントを停止します。</span><span class="sxs-lookup"><span data-stu-id="f08a0-128">Stops a running CDN endpoint asynchronously.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f08a0-129">(ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。</span><span class="sxs-lookup"><span data-stu-id="f08a0-129">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
        <return><span data-ttu-id="f08a0-130">この呼び出しの遅延の計算の表現。</span><span class="sxs-lookup"><span data-stu-id="f08a0-130">A representation of the deferred computation of this call.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="ValidateEndpointCustomDomain">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CustomDomainValidationResult ValidateEndpointCustomDomain (string endpointName, string hostName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CustomDomainValidationResult ValidateEndpointCustomDomain(string endpointName, string hostName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile.ValidateEndpointCustomDomain(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ValidateEndpointCustomDomain (endpointName As String, hostName As String) As CustomDomainValidationResult" />
      <MemberSignature Language="F#" Value="abstract member ValidateEndpointCustomDomain : string * string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CustomDomainValidationResult" Usage="iCdnProfile.ValidateEndpointCustomDomain (endpointName, hostName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CustomDomainValidationResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="hostName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="endpointName"><span data-ttu-id="f08a0-131">[プロファイル] で、エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="f08a0-131">A name of the endpoint under the profile.</span></span></param>
        <param name="hostName"><span data-ttu-id="f08a0-132">ドメイン名である必要があります、カスタム ドメインのホスト名。</span><span class="sxs-lookup"><span data-stu-id="f08a0-132">The host name of the custom domain, which must be a domain name.</span></span></param>
        <summary>
            <span data-ttu-id="f08a0-133">現在のプロファイルで正しい CNAME を DNS にマッピングされていることを確認するカスタム ドメインのマップを検証します。</span><span class="sxs-lookup"><span data-stu-id="f08a0-133">Validates a custom domain mapping to ensure it maps to the correct CNAME in DNS in current profile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="f08a0-134">正常終了した場合は、オブジェクトを CustomDomainValidationResult です。</span><span class="sxs-lookup"><span data-stu-id="f08a0-134">CustomDomainValidationResult object if successful.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="ValidateEndpointCustomDomainAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.CustomDomainValidationResult&gt; ValidateEndpointCustomDomainAsync (string endpointName, string hostName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.CustomDomainValidationResult&gt; ValidateEndpointCustomDomainAsync(string endpointName, string hostName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile.ValidateEndpointCustomDomainAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ValidateEndpointCustomDomainAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.CustomDomainValidationResult&gt;" Usage="iCdnProfile.ValidateEndpointCustomDomainAsync (endpointName, hostName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.CustomDomainValidationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="hostName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="endpointName"><span data-ttu-id="f08a0-135">[プロファイル] で、エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="f08a0-135">A name of the endpoint under the profile.</span></span></param>
        <param name="hostName"><span data-ttu-id="f08a0-136">ドメイン名である必要があります、カスタム ドメインのホスト名。</span><span class="sxs-lookup"><span data-stu-id="f08a0-136">The host name of the custom domain, which must be a domain name.</span></span></param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="f08a0-137">マップ、正しい CNAME を DNS に現在のプロファイルで非同期的にことを確認するカスタム ドメインのマップを検証します。</span><span class="sxs-lookup"><span data-stu-id="f08a0-137">Validates a custom domain mapping to ensure it maps to the correct CNAME in DNS in current profile asynchronously.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f08a0-138">(ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。</span><span class="sxs-lookup"><span data-stu-id="f08a0-138">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
        <return><span data-ttu-id="f08a0-139">正常終了した場合、CustomDomainValidationResult オブジェクトに観測可能なオブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="f08a0-139">The Observable to CustomDomainValidationResult object if successful.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>