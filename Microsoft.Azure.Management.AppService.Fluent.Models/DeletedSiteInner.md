<Type Name="DeletedSiteInner" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner">
  <TypeSignature Language="C#" Value="public class DeletedSiteInner : Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DeletedSiteInner extends Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner" />
  <TypeSignature Language="VB.NET" Value="Public Class DeletedSiteInner&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type DeletedSiteInner = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            削除されたアプリです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeletedSiteInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            DeletedSiteInner クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeletedSiteInner (string location = null, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Nullable&lt;DateTime&gt; deletedTimestamp = null, string state = null, System.Collections.Generic.IList&lt;string&gt; hostNames = null, string repositorySiteName = null, Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.UsageState&gt; usageState = null, Nullable&lt;bool&gt; enabled = null, System.Collections.Generic.IList&lt;string&gt; enabledHostNames = null, Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteAvailabilityState&gt; availabilityState = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState&gt; hostNameSslStates = null, string serverFarmId = null, Nullable&lt;bool&gt; reserved = null, Nullable&lt;DateTime&gt; lastModifiedTimeUtc = null, Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfig siteConfig = null, System.Collections.Generic.IList&lt;string&gt; trafficManagerHostNames = null, Nullable&lt;bool&gt; premiumAppDeployed = null, Nullable&lt;bool&gt; scmSiteAlsoStopped = null, string targetSwapSlot = null, Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentProfile hostingEnvironmentProfile = null, string microService = null, string gatewaySiteName = null, Nullable&lt;bool&gt; clientAffinityEnabled = null, Nullable&lt;bool&gt; clientCertEnabled = null, Nullable&lt;bool&gt; hostNamesDisabled = null, string outboundIpAddresses = null, Nullable&lt;int&gt; containerSize = null, Nullable&lt;int&gt; dailyMemoryTimeQuota = null, Nullable&lt;DateTime&gt; suspendedTill = null, Nullable&lt;int&gt; maxNumberOfWorkers = null, Microsoft.Azure.Management.AppService.Fluent.Models.CloningInfo cloningInfo = null, string resourceGroup = null, Nullable&lt;bool&gt; isDefaultContainer = null, string defaultHostName = null, Microsoft.Azure.Management.AppService.Fluent.Models.SlotSwapStatus slotSwapStatus = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; deletedTimestamp, string state, class System.Collections.Generic.IList`1&lt;string&gt; hostNames, string repositorySiteName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.UsageState&gt; usageState, valuetype System.Nullable`1&lt;bool&gt; enabled, class System.Collections.Generic.IList`1&lt;string&gt; enabledHostNames, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.SiteAvailabilityState&gt; availabilityState, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState&gt; hostNameSslStates, string serverFarmId, valuetype System.Nullable`1&lt;bool&gt; reserved, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastModifiedTimeUtc, class Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfig siteConfig, class System.Collections.Generic.IList`1&lt;string&gt; trafficManagerHostNames, valuetype System.Nullable`1&lt;bool&gt; premiumAppDeployed, valuetype System.Nullable`1&lt;bool&gt; scmSiteAlsoStopped, string targetSwapSlot, class Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentProfile hostingEnvironmentProfile, string microService, string gatewaySiteName, valuetype System.Nullable`1&lt;bool&gt; clientAffinityEnabled, valuetype System.Nullable`1&lt;bool&gt; clientCertEnabled, valuetype System.Nullable`1&lt;bool&gt; hostNamesDisabled, string outboundIpAddresses, valuetype System.Nullable`1&lt;int32&gt; containerSize, valuetype System.Nullable`1&lt;int32&gt; dailyMemoryTimeQuota, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; suspendedTill, valuetype System.Nullable`1&lt;int32&gt; maxNumberOfWorkers, class Microsoft.Azure.Management.AppService.Fluent.Models.CloningInfo cloningInfo, string resourceGroup, valuetype System.Nullable`1&lt;bool&gt; isDefaultContainer, string defaultHostName, class Microsoft.Azure.Management.AppService.Fluent.Models.SlotSwapStatus slotSwapStatus) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{System.DateTime},System.String,System.Collections.Generic.IList{System.String},System.String,System.Nullable{Microsoft.Azure.Management.AppService.Fluent.Models.UsageState},System.Nullable{System.Boolean},System.Collections.Generic.IList{System.String},System.Nullable{Microsoft.Azure.Management.AppService.Fluent.Models.SiteAvailabilityState},System.Collections.Generic.IList{Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState},System.String,System.Nullable{System.Boolean},System.Nullable{System.DateTime},Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfig,System.Collections.Generic.IList{System.String},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.String,Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentProfile,System.String,System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.DateTime},System.Nullable{System.Int32},Microsoft.Azure.Management.AppService.Fluent.Models.CloningInfo,System.String,System.Nullable{System.Boolean},System.String,Microsoft.Azure.Management.AppService.Fluent.Models.SlotSwapStatus)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;DateTime&gt; * string * System.Collections.Generic.IList&lt;string&gt; * string * Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.UsageState&gt; * Nullable&lt;bool&gt; * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteAvailabilityState&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState&gt; * string * Nullable&lt;bool&gt; * Nullable&lt;DateTime&gt; * Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfig * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * string * Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentProfile * string * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;int&gt; * Microsoft.Azure.Management.AppService.Fluent.Models.CloningInfo * string * Nullable&lt;bool&gt; * string * Microsoft.Azure.Management.AppService.Fluent.Models.SlotSwapStatus -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner (location, id, name, type, tags, deletedTimestamp, state, hostNames, repositorySiteName, usageState, enabled, enabledHostNames, availabilityState, hostNameSslStates, serverFarmId, reserved, lastModifiedTimeUtc, siteConfig, trafficManagerHostNames, premiumAppDeployed, scmSiteAlsoStopped, targetSwapSlot, hostingEnvironmentProfile, microService, gatewaySiteName, clientAffinityEnabled, clientCertEnabled, hostNamesDisabled, outboundIpAddresses, containerSize, dailyMemoryTimeQuota, suspendedTill, maxNumberOfWorkers, cloningInfo, resourceGroup, isDefaultContainer, defaultHostName, slotSwapStatus)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="deletedTimestamp" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="state" Type="System.String" />
        <Parameter Name="hostNames" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="repositorySiteName" Type="System.String" />
        <Parameter Name="usageState" Type="System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.UsageState&gt;" />
        <Parameter Name="enabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="enabledHostNames" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="availabilityState" Type="System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteAvailabilityState&gt;" />
        <Parameter Name="hostNameSslStates" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState&gt;" />
        <Parameter Name="serverFarmId" Type="System.String" />
        <Parameter Name="reserved" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="lastModifiedTimeUtc" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="siteConfig" Type="Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfig" />
        <Parameter Name="trafficManagerHostNames" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="premiumAppDeployed" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="scmSiteAlsoStopped" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="targetSwapSlot" Type="System.String" />
        <Parameter Name="hostingEnvironmentProfile" Type="Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentProfile" />
        <Parameter Name="microService" Type="System.String" />
        <Parameter Name="gatewaySiteName" Type="System.String" />
        <Parameter Name="clientAffinityEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="clientCertEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="hostNamesDisabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="outboundIpAddresses" Type="System.String" />
        <Parameter Name="containerSize" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="dailyMemoryTimeQuota" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="suspendedTill" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="maxNumberOfWorkers" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cloningInfo" Type="Microsoft.Azure.Management.AppService.Fluent.Models.CloningInfo" />
        <Parameter Name="resourceGroup" Type="System.String" />
        <Parameter Name="isDefaultContainer" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="defaultHostName" Type="System.String" />
        <Parameter Name="slotSwapStatus" Type="Microsoft.Azure.Management.AppService.Fluent.Models.SlotSwapStatus" />
      </Parameters>
      <Docs>
        <param name="location">To be added.</param>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="type">To be added.</param>
        <param name="tags">To be added.</param>
        <param name="deletedTimestamp">アプリが削除されたときの UTC 時間です。</param>
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
        <param name="premiumAppDeployed">Premium アプリとしてアプリが展開されたかどうかを示します。</param>
        <param name="scmSiteAlsoStopped">&lt;コード&gt;true&lt;/code&gt; 、アプリが停止している、それ以外の場合は、SCM (KUDU) サイトを停止する&lt;コード&gt;false&lt;/code&gt;です。 既定値は&lt;コード&gt;false&lt;/code&gt;です。</param>
        <param name="targetSwapSlot">このアプリにスワップは展開スロットを指定します。 読み取り専用。</param>
        <param name="hostingEnvironmentProfile">アプリの使用を app Service 環境。</param>
        <param name="microService">マイクロ サービスなどのアプリ、ロジック。</param>
        <param name="gatewaySiteName">アプリに関連付けられたゲートウェイ アプリの名前です。</param>
        <param name="clientAffinityEnabled">&lt;コード&gt;true&lt;/code&gt;クライアントのアフィニティを有効にするには&lt;コード&gt;false&lt;/code&gt;セッション アフィニティ cookie は、同じインスタンスを同じセッションでクライアント要求をルーティングの送信を停止します。 既定値は&lt;コード&gt;true&lt;/code&gt;です。</param>
        <param name="clientCertEnabled">&lt;コード&gt;true&lt;/code&gt; (TLS の相互認証) です。 クライアント証明書認証を有効にするそれ以外の場合、&lt;コード&gt;false&lt;/code&gt;です。 既定値は&lt;コード&gt;false&lt;/code&gt;です。</param>
        <param name="hostNamesDisabled">&lt;コード&gt;true&lt;/code&gt; ; アプリのパブリック ホスト名を無効にするそれ以外の場合、&lt;コード&gt;false&lt;/code&gt;です。
            場合&lt;コード&gt;true&lt;/code&gt;アプリは API 管理プロセスを使用してアクセスできるのみです。</param>
        <param name="outboundIpAddresses">アプリで使用する (例: データベースへのアクセス) の発信接続用の IP アドレスの一覧です。
            読み取り専用。</param>
        <param name="containerSize">関数のコンテナーのサイズです。</param>
        <param name="dailyMemoryTimeQuota">最大日単位のメモリ時間クォータ (動的アプリのみに該当する場合) です。</param>
        <param name="suspendedTill">アプリがメモリにクォータを超えた場合に、まで中断します。</param>
        <param name="maxNumberOfWorkers">ワーカーの最大数。
            これは、関数のコンテナーにのみ適用されます。</param>
        <param name="cloningInfo">アプリの作成時に指定した場合、ソース アプリケーションから、アプリが複製されます。</param>
        <param name="resourceGroup">アプリが属するリソース グループの名前です。 読み取り専用。</param>
        <param name="isDefaultContainer">&lt;コード&gt;true&lt;/code&gt;場合は、アプリが既定のコンテナーです。 それ以外の場合、&lt;コード&gt;false&lt;/code&gt;です。</param>
        <param name="defaultHostName">アプリの既定のホスト名です。
            読み取り専用。</param>
        <param name="slotSwapStatus">最後の展開スロットのスワップ操作の状態です。</param>
        <summary>
            DeletedSiteInner クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvailabilityState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteAvailabilityState&gt; AvailabilityState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.SiteAvailabilityState&gt; AvailabilityState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.AvailabilityState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AvailabilityState As Nullable(Of SiteAvailabilityState)" />
      <MemberSignature Language="F#" Value="member this.AvailabilityState : Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteAvailabilityState&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.AvailabilityState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.availabilityState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteAvailabilityState&gt;</ReturnType>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.ClientAffinityEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientAffinityEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ClientAffinityEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.ClientAffinityEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.ClientCertEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientCertEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ClientCertEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.ClientCertEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.CloningInfo CloningInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.CloningInfo CloningInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.CloningInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property CloningInfo As CloningInfo" />
      <MemberSignature Language="F#" Value="member this.CloningInfo : Microsoft.Azure.Management.AppService.Fluent.Models.CloningInfo with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.CloningInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.cloningInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.CloningInfo</ReturnType>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.ContainerSize" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerSize As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ContainerSize : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.ContainerSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.DailyMemoryTimeQuota" />
      <MemberSignature Language="VB.NET" Value="Public Property DailyMemoryTimeQuota As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DailyMemoryTimeQuota : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.DailyMemoryTimeQuota" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.DefaultHostName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultHostName As String" />
      <MemberSignature Language="F#" Value="member this.DefaultHostName : string" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.DefaultHostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
    <Member MemberName="DeletedTimestamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; DeletedTimestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; DeletedTimestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.DeletedTimestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeletedTimestamp As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.DeletedTimestamp : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.DeletedTimestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.deletedTimestamp")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            アプリが削除されたときに、時刻 (utc) を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Enabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Enabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.Enabled" />
      <MemberSignature Language="VB.NET" Value="Public Property Enabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Enabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.Enabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.EnabledHostNames" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnabledHostNames As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.EnabledHostNames : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.EnabledHostNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
    <Member MemberName="GatewaySiteName">
      <MemberSignature Language="C#" Value="public string GatewaySiteName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GatewaySiteName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.GatewaySiteName" />
      <MemberSignature Language="VB.NET" Value="Public Property GatewaySiteName As String" />
      <MemberSignature Language="F#" Value="member this.GatewaySiteName : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.GatewaySiteName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.gatewaySiteName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアプリに関連付けられたゲートウェイ アプリの名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostingEnvironmentProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentProfile HostingEnvironmentProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentProfile HostingEnvironmentProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.HostingEnvironmentProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property HostingEnvironmentProfile As HostingEnvironmentProfile" />
      <MemberSignature Language="F#" Value="member this.HostingEnvironmentProfile : Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentProfile with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.HostingEnvironmentProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hostingEnvironmentProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentProfile</ReturnType>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.HostNames" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HostNames As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.HostNames : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.HostNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.HostNamesDisabled" />
      <MemberSignature Language="VB.NET" Value="Public Property HostNamesDisabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.HostNamesDisabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.HostNamesDisabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState&gt; HostNameSslStates { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState&gt; HostNameSslStates" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.HostNameSslStates" />
      <MemberSignature Language="VB.NET" Value="Public Property HostNameSslStates As IList(Of HostNameSslState)" />
      <MemberSignature Language="F#" Value="member this.HostNameSslStates : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.HostNameSslStates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hostNameSslStates")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定 SSL ホスト名の状態は、アプリのホスト名の SSL バインドの管理に使用されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDefaultContainer">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsDefaultContainer { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsDefaultContainer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.IsDefaultContainer" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsDefaultContainer As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsDefaultContainer : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.IsDefaultContainer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.LastModifiedTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModifiedTimeUtc As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastModifiedTimeUtc : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.LastModifiedTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.MaxNumberOfWorkers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxNumberOfWorkers As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxNumberOfWorkers : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.MaxNumberOfWorkers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
    <Member MemberName="MicroService">
      <MemberSignature Language="C#" Value="public string MicroService { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MicroService" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.MicroService" />
      <MemberSignature Language="VB.NET" Value="Public Property MicroService As String" />
      <MemberSignature Language="F#" Value="member this.MicroService : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.MicroService" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.microService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアプリ、ロジックのアプリと同様にマイクロ サービスを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutboundIpAddresses">
      <MemberSignature Language="C#" Value="public string OutboundIpAddresses { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OutboundIpAddresses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.OutboundIpAddresses" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OutboundIpAddresses As String" />
      <MemberSignature Language="F#" Value="member this.OutboundIpAddresses : string" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.OutboundIpAddresses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            アプリで使用する (例: データベースへのアクセス) の発信接続用の IP アドレスの一覧を取得します。 読み取り専用。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PremiumAppDeployed">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; PremiumAppDeployed { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; PremiumAppDeployed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.PremiumAppDeployed" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PremiumAppDeployed As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.PremiumAppDeployed : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.PremiumAppDeployed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.premiumAppDeployed")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得では、premium アプリとしてアプリが展開されたかどうかを示します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RepositorySiteName">
      <MemberSignature Language="C#" Value="public string RepositorySiteName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RepositorySiteName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.RepositorySiteName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RepositorySiteName As String" />
      <MemberSignature Language="F#" Value="member this.RepositorySiteName : string" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.RepositorySiteName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.Reserved" />
      <MemberSignature Language="VB.NET" Value="Public Property Reserved As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Reserved : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.Reserved" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.ResourceGroup" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceGroup As String" />
      <MemberSignature Language="F#" Value="member this.ResourceGroup : string" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.ResourceGroup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.ScmSiteAlsoStopped" />
      <MemberSignature Language="VB.NET" Value="Public Property ScmSiteAlsoStopped As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ScmSiteAlsoStopped : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.ScmSiteAlsoStopped" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.ServerFarmId" />
      <MemberSignature Language="VB.NET" Value="Public Property ServerFarmId As String" />
      <MemberSignature Language="F#" Value="member this.ServerFarmId : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.ServerFarmId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfig SiteConfig { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfig SiteConfig" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.SiteConfig" />
      <MemberSignature Language="VB.NET" Value="Public Property SiteConfig As SiteConfig" />
      <MemberSignature Language="F#" Value="member this.SiteConfig : Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfig with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.SiteConfig" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.siteConfig")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfig</ReturnType>
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
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.SlotSwapStatus SlotSwapStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.SlotSwapStatus SlotSwapStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.SlotSwapStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SlotSwapStatus As SlotSwapStatus" />
      <MemberSignature Language="F#" Value="member this.SlotSwapStatus : Microsoft.Azure.Management.AppService.Fluent.Models.SlotSwapStatus" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.SlotSwapStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.slotSwapStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.SlotSwapStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            最後の展開スロットのスワップ操作の状態を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public string State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As String" />
      <MemberSignature Language="F#" Value="member this.State : string" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.SuspendedTill" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SuspendedTill As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.SuspendedTill : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.SuspendedTill" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.TargetSwapSlot" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TargetSwapSlot As String" />
      <MemberSignature Language="F#" Value="member this.TargetSwapSlot : string" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.TargetSwapSlot" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.TrafficManagerHostNames" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TrafficManagerHostNames As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.TrafficManagerHostNames : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.TrafficManagerHostNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.UsageState&gt; UsageState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.UsageState&gt; UsageState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.UsageState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UsageState As Nullable(Of UsageState)" />
      <MemberSignature Language="F#" Value="member this.UsageState : Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.UsageState&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.UsageState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.usageState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.UsageState&gt;</ReturnType>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="deletedSiteInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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