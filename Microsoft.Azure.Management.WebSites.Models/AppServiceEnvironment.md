<Type Name="AppServiceEnvironment" FullName="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment">
  <TypeSignature Language="C#" Value="public class AppServiceEnvironment" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AppServiceEnvironment extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment" />
  <TypeSignature Language="VB.NET" Value="Public Class AppServiceEnvironment" />
  <TypeSignature Language="F#" Value="type AppServiceEnvironment = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            App Service 環境の説明です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AppServiceEnvironment ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            AppServiceEnvironment クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AppServiceEnvironment (string name, string location, Microsoft.Azure.Management.WebSites.Models.VirtualNetworkProfile virtualNetwork, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPool&gt; workerPools, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt; provisioningState = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentStatus&gt; status = null, string vnetName = null, string vnetResourceGroupName = null, string vnetSubnetName = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.InternalLoadBalancingMode&gt; internalLoadBalancingMode = null, string multiSize = null, Nullable&lt;int&gt; multiRoleCount = null, Nullable&lt;int&gt; ipsslAddressCount = null, string databaseEdition = null, string databaseServiceObjective = null, Nullable&lt;int&gt; upgradeDomains = null, string subscriptionId = null, string dnsSuffix = null, string lastAction = null, string lastActionResult = null, string allowedMultiSizes = null, string allowedWorkerSizes = null, Nullable&lt;int&gt; maximumNumberOfMachines = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VirtualIPMapping&gt; vipMappings = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.StampCapacity&gt; environmentCapacities = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.NetworkAccessControlEntry&gt; networkAccessControlList = null, Nullable&lt;bool&gt; environmentIsHealthy = null, string environmentStatus = null, string resourceGroup = null, Nullable&lt;int&gt; frontEndScaleFactor = null, Nullable&lt;int&gt; defaultFrontEndScaleFactor = null, string apiManagementAccountId = null, Nullable&lt;bool&gt; suspended = null, Nullable&lt;bool&gt; dynamicCacheEnabled = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.NameValuePair&gt; clusterSettings = null, System.Collections.Generic.IList&lt;string&gt; userWhitelistedIpRanges = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string location, class Microsoft.Azure.Management.WebSites.Models.VirtualNetworkProfile virtualNetwork, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.WorkerPool&gt; workerPools, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt; provisioningState, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentStatus&gt; status, string vnetName, string vnetResourceGroupName, string vnetSubnetName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.InternalLoadBalancingMode&gt; internalLoadBalancingMode, string multiSize, valuetype System.Nullable`1&lt;int32&gt; multiRoleCount, valuetype System.Nullable`1&lt;int32&gt; ipsslAddressCount, string databaseEdition, string databaseServiceObjective, valuetype System.Nullable`1&lt;int32&gt; upgradeDomains, string subscriptionId, string dnsSuffix, string lastAction, string lastActionResult, string allowedMultiSizes, string allowedWorkerSizes, valuetype System.Nullable`1&lt;int32&gt; maximumNumberOfMachines, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.VirtualIPMapping&gt; vipMappings, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.StampCapacity&gt; environmentCapacities, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.NetworkAccessControlEntry&gt; networkAccessControlList, valuetype System.Nullable`1&lt;bool&gt; environmentIsHealthy, string environmentStatus, string resourceGroup, valuetype System.Nullable`1&lt;int32&gt; frontEndScaleFactor, valuetype System.Nullable`1&lt;int32&gt; defaultFrontEndScaleFactor, string apiManagementAccountId, valuetype System.Nullable`1&lt;bool&gt; suspended, valuetype System.Nullable`1&lt;bool&gt; dynamicCacheEnabled, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.NameValuePair&gt; clusterSettings, class System.Collections.Generic.IList`1&lt;string&gt; userWhitelistedIpRanges) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.#ctor(System.String,System.String,Microsoft.Azure.Management.WebSites.Models.VirtualNetworkProfile,System.Collections.Generic.IList{Microsoft.Azure.Management.WebSites.Models.WorkerPool},System.Nullable{Microsoft.Azure.Management.WebSites.Models.ProvisioningState},System.Nullable{Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentStatus},System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.WebSites.Models.InternalLoadBalancingMode},System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.String,System.String,System.Nullable{System.Int32},System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.IList{Microsoft.Azure.Management.WebSites.Models.VirtualIPMapping},System.Collections.Generic.IList{Microsoft.Azure.Management.WebSites.Models.StampCapacity},System.Collections.Generic.IList{Microsoft.Azure.Management.WebSites.Models.NetworkAccessControlEntry},System.Nullable{System.Boolean},System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Collections.Generic.IList{Microsoft.Azure.Management.WebSites.Models.NameValuePair},System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, location As String, virtualNetwork As VirtualNetworkProfile, workerPools As IList(Of WorkerPool), Optional provisioningState As Nullable(Of ProvisioningState) = null, Optional status As Nullable(Of HostingEnvironmentStatus) = null, Optional vnetName As String = null, Optional vnetResourceGroupName As String = null, Optional vnetSubnetName As String = null, Optional internalLoadBalancingMode As Nullable(Of InternalLoadBalancingMode) = null, Optional multiSize As String = null, Optional multiRoleCount As Nullable(Of Integer) = null, Optional ipsslAddressCount As Nullable(Of Integer) = null, Optional databaseEdition As String = null, Optional databaseServiceObjective As String = null, Optional upgradeDomains As Nullable(Of Integer) = null, Optional subscriptionId As String = null, Optional dnsSuffix As String = null, Optional lastAction As String = null, Optional lastActionResult As String = null, Optional allowedMultiSizes As String = null, Optional allowedWorkerSizes As String = null, Optional maximumNumberOfMachines As Nullable(Of Integer) = null, Optional vipMappings As IList(Of VirtualIPMapping) = null, Optional environmentCapacities As IList(Of StampCapacity) = null, Optional networkAccessControlList As IList(Of NetworkAccessControlEntry) = null, Optional environmentIsHealthy As Nullable(Of Boolean) = null, Optional environmentStatus As String = null, Optional resourceGroup As String = null, Optional frontEndScaleFactor As Nullable(Of Integer) = null, Optional defaultFrontEndScaleFactor As Nullable(Of Integer) = null, Optional apiManagementAccountId As String = null, Optional suspended As Nullable(Of Boolean) = null, Optional dynamicCacheEnabled As Nullable(Of Boolean) = null, Optional clusterSettings As IList(Of NameValuePair) = null, Optional userWhitelistedIpRanges As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment : string * string * Microsoft.Azure.Management.WebSites.Models.VirtualNetworkProfile * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPool&gt; * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt; * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentStatus&gt; * string * string * string * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.InternalLoadBalancingMode&gt; * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * string * string * Nullable&lt;int&gt; * string * string * string * string * string * string * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VirtualIPMapping&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.StampCapacity&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.NetworkAccessControlEntry&gt; * Nullable&lt;bool&gt; * string * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.NameValuePair&gt; * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment" Usage="new Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment (name, location, virtualNetwork, workerPools, provisioningState, status, vnetName, vnetResourceGroupName, vnetSubnetName, internalLoadBalancingMode, multiSize, multiRoleCount, ipsslAddressCount, databaseEdition, databaseServiceObjective, upgradeDomains, subscriptionId, dnsSuffix, lastAction, lastActionResult, allowedMultiSizes, allowedWorkerSizes, maximumNumberOfMachines, vipMappings, environmentCapacities, networkAccessControlList, environmentIsHealthy, environmentStatus, resourceGroup, frontEndScaleFactor, defaultFrontEndScaleFactor, apiManagementAccountId, suspended, dynamicCacheEnabled, clusterSettings, userWhitelistedIpRanges)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="virtualNetwork" Type="Microsoft.Azure.Management.WebSites.Models.VirtualNetworkProfile" />
        <Parameter Name="workerPools" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPool&gt;" />
        <Parameter Name="provisioningState" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt;" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentStatus&gt;" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="vnetResourceGroupName" Type="System.String" />
        <Parameter Name="vnetSubnetName" Type="System.String" />
        <Parameter Name="internalLoadBalancingMode" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.InternalLoadBalancingMode&gt;" />
        <Parameter Name="multiSize" Type="System.String" />
        <Parameter Name="multiRoleCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="ipsslAddressCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="databaseEdition" Type="System.String" />
        <Parameter Name="databaseServiceObjective" Type="System.String" />
        <Parameter Name="upgradeDomains" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="subscriptionId" Type="System.String" />
        <Parameter Name="dnsSuffix" Type="System.String" />
        <Parameter Name="lastAction" Type="System.String" />
        <Parameter Name="lastActionResult" Type="System.String" />
        <Parameter Name="allowedMultiSizes" Type="System.String" />
        <Parameter Name="allowedWorkerSizes" Type="System.String" />
        <Parameter Name="maximumNumberOfMachines" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="vipMappings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VirtualIPMapping&gt;" />
        <Parameter Name="environmentCapacities" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.StampCapacity&gt;" />
        <Parameter Name="networkAccessControlList" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.NetworkAccessControlEntry&gt;" />
        <Parameter Name="environmentIsHealthy" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="environmentStatus" Type="System.String" />
        <Parameter Name="resourceGroup" Type="System.String" />
        <Parameter Name="frontEndScaleFactor" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="defaultFrontEndScaleFactor" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="apiManagementAccountId" Type="System.String" />
        <Parameter Name="suspended" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="dynamicCacheEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="clusterSettings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.NameValuePair&gt;" />
        <Parameter Name="userWhitelistedIpRanges" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="name">App Service 環境の名前です。</param>
        <param name="location">App Service 環境の場所。"West US"です。</param>
        <param name="virtualNetwork">仮想ネットワークの説明です。</param>
        <param name="workerPools">ワーカー サイズ Id、VM サイズ、および各プールでワーカーの数のワーカー プールの説明です。</param>
        <param name="provisioningState">App Service 環境の状態を準備しています。 使用可能な値が含まれます: 'は Succeeded'、'失敗'、'キャンセル'、'処理中'、'削除'</param>
        <param name="status">App Service 環境の現在の状態。
            使用可能な値が含まれます: 'を準備する'、'準備完了'、'スケーリング'、'削除'</param>
        <param name="vnetName">App Service 環境の仮想ネットワークの名前。</param>
        <param name="vnetResourceGroupName">仮想ネットワークのリソース グループです。</param>
        <param name="vnetSubnetName">仮想ネットワークのサブネットです。</param>
        <param name="internalLoadBalancingMode">App Service 環境の仮想ネットワークで内部的に機能するには、どのエンドポイントを指定します。 使用可能な値が含まれます 'None'、'Web'、'公開'。</param>
        <param name="multiSize">フロント エンドの VM サイズ例。「中」、"Large"です。</param>
        <param name="multiRoleCount">フロント エンド インスタンスの数。</param>
        <param name="ipsslAddressCount">App Service 環境の予約済みの IP SSL アドレスの数。</param>
        <param name="databaseEdition">App Service 環境のデータベースの例: メタデータのエディション「標準」です。</param>
        <param name="databaseServiceObjective">サービスのメタデータ データベースの目標を App Service 環境例。"S0"です。</param>
        <param name="upgradeDomains">App Service Environment のアップグレード ドメインの数。</param>
        <param name="subscriptionId">App Service 環境のサブスクリプション。</param>
        <param name="dnsSuffix">App Service 環境の DNS サフィックス。</param>
        <param name="lastAction">App Service 環境の最後の展開の操作です。</param>
        <param name="lastActionResult">App Service 環境の最後の展開の操作の結果です。</param>
        <param name="allowedMultiSizes">コンマの一覧には、フロント エンドは許可されている VM のサイズを記述する文字列が区切られます。</param>
        <param name="allowedWorkerSizes">コンマの一覧には、ワーカーは許可されている VM のサイズを記述する文字列が区切られます。</param>
        <param name="maximumNumberOfMachines">App Service Environment で Vm の最大数。</param>
        <param name="vipMappings">IP SSL のマッピングを App Service 環境の説明です。</param>
        <param name="environmentCapacities">現在の合計、使用、および使用可能なワーカーの容量。</param>
        <param name="networkAccessControlList">App Service 環境へのトラフィックを制御するためのアクセス制御リストです。</param>
        <param name="environmentIsHealthy">App Service 環境が正常かどうかを示す true または false です。</param>
        <param name="environmentStatus">App Service 環境の最後のチェックの結果を含むに関する詳細なメッセージです。</param>
        <param name="resourceGroup">App Service 環境のリソース グループです。</param>
        <param name="frontEndScaleFactor">フロント エンドのスケール ファクター。</param>
        <param name="defaultFrontEndScaleFactor">フロント エンドに対して既定のスケール ファクター。</param>
        <param name="apiManagementAccountId">API 管理アカウントが App Service 環境に関連付けられています。</param>
        <param name="suspended">&lt;コード&gt;true&lt;/code&gt; App Service 環境が中断されている、それ以外の場合は&lt;コード&gt;false&lt;/code&gt;です。 環境を中断することができますなどと、管理エンドポイントは現在利用できません (最も可能性の高い NSG には、着信トラフィックがブロックされているため)。</param>
        <param name="dynamicCacheEnabled">App Service 環境が中断されているかどうかを示す true または false です。 環境を指定できます中断などと、管理エンドポイントは現在利用できません (最も可能性の高い NSG には、着信トラフィックがブロックされているため)。</param>
        <param name="clusterSettings">App Service 環境の動作を変更するためのカスタム設定。</param>
        <param name="userWhitelistedIpRanges">ユーザーを ASE db のホワイト リスト ip の範囲を追加します。</param>
        <summary>
            AppServiceEnvironment クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowedMultiSizes">
      <MemberSignature Language="C#" Value="public string AllowedMultiSizes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AllowedMultiSizes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.AllowedMultiSizes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AllowedMultiSizes As String" />
      <MemberSignature Language="F#" Value="member this.AllowedMultiSizes : string" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.AllowedMultiSizes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="allowedMultiSizes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            コンマ区切りの文字列の一覧を取得フロント エンドの VM サイズが許可されている記述します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowedWorkerSizes">
      <MemberSignature Language="C#" Value="public string AllowedWorkerSizes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AllowedWorkerSizes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.AllowedWorkerSizes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AllowedWorkerSizes As String" />
      <MemberSignature Language="F#" Value="member this.AllowedWorkerSizes : string" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.AllowedWorkerSizes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="allowedWorkerSizes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得コンマ区切りの文字列の一覧の記述作業者の VM サイズが許可されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiManagementAccountId">
      <MemberSignature Language="C#" Value="public string ApiManagementAccountId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApiManagementAccountId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.ApiManagementAccountId" />
      <MemberSignature Language="VB.NET" Value="Public Property ApiManagementAccountId As String" />
      <MemberSignature Language="F#" Value="member this.ApiManagementAccountId : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.ApiManagementAccountId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="apiManagementAccountId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または App Service 環境に関連付けられている API 管理アカウントを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.NameValuePair&gt; ClusterSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.NameValuePair&gt; ClusterSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.ClusterSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property ClusterSettings As IList(Of NameValuePair)" />
      <MemberSignature Language="F#" Value="member this.ClusterSettings : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.NameValuePair&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.ClusterSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="clusterSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.NameValuePair&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または App Service 環境の動作を変更するためのカスタム設定を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseEdition">
      <MemberSignature Language="C#" Value="public string DatabaseEdition { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DatabaseEdition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.DatabaseEdition" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseEdition As String" />
      <MemberSignature Language="F#" Value="member this.DatabaseEdition : string" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.DatabaseEdition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="databaseEdition")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            例: App Service 環境のメタデータ データベースのエディションを取得します。「標準」です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseServiceObjective">
      <MemberSignature Language="C#" Value="public string DatabaseServiceObjective { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DatabaseServiceObjective" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.DatabaseServiceObjective" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseServiceObjective As String" />
      <MemberSignature Language="F#" Value="member this.DatabaseServiceObjective : string" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.DatabaseServiceObjective" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="databaseServiceObjective")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            例: メタデータ データベースのサービス目標を App Service 環境の取得します。"S0"です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultFrontEndScaleFactor">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DefaultFrontEndScaleFactor { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DefaultFrontEndScaleFactor" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.DefaultFrontEndScaleFactor" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultFrontEndScaleFactor As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DefaultFrontEndScaleFactor : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.DefaultFrontEndScaleFactor" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="defaultFrontEndScaleFactor")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            フロント エンドに対して既定のスケール ファクターを取得。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DnsSuffix">
      <MemberSignature Language="C#" Value="public string DnsSuffix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DnsSuffix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.DnsSuffix" />
      <MemberSignature Language="VB.NET" Value="Public Property DnsSuffix As String" />
      <MemberSignature Language="F#" Value="member this.DnsSuffix : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.DnsSuffix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dnsSuffix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または App Service 環境の DNS サフィックスを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DynamicCacheEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; DynamicCacheEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; DynamicCacheEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.DynamicCacheEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property DynamicCacheEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.DynamicCacheEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.DynamicCacheEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dynamicCacheEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または App Service 環境が中断されているかどうかを示す true または false を設定します。 環境を指定できます中断などと、管理エンドポイントは現在利用できません (最も可能性の高い NSG には、着信トラフィックがブロックされているため)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnvironmentCapacities">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.StampCapacity&gt; EnvironmentCapacities { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.StampCapacity&gt; EnvironmentCapacities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.EnvironmentCapacities" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnvironmentCapacities As IList(Of StampCapacity)" />
      <MemberSignature Language="F#" Value="member this.EnvironmentCapacities : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.StampCapacity&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.EnvironmentCapacities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="environmentCapacities")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.StampCapacity&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            現在の合計、使用、および使用可能なワーカーの容量を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnvironmentIsHealthy">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnvironmentIsHealthy { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnvironmentIsHealthy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.EnvironmentIsHealthy" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnvironmentIsHealthy As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnvironmentIsHealthy : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.EnvironmentIsHealthy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="environmentIsHealthy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            App Service 環境が正常かどうかを示す true または false を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnvironmentStatus">
      <MemberSignature Language="C#" Value="public string EnvironmentStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EnvironmentStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.EnvironmentStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnvironmentStatus As String" />
      <MemberSignature Language="F#" Value="member this.EnvironmentStatus : string" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.EnvironmentStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="environmentStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得についての詳細メッセージの App Service 環境の最後のチェックの結果。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FrontEndScaleFactor">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; FrontEndScaleFactor { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; FrontEndScaleFactor" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.FrontEndScaleFactor" />
      <MemberSignature Language="VB.NET" Value="Public Property FrontEndScaleFactor As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.FrontEndScaleFactor : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.FrontEndScaleFactor" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="frontEndScaleFactor")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはフロント エンドのスケール ファクターを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InternalLoadBalancingMode">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.InternalLoadBalancingMode&gt; InternalLoadBalancingMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.InternalLoadBalancingMode&gt; InternalLoadBalancingMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.InternalLoadBalancingMode" />
      <MemberSignature Language="VB.NET" Value="Public Property InternalLoadBalancingMode As Nullable(Of InternalLoadBalancingMode)" />
      <MemberSignature Language="F#" Value="member this.InternalLoadBalancingMode : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.InternalLoadBalancingMode&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.InternalLoadBalancingMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="internalLoadBalancingMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.InternalLoadBalancingMode&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、App Service 環境の仮想ネットワークで内部的に機能するには、どのエンドポイントを指定します。 使用可能な値が含まれます 'None'、'Web'、'公開'。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IpsslAddressCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; IpsslAddressCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; IpsslAddressCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.IpsslAddressCount" />
      <MemberSignature Language="VB.NET" Value="Public Property IpsslAddressCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.IpsslAddressCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.IpsslAddressCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ipsslAddressCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または予約済みの App Service 環境の IP SSL アドレスの数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastAction">
      <MemberSignature Language="C#" Value="public string LastAction { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LastAction" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.LastAction" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastAction As String" />
      <MemberSignature Language="F#" Value="member this.LastAction : string" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.LastAction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastAction")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得の最後の App Service 環境の展開操作します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastActionResult">
      <MemberSignature Language="C#" Value="public string LastActionResult { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LastActionResult" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.LastActionResult" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastActionResult As String" />
      <MemberSignature Language="F#" Value="member this.LastActionResult : string" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.LastActionResult" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastActionResult")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            App Service 環境の最後の展開の操作の結果を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.Location" />
      <MemberSignature Language="VB.NET" Value="Public Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="location")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはなどの App Service 環境の場所を設定"West US"です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaximumNumberOfMachines">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaximumNumberOfMachines { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaximumNumberOfMachines" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.MaximumNumberOfMachines" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaximumNumberOfMachines As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaximumNumberOfMachines : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.MaximumNumberOfMachines" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maximumNumberOfMachines")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            App Service Environment で Vm の最大数を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MultiRoleCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MultiRoleCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MultiRoleCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.MultiRoleCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MultiRoleCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MultiRoleCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.MultiRoleCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="multiRoleCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはフロント エンド インスタンスの数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MultiSize">
      <MemberSignature Language="C#" Value="public string MultiSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MultiSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.MultiSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MultiSize As String" />
      <MemberSignature Language="F#" Value="member this.MultiSize : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.MultiSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="multiSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            例: フロント エンドの VM サイズの設定を取得または「中」、"Large"です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または App Service 環境の名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkAccessControlList">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.NetworkAccessControlEntry&gt; NetworkAccessControlList { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.NetworkAccessControlEntry&gt; NetworkAccessControlList" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.NetworkAccessControlList" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkAccessControlList As IList(Of NetworkAccessControlEntry)" />
      <MemberSignature Language="F#" Value="member this.NetworkAccessControlList : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.NetworkAccessControlEntry&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.NetworkAccessControlList" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="networkAccessControlList")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.NetworkAccessControlEntry&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または App Service 環境へのトラフィックを制御するためのアクセス制御リストを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt; ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt; ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As Nullable(Of ProvisioningState)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            App Service 環境の状態のプロビジョニングを取得します。 使用可能な値が含まれます: 'は Succeeded'、'失敗'、'キャンセル'、'処理中'、'削除'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceGroup">
      <MemberSignature Language="C#" Value="public string ResourceGroup { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceGroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.ResourceGroup" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceGroup As String" />
      <MemberSignature Language="F#" Value="member this.ResourceGroup : string" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.ResourceGroup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceGroup")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            App Service 環境のリソース グループを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentStatus&gt; Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentStatus&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As Nullable(Of HostingEnvironmentStatus)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentStatus&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            App Service 環境の現在の状態を取得します。 使用可能な値が含まれます: 'を準備する'、'準備完了'、'スケーリング'、'削除'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.SubscriptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="subscriptionId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            App Service 環境のサブスクリプションを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Suspended">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Suspended { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Suspended" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.Suspended" />
      <MemberSignature Language="VB.NET" Value="Public Property Suspended As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Suspended : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.Suspended" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="suspended")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定&amp;lt; コード&amp;gt 以外の場合は true&amp;lt;/code&amp;gt; App Service 環境が中断されている、それ以外の場合は&amp;lt; コード&amp;gt; false&amp;lt;/code&amp;。gt;。 環境を中断することができますなどと、管理エンドポイントは現在利用できません (最も可能性の高い NSG には、着信トラフィックがブロックされているため)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeDomains">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; UpgradeDomains { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; UpgradeDomains" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.UpgradeDomains" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeDomains As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.UpgradeDomains : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.UpgradeDomains" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="upgradeDomains")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            App Service Environment のアップグレード ドメインの数を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserWhitelistedIpRanges">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; UserWhitelistedIpRanges { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; UserWhitelistedIpRanges" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.UserWhitelistedIpRanges" />
      <MemberSignature Language="VB.NET" Value="Public Property UserWhitelistedIpRanges As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.UserWhitelistedIpRanges : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.UserWhitelistedIpRanges" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="userWhitelistedIpRanges")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または追加されたユーザーの設定を ASE db のホワイト リスト ip の範囲
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="appServiceEnvironment.Validate " />
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
    <Member MemberName="VipMappings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VirtualIPMapping&gt; VipMappings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.VirtualIPMapping&gt; VipMappings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.VipMappings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VipMappings As IList(Of VirtualIPMapping)" />
      <MemberSignature Language="F#" Value="member this.VipMappings : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VirtualIPMapping&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.VipMappings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="vipMappings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VirtualIPMapping&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            App Service 環境のマッピングの IP SSL の説明を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualNetwork">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.VirtualNetworkProfile VirtualNetwork { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.VirtualNetworkProfile VirtualNetwork" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.VirtualNetwork" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualNetwork As VirtualNetworkProfile" />
      <MemberSignature Language="F#" Value="member this.VirtualNetwork : Microsoft.Azure.Management.WebSites.Models.VirtualNetworkProfile with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.VirtualNetwork" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="virtualNetwork")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.VirtualNetworkProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または仮想ネットワークの説明を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VnetName">
      <MemberSignature Language="C#" Value="public string VnetName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VnetName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.VnetName" />
      <MemberSignature Language="VB.NET" Value="Public Property VnetName As String" />
      <MemberSignature Language="F#" Value="member this.VnetName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.VnetName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="vnetName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または App Service 環境の仮想ネットワークの名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VnetResourceGroupName">
      <MemberSignature Language="C#" Value="public string VnetResourceGroupName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VnetResourceGroupName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.VnetResourceGroupName" />
      <MemberSignature Language="VB.NET" Value="Public Property VnetResourceGroupName As String" />
      <MemberSignature Language="F#" Value="member this.VnetResourceGroupName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.VnetResourceGroupName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="vnetResourceGroupName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または仮想ネットワークのリソース グループを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VnetSubnetName">
      <MemberSignature Language="C#" Value="public string VnetSubnetName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VnetSubnetName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.VnetSubnetName" />
      <MemberSignature Language="VB.NET" Value="Public Property VnetSubnetName As String" />
      <MemberSignature Language="F#" Value="member this.VnetSubnetName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.VnetSubnetName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="vnetSubnetName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または仮想ネットワークのサブネットを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WorkerPools">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPool&gt; WorkerPools { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.WorkerPool&gt; WorkerPools" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.WorkerPools" />
      <MemberSignature Language="VB.NET" Value="Public Property WorkerPools As IList(Of WorkerPool)" />
      <MemberSignature Language="F#" Value="member this.WorkerPools : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironment.WorkerPools" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="workerPools")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPool&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または各プールでワーカー サイズ Id のワーカー プールの説明、VM サイズ、およびワーカーの数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>