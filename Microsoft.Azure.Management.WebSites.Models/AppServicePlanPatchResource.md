<Type Name="AppServicePlanPatchResource" FullName="Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource">
  <TypeSignature Language="C#" Value="public class AppServicePlanPatchResource : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AppServicePlanPatchResource extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource" />
  <TypeSignature Language="VB.NET" Value="Public Class AppServicePlanPatchResource&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type AppServicePlanPatchResource = class&#xA;    inherit ProxyOnlyResource" />
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
            App service プランの ARM リソースです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AppServicePlanPatchResource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            AppServicePlanPatchResource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AppServicePlanPatchResource (string id = null, string name = null, string kind = null, string type = null, string appServicePlanPatchResourceName = null, string workerTierName = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.StatusOptions&gt; status = null, string subscription = null, string adminSiteName = null, Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile hostingEnvironmentProfile = null, Nullable&lt;int&gt; maximumNumberOfWorkers = null, string geoRegion = null, Nullable&lt;bool&gt; perSiteScaling = null, Nullable&lt;int&gt; numberOfSites = null, Nullable&lt;bool&gt; isSpot = null, Nullable&lt;DateTime&gt; spotExpirationTime = null, string resourceGroup = null, Nullable&lt;bool&gt; reserved = null, Nullable&lt;int&gt; targetWorkerCount = null, Nullable&lt;int&gt; targetWorkerSizeId = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt; provisioningState = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string appServicePlanPatchResourceName, string workerTierName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.StatusOptions&gt; status, string subscription, string adminSiteName, class Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile hostingEnvironmentProfile, valuetype System.Nullable`1&lt;int32&gt; maximumNumberOfWorkers, string geoRegion, valuetype System.Nullable`1&lt;bool&gt; perSiteScaling, valuetype System.Nullable`1&lt;int32&gt; numberOfSites, valuetype System.Nullable`1&lt;bool&gt; isSpot, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; spotExpirationTime, string resourceGroup, valuetype System.Nullable`1&lt;bool&gt; reserved, valuetype System.Nullable`1&lt;int32&gt; targetWorkerCount, valuetype System.Nullable`1&lt;int32&gt; targetWorkerSizeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt; provisioningState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.WebSites.Models.StatusOptions},System.String,System.String,Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile,System.Nullable{System.Int32},System.String,System.Nullable{System.Boolean},System.Nullable{System.Int32},System.Nullable{System.Boolean},System.Nullable{System.DateTime},System.String,System.Nullable{System.Boolean},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{Microsoft.Azure.Management.WebSites.Models.ProvisioningState})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource : string * string * string * string * string * string * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.StatusOptions&gt; * string * string * Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile * Nullable&lt;int&gt; * string * Nullable&lt;bool&gt; * Nullable&lt;int&gt; * Nullable&lt;bool&gt; * Nullable&lt;DateTime&gt; * string * Nullable&lt;bool&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource" Usage="new Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource (id, name, kind, type, appServicePlanPatchResourceName, workerTierName, status, subscription, adminSiteName, hostingEnvironmentProfile, maximumNumberOfWorkers, geoRegion, perSiteScaling, numberOfSites, isSpot, spotExpirationTime, resourceGroup, reserved, targetWorkerCount, targetWorkerSizeId, provisioningState)" />
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
        <Parameter Name="appServicePlanPatchResourceName" Type="System.String" />
        <Parameter Name="workerTierName" Type="System.String" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.StatusOptions&gt;" />
        <Parameter Name="subscription" Type="System.String" />
        <Parameter Name="adminSiteName" Type="System.String" />
        <Parameter Name="hostingEnvironmentProfile" Type="Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile" />
        <Parameter Name="maximumNumberOfWorkers" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="geoRegion" Type="System.String" />
        <Parameter Name="perSiteScaling" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="numberOfSites" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="isSpot" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="spotExpirationTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="resourceGroup" Type="System.String" />
        <Parameter Name="reserved" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="targetWorkerCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="targetWorkerSizeId" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="provisioningState" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt;" />
      </Parameters>
      <Docs>
        <param name="id">リソース id です。</param>
        <param name="name">リソースの名前です。</param>
        <param name="kind">リソースの種類。</param>
        <param name="type">リソースの種類。</param>
        <param name="appServicePlanPatchResourceName">App Service プランの名前です。</param>
        <param name="workerTierName">App Service プランに割り当てられている対象となるワーカー層です。</param>
        <param name="status">App Service プランの状態です。 使用可能な値が含まれます: '準備完了'、'保留中'、'作成'</param>
        <param name="subscription">App Service プランのサブスクリプション。</param>
        <param name="adminSiteName">App Service プランの管理のサイトです。</param>
        <param name="hostingEnvironmentProfile">App Service プランに使用する App Service 環境を指定します。</param>
        <param name="maximumNumberOfWorkers">この App Service プランに割り当てることのできるインスタンスの最大数。</param>
        <param name="geoRegion">App Service プランの地理的な場所です。</param>
        <param name="perSiteScaling">場合&lt;コード&gt;true&lt;/code&gt;アプリがこの App Service プランに割り当てられている個別に拡張することができます。
            場合&lt;コード&gt;false&lt;/code&gt;プランのすべてのインスタンスにこの App Service プランに割り当てられているアプリをスケールします。</param>
        <param name="numberOfSites">この App Service プランに割り当てられているアプリの数です。</param>
        <param name="isSpot">場合&lt;コード&gt;true&lt;/code&gt;、スポット インスタンスこの App Service プランを所有します。</param>
        <param name="spotExpirationTime">サーバー ファームの有効期限が切れる時刻。 スポット サーバー ファームの場合にのみ有効です。</param>
        <param name="resourceGroup">App Service プランのリソース グループです。</param>
        <param name="reserved">予約済み。</param>
        <param name="targetWorkerCount">ワーカーの数をスケーリングします。</param>
        <param name="targetWorkerSizeId">スケーリングのワーカー サイズ id。</param>
        <param name="provisioningState">App Service 環境の状態を準備しています。 使用可能な値が含まれます: 'は Succeeded'、'失敗'、'キャンセル'、'処理中'、'削除'</param>
        <summary>
            AppServicePlanPatchResource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdminSiteName">
      <MemberSignature Language="C#" Value="public string AdminSiteName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AdminSiteName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.AdminSiteName" />
      <MemberSignature Language="VB.NET" Value="Public Property AdminSiteName As String" />
      <MemberSignature Language="F#" Value="member this.AdminSiteName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.AdminSiteName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.adminSiteName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアプリ サービス プランの管理サイトを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppServicePlanPatchResourceName">
      <MemberSignature Language="C#" Value="public string AppServicePlanPatchResourceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AppServicePlanPatchResourceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.AppServicePlanPatchResourceName" />
      <MemberSignature Language="VB.NET" Value="Public Property AppServicePlanPatchResourceName As String" />
      <MemberSignature Language="F#" Value="member this.AppServicePlanPatchResourceName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.AppServicePlanPatchResourceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または App Service プランの名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GeoRegion">
      <MemberSignature Language="C#" Value="public string GeoRegion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GeoRegion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.GeoRegion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property GeoRegion As String" />
      <MemberSignature Language="F#" Value="member this.GeoRegion : string" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.GeoRegion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.geoRegion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            App Service プランの地理的な場所を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostingEnvironmentProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile HostingEnvironmentProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile HostingEnvironmentProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.HostingEnvironmentProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property HostingEnvironmentProfile As HostingEnvironmentProfile" />
      <MemberSignature Language="F#" Value="member this.HostingEnvironmentProfile : Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.HostingEnvironmentProfile" />
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
            取得または、App Service 環境の App Service プランに使用するための仕様を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsSpot">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsSpot { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsSpot" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.IsSpot" />
      <MemberSignature Language="VB.NET" Value="Public Property IsSpot As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsSpot : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.IsSpot" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.isSpot")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            場合取得または設定&amp;lt; コード&amp;gt 以外の場合は true。&amp;lt;/code&amp;gt;、スポット インスタンスこの App Service プランを所有しています。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaximumNumberOfWorkers">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaximumNumberOfWorkers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaximumNumberOfWorkers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.MaximumNumberOfWorkers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaximumNumberOfWorkers As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaximumNumberOfWorkers : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.MaximumNumberOfWorkers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maximumNumberOfWorkers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            この App Service プランに割り当てることのできるインスタンスの最大数を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumberOfSites">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; NumberOfSites { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; NumberOfSites" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.NumberOfSites" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NumberOfSites As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.NumberOfSites : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.NumberOfSites" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.numberOfSites")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            この App Service プランに割り当てられているアプリの数を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PerSiteScaling">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; PerSiteScaling { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; PerSiteScaling" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.PerSiteScaling" />
      <MemberSignature Language="VB.NET" Value="Public Property PerSiteScaling As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.PerSiteScaling : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.PerSiteScaling" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.perSiteScaling")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            場合取得または設定&amp;lt; コード&amp;gt; true&amp;lt;/code&amp;gt 以外の場合は、この App Service プランに割り当てられているアプリ個別に拡張することができます。
            場合&amp;lt; コード&amp;gt 以外の場合は false&amp;lt;/code&amp;gt;、プランのすべてのインスタンスにこの App Service プランに割り当てられているアプリをスケールします。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt; ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt; ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As Nullable(Of ProvisioningState)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
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
    <Member MemberName="Reserved">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Reserved { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Reserved" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.Reserved" />
      <MemberSignature Language="VB.NET" Value="Public Property Reserved As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Reserved : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.Reserved" />
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
            取得または予約済みに設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceGroup">
      <MemberSignature Language="C#" Value="public string ResourceGroup { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceGroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.ResourceGroup" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceGroup As String" />
      <MemberSignature Language="F#" Value="member this.ResourceGroup : string" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.ResourceGroup" />
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
            App Service プランのリソース グループを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SpotExpirationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; SpotExpirationTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; SpotExpirationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.SpotExpirationTime" />
      <MemberSignature Language="VB.NET" Value="Public Property SpotExpirationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.SpotExpirationTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.SpotExpirationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.spotExpirationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはサーバー ファームの有効期限が切れる時刻を設定します。 スポット サーバー ファームの場合にのみ有効です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.StatusOptions&gt; Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.StatusOptions&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As Nullable(Of StatusOptions)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.StatusOptions&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.StatusOptions&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            アプリ サービス プランの状態を取得します。 使用可能な値が含まれます: '準備完了'、'保留中'、'作成'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Subscription">
      <MemberSignature Language="C#" Value="public string Subscription { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Subscription" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.Subscription" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Subscription As String" />
      <MemberSignature Language="F#" Value="member this.Subscription : string" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.Subscription" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.subscription")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            アプリ サービス プランのサブスクリプションを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetWorkerCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TargetWorkerCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TargetWorkerCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.TargetWorkerCount" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetWorkerCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TargetWorkerCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.TargetWorkerCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.targetWorkerCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定のワーカーの数をスケーリングします。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetWorkerSizeId">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TargetWorkerSizeId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TargetWorkerSizeId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.TargetWorkerSizeId" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetWorkerSizeId As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TargetWorkerSizeId : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.TargetWorkerSizeId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.targetWorkerSizeId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定スケーリング ワーカー サイズ id。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WorkerTierName">
      <MemberSignature Language="C#" Value="public string WorkerTierName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WorkerTierName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.WorkerTierName" />
      <MemberSignature Language="VB.NET" Value="Public Property WorkerTierName As String" />
      <MemberSignature Language="F#" Value="member this.WorkerTierName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.WorkerTierName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.workerTierName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または App Service プランに割り当てられている対象となるワーカー層を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>