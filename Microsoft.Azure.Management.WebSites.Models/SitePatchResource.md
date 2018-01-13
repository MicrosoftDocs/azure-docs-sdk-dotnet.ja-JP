<Type Name="SitePatchResource" FullName="Microsoft.Azure.Management.WebSites.Models.SitePatchResource">
  <TypeSignature Language="C#" Value="public class SitePatchResource : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SitePatchResource extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.SitePatchResource" />
  <TypeSignature Language="VB.NET" Value="Public Class SitePatchResource&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type SitePatchResource = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            サイトの ARM リソースです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SitePatchResource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.SitePatchResource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            SitePatchResource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SitePatchResource (string id = null, string name = null, string kind = null, string type = null, string state = null, System.Collections.Generic.IList&lt;string&gt; hostNames = null, string repositorySiteName = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.UsageState&gt; usageState = null, Nullable&lt;bool&gt; enabled = null, System.Collections.Generic.IList&lt;string&gt; enabledHostNames = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.SiteAvailabilityState&gt; availabilityState = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HostNameSslState&gt; hostNameSslStates = null, string serverFarmId = null, Nullable&lt;bool&gt; reserved = null, Nullable&lt;DateTime&gt; lastModifiedTimeUtc = null, Microsoft.Azure.Management.WebSites.Models.SiteConfig siteConfig = null, System.Collections.Generic.IList&lt;string&gt; trafficManagerHostNames = null, Nullable&lt;bool&gt; scmSiteAlsoStopped = null, string targetSwapSlot = null, Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile hostingEnvironmentProfile = null, Nullable&lt;bool&gt; clientAffinityEnabled = null, Nullable&lt;bool&gt; clientCertEnabled = null, Nullable&lt;bool&gt; hostNamesDisabled = null, string outboundIpAddresses = null, string possibleOutboundIpAddresses = null, Nullable&lt;int&gt; containerSize = null, Nullable&lt;int&gt; dailyMemoryTimeQuota = null, Nullable&lt;DateTime&gt; suspendedTill = null, Nullable&lt;int&gt; maxNumberOfWorkers = null, Microsoft.Azure.Management.WebSites.Models.CloningInfo cloningInfo = null, Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest snapshotInfo = null, string resourceGroup = null, Nullable&lt;bool&gt; isDefaultContainer = null, string defaultHostName = null, Microsoft.Azure.Management.WebSites.Models.SlotSwapStatus slotSwapStatus = null, Nullable&lt;bool&gt; httpsOnly = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string state, class System.Collections.Generic.IList`1&lt;string&gt; hostNames, string repositorySiteName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.UsageState&gt; usageState, valuetype System.Nullable`1&lt;bool&gt; enabled, class System.Collections.Generic.IList`1&lt;string&gt; enabledHostNames, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.SiteAvailabilityState&gt; availabilityState, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.HostNameSslState&gt; hostNameSslStates, string serverFarmId, valuetype System.Nullable`1&lt;bool&gt; reserved, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastModifiedTimeUtc, class Microsoft.Azure.Management.WebSites.Models.SiteConfig siteConfig, class System.Collections.Generic.IList`1&lt;string&gt; trafficManagerHostNames, valuetype System.Nullable`1&lt;bool&gt; scmSiteAlsoStopped, string targetSwapSlot, class Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile hostingEnvironmentProfile, valuetype System.Nullable`1&lt;bool&gt; clientAffinityEnabled, valuetype System.Nullable`1&lt;bool&gt; clientCertEnabled, valuetype System.Nullable`1&lt;bool&gt; hostNamesDisabled, string outboundIpAddresses, string possibleOutboundIpAddresses, valuetype System.Nullable`1&lt;int32&gt; containerSize, valuetype System.Nullable`1&lt;int32&gt; dailyMemoryTimeQuota, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; suspendedTill, valuetype System.Nullable`1&lt;int32&gt; maxNumberOfWorkers, class Microsoft.Azure.Management.WebSites.Models.CloningInfo cloningInfo, class Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest snapshotInfo, string resourceGroup, valuetype System.Nullable`1&lt;bool&gt; isDefaultContainer, string defaultHostName, class Microsoft.Azure.Management.WebSites.Models.SlotSwapStatus slotSwapStatus, valuetype System.Nullable`1&lt;bool&gt; httpsOnly) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.SitePatchResource.#ctor(System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.IList{System.String},System.String,System.Nullable{Microsoft.Azure.Management.WebSites.Models.UsageState},System.Nullable{System.Boolean},System.Collections.Generic.IList{System.String},System.Nullable{Microsoft.Azure.Management.WebSites.Models.SiteAvailabilityState},System.Collections.Generic.IList{Microsoft.Azure.Management.WebSites.Models.HostNameSslState},System.String,System.Nullable{System.Boolean},System.Nullable{System.DateTime},Microsoft.Azure.Management.WebSites.Models.SiteConfig,System.Collections.Generic.IList{System.String},System.Nullable{System.Boolean},System.String,Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.DateTime},System.Nullable{System.Int32},Microsoft.Azure.Management.WebSites.Models.CloningInfo,Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest,System.String,System.Nullable{System.Boolean},System.String,Microsoft.Azure.Management.WebSites.Models.SlotSwapStatus,System.Nullable{System.Boolean})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.SitePatchResource : string * string * string * string * string * System.Collections.Generic.IList&lt;string&gt; * string * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.UsageState&gt; * Nullable&lt;bool&gt; * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.SiteAvailabilityState&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HostNameSslState&gt; * string * Nullable&lt;bool&gt; * Nullable&lt;DateTime&gt; * Microsoft.Azure.Management.WebSites.Models.SiteConfig * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;bool&gt; * string * Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * string * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;int&gt; * Microsoft.Azure.Management.WebSites.Models.CloningInfo * Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest * string * Nullable&lt;bool&gt; * string * Microsoft.Azure.Management.WebSites.Models.SlotSwapStatus * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.SitePatchResource" Usage="new Microsoft.Azure.Management.WebSites.Models.SitePatchResource (id, name, kind, type, state, hostNames, repositorySiteName, usageState, enabled, enabledHostNames, availabilityState, hostNameSslStates, serverFarmId, reserved, lastModifiedTimeUtc, siteConfig, trafficManagerHostNames, scmSiteAlsoStopped, targetSwapSlot, hostingEnvironmentProfile, clientAffinityEnabled, clientCertEnabled, hostNamesDisabled, outboundIpAddresses, possibleOutboundIpAddresses, containerSize, dailyMemoryTimeQuota, suspendedTill, maxNumberOfWorkers, cloningInfo, snapshotInfo, resourceGroup, isDefaultContainer, defaultHostName, slotSwapStatus, httpsOnly)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="state" Type="System.String" />
        <Parameter Name="hostNames" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="repositorySiteName" Type="System.String" />
        <Parameter Name="usageState" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.UsageState&gt;" />
        <Parameter Name="enabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="enabledHostNames" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="availabilityState" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.SiteAvailabilityState&gt;" />
        <Parameter Name="hostNameSslStates" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HostNameSslState&gt;" />
        <Parameter Name="serverFarmId" Type="System.String" />
        <Parameter Name="reserved" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="lastModifiedTimeUtc" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="siteConfig" Type="Microsoft.Azure.Management.WebSites.Models.SiteConfig" />
        <Parameter Name="trafficManagerHostNames" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="scmSiteAlsoStopped" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="targetSwapSlot" Type="System.String" />
        <Parameter Name="hostingEnvironmentProfile" Type="Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile" />
        <Parameter Name="clientAffinityEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="clientCertEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="hostNamesDisabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="outboundIpAddresses" Type="System.String" />
        <Parameter Name="possibleOutboundIpAddresses" Type="System.String" />
        <Parameter Name="containerSize" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="dailyMemoryTimeQuota" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="suspendedTill" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="maxNumberOfWorkers" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cloningInfo" Type="Microsoft.Azure.Management.WebSites.Models.CloningInfo" />
        <Parameter Name="snapshotInfo" Type="Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest" />
        <Parameter Name="resourceGroup" Type="System.String" />
        <Parameter Name="isDefaultContainer" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="defaultHostName" Type="System.String" />
        <Parameter Name="slotSwapStatus" Type="Microsoft.Azure.Management.WebSites.Models.SlotSwapStatus" />
        <Parameter Name="httpsOnly" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="id">リソース id です。</param>
        <param name="name">リソースの名前です。</param>
        <param name="kind">リソースの種類。</param>
        <param name="type">リソースの種類。</param>
        <param name="state">アプリの現在の状態。</param>
        <param name="hostNames">アプリに関連付けられているホスト名です。</param>
        <param name="repositorySiteName">リポジトリ サイトの名前です。</param>
        <param name="usageState">アプリでのクォータ使用率が超過するかどうかを示す状態です。 読み取り専用。 使用可能な値が含まれます: 'Normal'、'を超えました'</param>
        <param name="enabled">&lt;コード&gt;true&lt;/code&gt; 、アプリが有効になっている、それ以外の場合は&lt;コード&gt;false&lt;/code&gt;です。 この値を false に設定すると、アプリ (オフライン アプリ) が無効にします。</param>
        <param name="enabledHostNames">アプリの有効なホスト名です。ホスト名を割り当てる必要があります (ホスト名を参照してください) 有効になっているとします。
            それ以外の場合、アプリは、そのホスト名では処理できません。</param>
        <param name="availabilityState">アプリの管理情報の可用性の状態。 使用可能な値が含まれます: 'Normal'、'Limited'、'DisasterRecoveryMode'</param>
        <param name="hostNameSslStates">ホスト名の SSL の状態は、アプリのホスト名の SSL バインドの管理に使用されます。</param>
        <param name="serverFarmId">リソース ID、関連付けられている App Service プランの設定として書式設定:"/subscriptions/{subscriptionID}/resourceGroups/{groupName}/providers/Microsoft.Web/serverfarms/{appServicePlanName}"。</param>
        <param name="reserved">&lt;コード&gt;true&lt;/code&gt;予約されている場合は、&lt;コード&gt;false&lt;/code&gt;です。</param>
        <param name="lastModifiedTimeUtc">最後の時刻 (utc) で、アプリが変更されました。 読み取り専用。</param>
        <param name="siteConfig">アプリの構成。</param>
        <param name="trafficManagerHostNames">Azure Traffic Manager のホスト名は、アプリに関連付けられています。 読み取り専用。</param>
        <param name="scmSiteAlsoStopped">&lt;コード&gt;true&lt;/code&gt; 、アプリが停止している、それ以外の場合は、SCM (KUDU) サイトを停止する&lt;コード&gt;false&lt;/code&gt;です。 既定値は&lt;コード&gt;false&lt;/code&gt;です。</param>
        <param name="targetSwapSlot">このアプリにスワップは展開スロットを指定します。 読み取り専用。</param>
        <param name="hostingEnvironmentProfile">アプリの使用を app Service 環境。</param>
        <param name="clientAffinityEnabled">&lt;コード&gt;true&lt;/code&gt;クライアントのアフィニティを有効にするには&lt;コード&gt;false&lt;/code&gt;セッション アフィニティ cookie は、同じインスタンスを同じセッションでクライアント要求をルーティングの送信を停止します。 既定値は&lt;コード&gt;true&lt;/code&gt;です。</param>
        <param name="clientCertEnabled">&lt;コード&gt;true&lt;/code&gt; (TLS の相互認証) です。 クライアント証明書認証を有効にするそれ以外の場合、&lt;コード&gt;false&lt;/code&gt;です。 既定値は&lt;コード&gt;false&lt;/code&gt;です。</param>
        <param name="hostNamesDisabled">&lt;コード&gt;true&lt;/code&gt; ; アプリのパブリック ホスト名を無効にするそれ以外の場合、&lt;コード&gt;false&lt;/code&gt;です。
            場合&lt;コード&gt;true&lt;/code&gt;アプリは API 管理プロセスを使用してアクセスできるのみです。</param>
        <param name="outboundIpAddresses">アプリで使用する (例: データベースへのアクセス) の発信接続用の IP アドレスの一覧です。 Vip を含むテナントからは、現在の設定でそのサイトがホストされることができます。
            読み取り専用。</param>
        <param name="possibleOutboundIpAddresses">アプリで使用する (例: データベースへのアクセス) の発信接続用の IP アドレスの一覧です。
            すべてのテナントからは、Vip が含まれています。 読み取り専用。</param>
        <param name="containerSize">関数のコンテナーのサイズです。</param>
        <param name="dailyMemoryTimeQuota">最大日単位のメモリ時間クォータ (動的アプリのみに該当する場合) です。</param>
        <param name="suspendedTill">アプリがメモリにクォータを超えた場合に、まで中断します。</param>
        <param name="maxNumberOfWorkers">ワーカーの最大数。
            これは、関数のコンテナーにのみ適用されます。</param>
        <param name="cloningInfo">アプリの作成時に指定した場合、ソース アプリケーションから、アプリが複製されます。</param>
        <param name="snapshotInfo">アプリの作成時に指定すると、前のスナップショットから、アプリが作成されます。</param>
        <param name="resourceGroup">アプリが属するリソース グループの名前です。 読み取り専用。</param>
        <param name="isDefaultContainer">&lt;コード&gt;true&lt;/code&gt;場合は、アプリが既定のコンテナーです。 それ以外の場合、&lt;コード&gt;false&lt;/code&gt;です。</param>
        <param name="defaultHostName">アプリの既定のホスト名です。
            読み取り専用。</param>
        <param name="slotSwapStatus">最後の展開スロットのスワップ操作の状態です。</param>
        <param name="httpsOnly">HttpsOnly: は、https 要求のみを受け入れるように web サイトを構成します。 問題が http 要求をリダイレクトします。</param>
        <summary>
            SitePatchResource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvailabilityState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.SiteAvailabilityState&gt; AvailabilityState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.SiteAvailabilityState&gt; AvailabilityState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SitePatchResource.AvailabilityState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AvailabilityState As Nullable(Of SiteAvailabilityState)" />
      <MemberSignature Language="F#" Value="member this.AvailabilityState : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.SiteAvailabilityState&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.SitePatchResource.AvailabilityState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.availabilityState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.SiteAvailabilityState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            アプリの管理情報の可用性の状態を取得します。
            使用可能な値が含まれます: 'Normal'、'Limited'、'DisasterRecoveryMode'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientAffinityEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ClientAffinityEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ClientAffinityEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SitePatchResource.ClientAffinityEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientAffinityEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ClientAffinityEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SitePatchResource.ClientAffinityEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.clientAffinityEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定&amp;lt; コード&amp;gt; true&amp;lt;/code&amp;gt; クライアントのアフィニティを有効にするには&amp;lt; コード&amp;gt; false&amp;lt;/code&amp;gt; セッション アフィニティ cookie は、同じインスタンスを同じセッションでクライアント要求をルーティングの送信を停止します。 既定値は&amp;lt; コード&amp;gt; true&amp;lt;/code&amp;gt;。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientCertEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ClientCertEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ClientCertEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SitePatchResource.ClientCertEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientCertEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ClientCertEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SitePatchResource.ClientCertEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.clientCertEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定&amp;lt; コード&amp;gt; true&amp;lt;/code&amp;gt; (TLS の相互認証) ですクライアント証明書認証を有効にするそれ以外の場合、 &amp;lt; コード&amp;gt; false&amp;。lt;/code&amp;gt;。 既定値は&amp;lt; コード&amp;gt; false&amp;lt;/code&amp;gt;。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloningInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.CloningInfo CloningInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.CloningInfo CloningInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SitePatchResource.CloningInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property CloningInfo As CloningInfo" />
      <MemberSignature Language="F#" Value="member this.CloningInfo : Microsoft.Azure.Management.WebSites.Models.CloningInfo with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SitePatchResource.CloningInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.cloningInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.CloningInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定アプリの作成時に指定されている場合、ソース アプリからアプリを複製します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ContainerSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ContainerSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SitePatchResource.ContainerSize" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerSize As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ContainerSize : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SitePatchResource.ContainerSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.containerSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または関数のコンテナーのサイズを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DailyMemoryTimeQuota">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DailyMemoryTimeQuota { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DailyMemoryTimeQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SitePatchResource.DailyMemoryTimeQuota" />
      <MemberSignature Language="VB.NET" Value="Public Property DailyMemoryTimeQuota As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DailyMemoryTimeQuota : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SitePatchResource.DailyMemoryTimeQuota" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dailyMemoryTimeQuota")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定最大日単位のメモリ時間クォータ (動的アプリのみに該当する場合) を許可します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultHostName">
      <MemberSignature Language="C#" Value="public string DefaultHostName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DefaultHostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SitePatchResource.DefaultHostName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultHostName As String" />
      <MemberSignature Language="F#" Value="member this.DefaultHostName : string" Usage="Microsoft.Azure.Management.WebSites.Models.SitePatchResource.DefaultHostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.defaultHostName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            アプリの既定のホスト名を取得します。 読み取り専用。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Enabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Enabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SitePatchResource.Enabled" />
      <MemberSignature Language="VB.NET" Value="Public Property Enabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Enabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SitePatchResource.Enabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定&amp;lt; コード&amp;gt 以外の場合は true。&amp;lt;/code&amp;gt;、アプリが有効になっている、それ以外の場合は&amp;lt; コード&amp;gt 以外の場合は false&amp;lt;/code&amp;gt;。 この値を false に設定すると、アプリ (オフライン アプリ) が無効にします。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnabledHostNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; EnabledHostNames { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; EnabledHostNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SitePatchResource.EnabledHostNames" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnabledHostNames As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.EnabledHostNames : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.SitePatchResource.EnabledHostNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enabledHostNames")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得には、アプリ用のホスト名が有効になります。ホスト名を割り当てる必要があります (ホスト名を参照してください) 有効になっているとします。 それ以外の場合、アプリは、そのホスト名では処理できません。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostingEnvironmentProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile HostingEnvironmentProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile HostingEnvironmentProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SitePatchResource.HostingEnvironmentProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property HostingEnvironmentProfile As HostingEnvironmentProfile" />
      <MemberSignature Language="F#" Value="member this.HostingEnvironmentProfile : Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SitePatchResource.HostingEnvironmentProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hostingEnvironmentProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアプリ、アプリに使用するサービス環境を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; HostNames { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; HostNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SitePatchResource.HostNames" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HostNames As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.HostNames : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.SitePatchResource.HostNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hostNames")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            アプリに関連付けられているホスト名を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostNamesDisabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; HostNamesDisabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; HostNamesDisabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SitePatchResource.HostNamesDisabled" />
      <MemberSignature Language="VB.NET" Value="Public Property HostNamesDisabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.HostNamesDisabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SitePatchResource.HostNamesDisabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hostNamesDisabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定&amp;lt; コード&amp;gt 以外の場合は true&amp;lt;/code&amp;gt; アプリのパブリック ホスト名を無効にするそれ以外の場合、 &amp;lt; コード&amp;gt; false&amp;lt;/code&amp; 。gt;。
            場合&amp;lt; コード&amp;gt 以外の場合は true。&amp;lt;/code&amp;gt;、アプリは API 管理プロセスを使用してアクセスできるのみです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostNameSslStates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HostNameSslState&gt; HostNameSslStates { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.HostNameSslState&gt; HostNameSslStates" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SitePatchResource.HostNameSslStates" />
      <MemberSignature Language="VB.NET" Value="Public Property HostNameSslStates As IList(Of HostNameSslState)" />
      <MemberSignature Language="F#" Value="member this.HostNameSslStates : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HostNameSslState&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SitePatchResource.HostNameSslStates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hostNameSslStates")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HostNameSslState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定 SSL ホスト名の状態は、アプリのホスト名の SSL バインドの管理に使用されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpsOnly">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; HttpsOnly { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; HttpsOnly" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SitePatchResource.HttpsOnly" />
      <MemberSignature Language="VB.NET" Value="Public Property HttpsOnly As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.HttpsOnly : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SitePatchResource.HttpsOnly" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.httpsOnly")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定 httpsOnly: https 要求のみを受け入れるように web サイトを構成します。 問題が http 要求をリダイレクトします。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDefaultContainer">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsDefaultContainer { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsDefaultContainer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SitePatchResource.IsDefaultContainer" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsDefaultContainer As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsDefaultContainer : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.SitePatchResource.IsDefaultContainer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.isDefaultContainer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得&amp;lt; コード&amp;gt 以外の場合は true。&amp;lt;/code&amp;gt; 場合は、アプリが既定のコンテナーです。 それ以外の場合、 &amp;lt; コード&amp;gt 以外の場合は false&amp;lt;/code&amp;gt;。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModifiedTimeUtc">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastModifiedTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastModifiedTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SitePatchResource.LastModifiedTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModifiedTimeUtc As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastModifiedTimeUtc : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.SitePatchResource.LastModifiedTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lastModifiedTimeUtc")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Utc 形式で、アプリが変更された最終時刻を取得します。 読み取り専用。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxNumberOfWorkers">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxNumberOfWorkers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxNumberOfWorkers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SitePatchResource.MaxNumberOfWorkers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxNumberOfWorkers As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxNumberOfWorkers : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.SitePatchResource.MaxNumberOfWorkers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maxNumberOfWorkers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ワーカーの最大数を取得します。
            これは、関数のコンテナーにのみ適用されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutboundIpAddresses">
      <MemberSignature Language="C#" Value="public string OutboundIpAddresses { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OutboundIpAddresses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SitePatchResource.OutboundIpAddresses" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OutboundIpAddresses As String" />
      <MemberSignature Language="F#" Value="member this.OutboundIpAddresses : string" Usage="Microsoft.Azure.Management.WebSites.Models.SitePatchResource.OutboundIpAddresses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.outboundIpAddresses")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            アプリで使用する (例: データベースへのアクセス) の発信接続用の IP アドレスの一覧を取得します。 Vip を含むテナントからは、現在の設定でそのサイトがホストされることができます。 読み取り専用。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PossibleOutboundIpAddresses">
      <MemberSignature Language="C#" Value="public string PossibleOutboundIpAddresses { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PossibleOutboundIpAddresses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SitePatchResource.PossibleOutboundIpAddresses" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PossibleOutboundIpAddresses As String" />
      <MemberSignature Language="F#" Value="member this.PossibleOutboundIpAddresses : string" Usage="Microsoft.Azure.Management.WebSites.Models.SitePatchResource.PossibleOutboundIpAddresses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.possibleOutboundIpAddresses")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            アプリで使用する (例: データベースへのアクセス) の発信接続用の IP アドレスの一覧を取得します。 すべてのテナントからは、Vip が含まれています。
            読み取り専用。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RepositorySiteName">
      <MemberSignature Language="C#" Value="public string RepositorySiteName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RepositorySiteName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SitePatchResource.RepositorySiteName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RepositorySiteName As String" />
      <MemberSignature Language="F#" Value="member this.RepositorySiteName : string" Usage="Microsoft.Azure.Management.WebSites.Models.SitePatchResource.RepositorySiteName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.repositorySiteName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            リポジトリ サイトの名前を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Reserved">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Reserved { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Reserved" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SitePatchResource.Reserved" />
      <MemberSignature Language="VB.NET" Value="Public Property Reserved As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Reserved : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SitePatchResource.Reserved" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.reserved")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定&amp;lt; コード&amp;gt 以外の場合は true。&amp;lt;/code&amp;gt; 予約されている場合は、 &amp;lt; コード&amp;gt 以外の場合は false&amp;lt;/code&amp;gt;。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceGroup">
      <MemberSignature Language="C#" Value="public string ResourceGroup { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceGroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SitePatchResource.ResourceGroup" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceGroup As String" />
      <MemberSignature Language="F#" Value="member this.ResourceGroup : string" Usage="Microsoft.Azure.Management.WebSites.Models.SitePatchResource.ResourceGroup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.resourceGroup")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            アプリが属するリソース グループの名前を取得します。 読み取り専用。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScmSiteAlsoStopped">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ScmSiteAlsoStopped { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ScmSiteAlsoStopped" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SitePatchResource.ScmSiteAlsoStopped" />
      <MemberSignature Language="VB.NET" Value="Public Property ScmSiteAlsoStopped As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ScmSiteAlsoStopped : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SitePatchResource.ScmSiteAlsoStopped" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.scmSiteAlsoStopped")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定&amp;lt; コード&amp;gt 以外の場合は true&amp;lt;/code&amp;gt; を、アプリが停止している、それ以外の場合は、SCM (KUDU) サイトを停止する&amp;lt; コード&amp;gt; false&amp;lt;/code&amp;。gt;。 既定値は&amp;lt; コード&amp;gt; false&amp;lt;/code&amp;gt;。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerFarmId">
      <MemberSignature Language="C#" Value="public string ServerFarmId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServerFarmId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SitePatchResource.ServerFarmId" />
      <MemberSignature Language="VB.NET" Value="Public Property ServerFarmId As String" />
      <MemberSignature Language="F#" Value="member this.ServerFarmId : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SitePatchResource.ServerFarmId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serverFarmId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定として書式設定、関連付けられている、App Service プランのリソース ID:"/subscriptions/{subscriptionID}/resourceGroups/{groupName}/providers/Microsoft.Web/serverfarms/{appServicePlanName}"。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SiteConfig">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.SiteConfig SiteConfig { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.SiteConfig SiteConfig" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SitePatchResource.SiteConfig" />
      <MemberSignature Language="VB.NET" Value="Public Property SiteConfig As SiteConfig" />
      <MemberSignature Language="F#" Value="member this.SiteConfig : Microsoft.Azure.Management.WebSites.Models.SiteConfig with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SitePatchResource.SiteConfig" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.siteConfig")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.SiteConfig</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアプリの構成を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SlotSwapStatus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.SlotSwapStatus SlotSwapStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.SlotSwapStatus SlotSwapStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SitePatchResource.SlotSwapStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SlotSwapStatus As SlotSwapStatus" />
      <MemberSignature Language="F#" Value="member this.SlotSwapStatus : Microsoft.Azure.Management.WebSites.Models.SlotSwapStatus" Usage="Microsoft.Azure.Management.WebSites.Models.SitePatchResource.SlotSwapStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.slotSwapStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.SlotSwapStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            最後の展開スロットのスワップ操作の状態を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SnapshotInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest SnapshotInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest SnapshotInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SitePatchResource.SnapshotInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property SnapshotInfo As SnapshotRecoveryRequest" />
      <MemberSignature Language="F#" Value="member this.SnapshotInfo : Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SitePatchResource.SnapshotInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.snapshotInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定アプリの作成時に指定されている場合、前のスナップショットから、アプリが作成されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public string State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SitePatchResource.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As String" />
      <MemberSignature Language="F#" Value="member this.State : string" Usage="Microsoft.Azure.Management.WebSites.Models.SitePatchResource.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            アプリの現在の状態を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SuspendedTill">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; SuspendedTill { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; SuspendedTill" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SitePatchResource.SuspendedTill" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SuspendedTill As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.SuspendedTill : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.SitePatchResource.SuspendedTill" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.suspendedTill")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            メモリにクォータを超えた場合に、まで中断されているアプリを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetSwapSlot">
      <MemberSignature Language="C#" Value="public string TargetSwapSlot { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetSwapSlot" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SitePatchResource.TargetSwapSlot" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TargetSwapSlot As String" />
      <MemberSignature Language="F#" Value="member this.TargetSwapSlot : string" Usage="Microsoft.Azure.Management.WebSites.Models.SitePatchResource.TargetSwapSlot" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.targetSwapSlot")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得では、このアプリにスワップは展開スロットを指定します。
            読み取り専用。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrafficManagerHostNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; TrafficManagerHostNames { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; TrafficManagerHostNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SitePatchResource.TrafficManagerHostNames" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TrafficManagerHostNames As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.TrafficManagerHostNames : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.SitePatchResource.TrafficManagerHostNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.trafficManagerHostNames")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            アプリに関連付けられている azure の Traffic Manager のホスト名を取得します。
            読み取り専用。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UsageState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.UsageState&gt; UsageState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.UsageState&gt; UsageState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SitePatchResource.UsageState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UsageState As Nullable(Of UsageState)" />
      <MemberSignature Language="F#" Value="member this.UsageState : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.UsageState&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.SitePatchResource.UsageState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.usageState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.UsageState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得の状態は、アプリがそのクォータ使用率を超えたかどうかを示すです。
            読み取り専用。 使用可能な値が含まれます: 'Normal'、'を超えました'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.SitePatchResource.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="sitePatchResource.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>