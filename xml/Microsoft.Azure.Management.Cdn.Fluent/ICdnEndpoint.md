<Type Name="ICdnEndpoint" FullName="Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint">
  <TypeSignature Language="C#" Value="public interface ICdnEndpoint : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint,Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ICdnEndpoint implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource`2&lt;class Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint, class Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint" />
  <TypeSignature Language="VB.NET" Value="Public Interface ICdnEndpoint&#xA;Implements IChildResource(Of ICdnProfile), IExternalChildResource(Of ICdnEndpoint, ICdnProfile), IHasInner(Of EndpointInner), IHasParent(Of ICdnProfile), IRefreshable(Of ICdnEndpoint)" />
  <TypeSignature Language="F#" Value="type ICdnEndpoint = interface&#xA;    interface IExternalChildResource&lt;ICdnEndpoint, ICdnProfile&gt;&#xA;    interface IChildResource&lt;ICdnProfile&gt;&#xA;    interface IHasName&#xA;    interface IIndexable&#xA;    interface IHasParent&lt;ICdnProfile&gt;&#xA;    interface IRefreshable&lt;ICdnEndpoint&gt;&#xA;    interface IHasInner&lt;EndpointInner&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint,Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="a7239-101">Azure CDN エンドポイントの変更できないクライアント側表現。</span><span class="sxs-lookup"><span data-stu-id="a7239-101">An immutable client-side representation of an Azure CDN endpoint.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ContentTypesToCompress">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.ISet&lt;string&gt; ContentTypesToCompress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.ISet`1&lt;string&gt; ContentTypesToCompress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.ContentTypesToCompress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContentTypesToCompress As ISet(Of String)" />
      <MemberSignature Language="F#" Value="member this.ContentTypesToCompress : System.Collections.Generic.ISet&lt;string&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.ContentTypesToCompress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.ISet&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a7239-102">圧縮するコンテンツの種類の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="a7239-102">Gets list of content types to be compressed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="a7239-103">取得 (ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。</span><span class="sxs-lookup"><span data-stu-id="a7239-103">Gets (Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomDomains">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.ISet&lt;string&gt; CustomDomains { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.ISet`1&lt;string&gt; CustomDomains" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.CustomDomains" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CustomDomains As ISet(Of String)" />
      <MemberSignature Language="F#" Value="member this.CustomDomains : System.Collections.Generic.ISet&lt;string&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.CustomDomains" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.ISet&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a7239-104">このエンドポイントに関連付けられているカスタム ドメインの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="a7239-104">Gets list of custom domains associated with this endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="a7239-105">取得 (ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。</span><span class="sxs-lookup"><span data-stu-id="a7239-105">Gets (Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GeoFilters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter&gt; GeoFilters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter&gt; GeoFilters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.GeoFilters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property GeoFilters As IReadOnlyList(Of GeoFilter)" />
      <MemberSignature Language="F#" Value="member this.GeoFilters : System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.GeoFilters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a7239-106">地理的フィルターの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="a7239-106">Gets list of Geo filters.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostName">
      <MemberSignature Language="C#" Value="public string HostName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.HostName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HostName As String" />
      <MemberSignature Language="F#" Value="member this.HostName : string" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.HostName" />
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
            <span data-ttu-id="a7239-107">エンドポイントのホスト名を取得します。</span><span class="sxs-lookup"><span data-stu-id="a7239-107">Gets endpoint host name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpPort">
      <MemberSignature Language="C#" Value="public int HttpPort { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 HttpPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.HttpPort" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HttpPort As Integer" />
      <MemberSignature Language="F#" Value="member this.HttpPort : int" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.HttpPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a7239-108">HTTP ポート値を取得します。</span><span class="sxs-lookup"><span data-stu-id="a7239-108">Gets HTTP port value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpsPort">
      <MemberSignature Language="C#" Value="public int HttpsPort { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 HttpsPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.HttpsPort" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HttpsPort As Integer" />
      <MemberSignature Language="F#" Value="member this.HttpsPort : int" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.HttpsPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a7239-109">HTTPS ポート値を取得します。</span><span class="sxs-lookup"><span data-stu-id="a7239-109">Gets HTTPS port value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsCompressionEnabled">
      <MemberSignature Language="C#" Value="public bool IsCompressionEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsCompressionEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.IsCompressionEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsCompressionEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsCompressionEnabled : bool" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.IsCompressionEnabled" />
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
            <span data-ttu-id="a7239-110">コンテンツの圧縮が有効になっていない場合は false の場合は true を取得します。</span><span class="sxs-lookup"><span data-stu-id="a7239-110">Gets true if content compression is enabled, otherwise false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsHttpAllowed">
      <MemberSignature Language="C#" Value="public bool IsHttpAllowed { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsHttpAllowed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.IsHttpAllowed" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsHttpAllowed As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsHttpAllowed : bool" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.IsHttpAllowed" />
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
            <span data-ttu-id="a7239-111">HTTP トラフィックできる場合は true、それ以外の場合は false を取得します。</span><span class="sxs-lookup"><span data-stu-id="a7239-111">Gets true if HTTP traffic is allowed, otherwise false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsHttpsAllowed">
      <MemberSignature Language="C#" Value="public bool IsHttpsAllowed { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsHttpsAllowed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.IsHttpsAllowed" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsHttpsAllowed As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsHttpsAllowed : bool" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.IsHttpsAllowed" />
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
            <span data-ttu-id="a7239-112">HTTPS トラフィックが許可された場合、それ以外の場合は false、true を取得します。</span><span class="sxs-lookup"><span data-stu-id="a7239-112">Gets true if HTTPS traffic is allowed, otherwise false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListResourceUsage">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsage&gt; ListResourceUsage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsage&gt; ListResourceUsage() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.ListResourceUsage" />
      <MemberSignature Language="VB.NET" Value="Public Function ListResourceUsage () As IEnumerable(Of ResourceUsage)" />
      <MemberSignature Language="F#" Value="abstract member ListResourceUsage : unit -&gt; seq&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsage&gt;" Usage="iCdnEndpoint.ListResourceUsage " />
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
        <summary>
            <span data-ttu-id="a7239-113">クォータと地理的フィルターと、現在のエンドポイントでカスタム ドメインの使用状況を確認します。</span><span class="sxs-lookup"><span data-stu-id="a7239-113">Checks the quota and usage of geo filters and custom domains under the current endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a7239-114">クォータと使用法の地理的フィルターと、現在のエンドポイントでカスタム ドメインの一覧です。</span><span class="sxs-lookup"><span data-stu-id="a7239-114">List of quotas and usages of geo filters and custom domains under the current endpoint.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="LoadContent">
      <MemberSignature Language="C#" Value="public void LoadContent (System.Collections.Generic.ISet&lt;string&gt; contentPaths);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void LoadContent(class System.Collections.Generic.ISet`1&lt;string&gt; contentPaths) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.LoadContent(System.Collections.Generic.ISet{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub LoadContent (contentPaths As ISet(Of String))" />
      <MemberSignature Language="F#" Value="abstract member LoadContent : System.Collections.Generic.ISet&lt;string&gt; -&gt; unit" Usage="iCdnEndpoint.LoadContent contentPaths" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="contentPaths" Type="System.Collections.Generic.ISet&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="contentPaths">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadContentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task LoadContentAsync (System.Collections.Generic.ISet&lt;string&gt; contentPaths, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task LoadContentAsync(class System.Collections.Generic.ISet`1&lt;string&gt; contentPaths, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.LoadContentAsync(System.Collections.Generic.ISet{System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member LoadContentAsync : System.Collections.Generic.ISet&lt;string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iCdnEndpoint.LoadContentAsync (contentPaths, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="contentPaths" Type="System.Collections.Generic.ISet&lt;System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="contentPaths">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OptimizationType">
      <MemberSignature Language="C#" Value="public string OptimizationType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OptimizationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.OptimizationType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OptimizationType As String" />
      <MemberSignature Language="F#" Value="member this.OptimizationType : string" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.OptimizationType" />
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
            <span data-ttu-id="a7239-115">最適化の種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="a7239-115">Gets optimization type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OriginHostHeader">
      <MemberSignature Language="C#" Value="public string OriginHostHeader { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OriginHostHeader" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.OriginHostHeader" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OriginHostHeader As String" />
      <MemberSignature Language="F#" Value="member this.OriginHostHeader : string" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.OriginHostHeader" />
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
            <span data-ttu-id="a7239-116">配信元ホスト ヘッダーを取得します。</span><span class="sxs-lookup"><span data-stu-id="a7239-116">Gets origin host header.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OriginHostName">
      <MemberSignature Language="C#" Value="public string OriginHostName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OriginHostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.OriginHostName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OriginHostName As String" />
      <MemberSignature Language="F#" Value="member this.OriginHostName : string" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.OriginHostName" />
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
            <span data-ttu-id="a7239-117">配信元ホスト名を取得します。</span><span class="sxs-lookup"><span data-stu-id="a7239-117">Gets origin host name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OriginPath">
      <MemberSignature Language="C#" Value="public string OriginPath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OriginPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.OriginPath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OriginPath As String" />
      <MemberSignature Language="F#" Value="member this.OriginPath : string" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.OriginPath" />
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
            <span data-ttu-id="a7239-118">配信元のパスを取得します。</span><span class="sxs-lookup"><span data-stu-id="a7239-118">Gets origin path.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.ProvisioningState" />
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
            <span data-ttu-id="a7239-119">エンドポイントのプロビジョニング状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="a7239-119">Gets endpoint provisioning state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeContent">
      <MemberSignature Language="C#" Value="public void PurgeContent (System.Collections.Generic.ISet&lt;string&gt; contentPaths);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void PurgeContent(class System.Collections.Generic.ISet`1&lt;string&gt; contentPaths) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.PurgeContent(System.Collections.Generic.ISet{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub PurgeContent (contentPaths As ISet(Of String))" />
      <MemberSignature Language="F#" Value="abstract member PurgeContent : System.Collections.Generic.ISet&lt;string&gt; -&gt; unit" Usage="iCdnEndpoint.PurgeContent contentPaths" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="contentPaths" Type="System.Collections.Generic.ISet&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="contentPaths">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeContentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PurgeContentAsync (System.Collections.Generic.ISet&lt;string&gt; contentPaths, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task PurgeContentAsync(class System.Collections.Generic.ISet`1&lt;string&gt; contentPaths, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.PurgeContentAsync(System.Collections.Generic.ISet{System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PurgeContentAsync : System.Collections.Generic.ISet&lt;string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iCdnEndpoint.PurgeContentAsync (contentPaths, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="contentPaths" Type="System.Collections.Generic.ISet&lt;System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="contentPaths">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QueryStringCachingBehavior">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.Models.QueryStringCachingBehavior QueryStringCachingBehavior { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Cdn.Fluent.Models.QueryStringCachingBehavior QueryStringCachingBehavior" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.QueryStringCachingBehavior" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property QueryStringCachingBehavior As QueryStringCachingBehavior" />
      <MemberSignature Language="F#" Value="member this.QueryStringCachingBehavior : Microsoft.Azure.Management.Cdn.Fluent.Models.QueryStringCachingBehavior" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.QueryStringCachingBehavior" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.Models.QueryStringCachingBehavior</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a7239-120">取得では、文字列のキャッシュ動作をクエリします。</span><span class="sxs-lookup"><span data-stu-id="a7239-120">Gets query string caching behavior.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceState">
      <MemberSignature Language="C#" Value="public string ResourceState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.ResourceState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceState As String" />
      <MemberSignature Language="F#" Value="member this.ResourceState : string" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.ResourceState" />
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
            <span data-ttu-id="a7239-121">エンドポイントの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="a7239-121">Gets endpoint state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Start">
      <MemberSignature Language="C#" Value="public void Start ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Start() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.Start" />
      <MemberSignature Language="VB.NET" Value="Public Sub Start ()" />
      <MemberSignature Language="F#" Value="abstract member Start : unit -&gt; unit" Usage="iCdnEndpoint.Start " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a7239-122">停止している場合は、CDN エンドポイントを起動します。</span><span class="sxs-lookup"><span data-stu-id="a7239-122">Starts the CDN endpoint, if it is stopped.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task StartAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.StartAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member StartAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iCdnEndpoint.StartAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="a7239-123">停止している場合は、CDN エンドポイントを非同期的に開始されます。</span><span class="sxs-lookup"><span data-stu-id="a7239-123">Starts the CDN endpoint asynchronously, if it is stopped.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="a7239-124">(ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。</span><span class="sxs-lookup"><span data-stu-id="a7239-124">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
        <return><span data-ttu-id="a7239-125">この呼び出しの遅延の計算の表現。</span><span class="sxs-lookup"><span data-stu-id="a7239-125">A representation of the deferred computation of this call.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="Stop">
      <MemberSignature Language="C#" Value="public void Stop ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Stop() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.Stop" />
      <MemberSignature Language="VB.NET" Value="Public Sub Stop ()" />
      <MemberSignature Language="F#" Value="abstract member Stop : unit -&gt; unit" Usage="iCdnEndpoint.Stop " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a7239-126">実行されている場合は、CDN エンドポイントを停止します。</span><span class="sxs-lookup"><span data-stu-id="a7239-126">Stops the CDN endpoint, if it is running.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StopAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StopAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task StopAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.StopAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member StopAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iCdnEndpoint.StopAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="a7239-127">実行されている場合は、CDN エンドポイントを非同期的に、停止します。</span><span class="sxs-lookup"><span data-stu-id="a7239-127">Stops the CDN endpoint asynchronously, if it is running.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="a7239-128">(ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。</span><span class="sxs-lookup"><span data-stu-id="a7239-128">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
        <return><span data-ttu-id="a7239-129">この呼び出しの遅延の計算の表現。</span><span class="sxs-lookup"><span data-stu-id="a7239-129">A representation of the deferred computation of this call.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="ValidateCustomDomain">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CustomDomainValidationResult ValidateCustomDomain (string hostName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CustomDomainValidationResult ValidateCustomDomain(string hostName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.ValidateCustomDomain(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ValidateCustomDomain (hostName As String) As CustomDomainValidationResult" />
      <MemberSignature Language="F#" Value="abstract member ValidateCustomDomain : string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CustomDomainValidationResult" Usage="iCdnEndpoint.ValidateCustomDomain hostName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CustomDomainValidationResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="hostName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="hostName"><span data-ttu-id="a7239-130">ホスト名、カスタム ドメインのドメイン名を指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="a7239-130">The host name, which must be a domain name, of the custom domain.</span></span></param>
        <summary>
            <span data-ttu-id="a7239-131">現在のエンドポイントの正しい CNAME を DNS にマッピングされていることを確認するカスタム ドメインのマップを検証します。</span><span class="sxs-lookup"><span data-stu-id="a7239-131">Validates a custom domain mapping to ensure it maps to the correct CNAME in DNS for current endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a7239-132">正常終了した場合は、アクションの結果です。</span><span class="sxs-lookup"><span data-stu-id="a7239-132">The result of the action, if successful.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="ValidateCustomDomainAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.CustomDomainValidationResult&gt; ValidateCustomDomainAsync (string hostName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.CustomDomainValidationResult&gt; ValidateCustomDomainAsync(string hostName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.ValidateCustomDomainAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ValidateCustomDomainAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.CustomDomainValidationResult&gt;" Usage="iCdnEndpoint.ValidateCustomDomainAsync (hostName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.CustomDomainValidationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="hostName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="hostName"><span data-ttu-id="a7239-133">ホスト名、カスタム ドメインのドメイン名を指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="a7239-133">The host name, which must be a domain name, of the custom domain.</span></span></param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="a7239-134">マップ、正しい CNAME を DNS に現在のエンドポイントを非同期的にことを確認するカスタム ドメインのマップを検証します。</span><span class="sxs-lookup"><span data-stu-id="a7239-134">Validates a custom domain mapping to ensure it maps to the correct CNAME in DNS for current endpoint asynchronously.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="a7239-135">(ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。</span><span class="sxs-lookup"><span data-stu-id="a7239-135">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
        <return><span data-ttu-id="a7239-136">結果の監視対象です。</span><span class="sxs-lookup"><span data-stu-id="a7239-136">An observable of the result.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>