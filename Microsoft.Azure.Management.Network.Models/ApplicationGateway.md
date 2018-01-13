<Type Name="ApplicationGateway" FullName="Microsoft.Azure.Management.Network.Models.ApplicationGateway">
  <TypeSignature Language="C#" Value="public class ApplicationGateway : Microsoft.Azure.Management.Network.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationGateway extends Microsoft.Azure.Management.Network.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.ApplicationGateway" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationGateway&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type ApplicationGateway = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Network.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            アプリケーション ゲートウェイ リソース
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGateway ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGateway.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ApplicationGateway クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGateway (string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.Network.Models.ApplicationGatewaySku sku = null, Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPolicy sslPolicy = null, string operationalState = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayIPConfiguration&gt; gatewayIPConfigurations = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayAuthenticationCertificate&gt; authenticationCertificates = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslCertificate&gt; sslCertificates = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayFrontendIPConfiguration&gt; frontendIPConfigurations = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayFrontendPort&gt; frontendPorts = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe&gt; probes = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendAddressPool&gt; backendAddressPools = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings&gt; backendHttpSettingsCollection = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayHttpListener&gt; httpListeners = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayUrlPathMap&gt; urlPathMaps = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayRequestRoutingRule&gt; requestRoutingRules = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration&gt; redirectConfigurations = null, Microsoft.Azure.Management.Network.Models.ApplicationGatewayWebApplicationFirewallConfiguration webApplicationFirewallConfiguration = null, Nullable&lt;bool&gt; enableHttp2 = null, string resourceGuid = null, string provisioningState = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.Network.Models.ApplicationGatewaySku sku, class Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPolicy sslPolicy, string operationalState, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewayIPConfiguration&gt; gatewayIPConfigurations, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewayAuthenticationCertificate&gt; authenticationCertificates, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslCertificate&gt; sslCertificates, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewayFrontendIPConfiguration&gt; frontendIPConfigurations, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewayFrontendPort&gt; frontendPorts, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe&gt; probes, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendAddressPool&gt; backendAddressPools, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings&gt; backendHttpSettingsCollection, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewayHttpListener&gt; httpListeners, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewayUrlPathMap&gt; urlPathMaps, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewayRequestRoutingRule&gt; requestRoutingRules, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration&gt; redirectConfigurations, class Microsoft.Azure.Management.Network.Models.ApplicationGatewayWebApplicationFirewallConfiguration webApplicationFirewallConfiguration, valuetype System.Nullable`1&lt;bool&gt; enableHttp2, string resourceGuid, string provisioningState, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGateway.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.Network.Models.ApplicationGatewaySku,Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPolicy,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.ApplicationGatewayIPConfiguration},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.ApplicationGatewayAuthenticationCertificate},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslCertificate},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.ApplicationGatewayFrontendIPConfiguration},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.ApplicationGatewayFrontendPort},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendAddressPool},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.ApplicationGatewayHttpListener},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.ApplicationGatewayUrlPathMap},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.ApplicationGatewayRequestRoutingRule},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration},Microsoft.Azure.Management.Network.Models.ApplicationGatewayWebApplicationFirewallConfiguration,System.Nullable{System.Boolean},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional location As String = null, Optional tags As IDictionary(Of String, String) = null, Optional sku As ApplicationGatewaySku = null, Optional sslPolicy As ApplicationGatewaySslPolicy = null, Optional operationalState As String = null, Optional gatewayIPConfigurations As IList(Of ApplicationGatewayIPConfiguration) = null, Optional authenticationCertificates As IList(Of ApplicationGatewayAuthenticationCertificate) = null, Optional sslCertificates As IList(Of ApplicationGatewaySslCertificate) = null, Optional frontendIPConfigurations As IList(Of ApplicationGatewayFrontendIPConfiguration) = null, Optional frontendPorts As IList(Of ApplicationGatewayFrontendPort) = null, Optional probes As IList(Of ApplicationGatewayProbe) = null, Optional backendAddressPools As IList(Of ApplicationGatewayBackendAddressPool) = null, Optional backendHttpSettingsCollection As IList(Of ApplicationGatewayBackendHttpSettings) = null, Optional httpListeners As IList(Of ApplicationGatewayHttpListener) = null, Optional urlPathMaps As IList(Of ApplicationGatewayUrlPathMap) = null, Optional requestRoutingRules As IList(Of ApplicationGatewayRequestRoutingRule) = null, Optional redirectConfigurations As IList(Of ApplicationGatewayRedirectConfiguration) = null, Optional webApplicationFirewallConfiguration As ApplicationGatewayWebApplicationFirewallConfiguration = null, Optional enableHttp2 As Nullable(Of Boolean) = null, Optional resourceGuid As String = null, Optional provisioningState As String = null, Optional etag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.ApplicationGateway : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.Network.Models.ApplicationGatewaySku * Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPolicy * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayIPConfiguration&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayAuthenticationCertificate&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslCertificate&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayFrontendIPConfiguration&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayFrontendPort&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendAddressPool&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayHttpListener&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayUrlPathMap&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayRequestRoutingRule&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration&gt; * Microsoft.Azure.Management.Network.Models.ApplicationGatewayWebApplicationFirewallConfiguration * Nullable&lt;bool&gt; * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.ApplicationGateway" Usage="new Microsoft.Azure.Management.Network.Models.ApplicationGateway (id, name, type, location, tags, sku, sslPolicy, operationalState, gatewayIPConfigurations, authenticationCertificates, sslCertificates, frontendIPConfigurations, frontendPorts, probes, backendAddressPools, backendHttpSettingsCollection, httpListeners, urlPathMaps, requestRoutingRules, redirectConfigurations, webApplicationFirewallConfiguration, enableHttp2, resourceGuid, provisioningState, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.Network.Models.ApplicationGatewaySku" />
        <Parameter Name="sslPolicy" Type="Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPolicy" />
        <Parameter Name="operationalState" Type="System.String" />
        <Parameter Name="gatewayIPConfigurations" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayIPConfiguration&gt;" />
        <Parameter Name="authenticationCertificates" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayAuthenticationCertificate&gt;" />
        <Parameter Name="sslCertificates" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslCertificate&gt;" />
        <Parameter Name="frontendIPConfigurations" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayFrontendIPConfiguration&gt;" />
        <Parameter Name="frontendPorts" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayFrontendPort&gt;" />
        <Parameter Name="probes" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe&gt;" />
        <Parameter Name="backendAddressPools" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendAddressPool&gt;" />
        <Parameter Name="backendHttpSettingsCollection" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings&gt;" />
        <Parameter Name="httpListeners" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayHttpListener&gt;" />
        <Parameter Name="urlPathMaps" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayUrlPathMap&gt;" />
        <Parameter Name="requestRoutingRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayRequestRoutingRule&gt;" />
        <Parameter Name="redirectConfigurations" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration&gt;" />
        <Parameter Name="webApplicationFirewallConfiguration" Type="Microsoft.Azure.Management.Network.Models.ApplicationGatewayWebApplicationFirewallConfiguration" />
        <Parameter Name="enableHttp2" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="resourceGuid" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">リソースの ID</param>
        <param name="name">リソース名。</param>
        <param name="type">リソースの種類。</param>
        <param name="location">リソースの場所。</param>
        <param name="tags">リソース タグ。</param>
        <param name="sku">アプリケーション ゲートウェイ リソースの SKU。</param>
        <param name="sslPolicy">アプリケーション ゲートウェイ リソースの SSL ポリシーです。</param>
        <param name="operationalState">アプリケーション ゲートウェイ リソースの動作状態。 使用可能な値が含まれます: '停止'、'開始'、'実行中'、'停止'</param>
        <param name="gatewayIPConfigurations">アプリケーション ゲートウェイ リソースのサブネットです。</param>
        <param name="authenticationCertificates">アプリケーション ゲートウェイ リソースの証明書を認証します。</param>
        <param name="sslCertificates">アプリケーション ゲートウェイ リソースの SSL 証明書。</param>
        <param name="frontendIPConfigurations">アプリケーション ゲートウェイ リソースのフロント エンド IP アドレスです。</param>
        <param name="frontendPorts">アプリケーション ゲートウェイ リソースのフロント エンド ポートです。</param>
        <param name="probes">アプリケーション ゲートウェイ リソースのプローブです。</param>
        <param name="backendAddressPools">アプリケーション ゲートウェイ リソースのバックエンド アドレス プールです。</param>
        <param name="backendHttpSettingsCollection">アプリケーション ゲートウェイ リソースのバックエンド http 設定します。</param>
        <param name="httpListeners">アプリケーション ゲートウェイ リソースの http リスナーです。</param>
        <param name="urlPathMaps">アプリケーション ゲートウェイ リソースの URL パス マップします。</param>
        <param name="requestRoutingRules">アプリケーション ゲートウェイ リソースのルーティング規則を要求します。</param>
        <param name="redirectConfigurations">アプリケーション ゲートウェイ リソースの構成をリダイレクトします。</param>
        <param name="webApplicationFirewallConfiguration">Web アプリケーション ファイアウォール構成します。</param>
        <param name="enableHttp2">HTTP2 をアプリケーション ゲートウェイ リソースに対して有効かどうか。</param>
        <param name="resourceGuid">アプリケーション ゲートウェイ リソースのリソース GUID プロパティです。</param>
        <param name="provisioningState">アプリケーション ゲートウェイ リソースのプロビジョニング状態。 使用可能な値が: '更新'、'削除' および '失敗' です。</param>
        <param name="etag">読み取り専用する一意の文字列リソースを更新するたびに変化します。</param>
        <summary>
            ApplicationGateway クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationCertificates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayAuthenticationCertificate&gt; AuthenticationCertificates { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewayAuthenticationCertificate&gt; AuthenticationCertificates" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGateway.AuthenticationCertificates" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationCertificates As IList(Of ApplicationGatewayAuthenticationCertificate)" />
      <MemberSignature Language="F#" Value="member this.AuthenticationCertificates : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayAuthenticationCertificate&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGateway.AuthenticationCertificates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.authenticationCertificates")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayAuthenticationCertificate&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアプリケーション ゲートウェイ リソースの認証証明書を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackendAddressPools">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendAddressPool&gt; BackendAddressPools { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendAddressPool&gt; BackendAddressPools" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGateway.BackendAddressPools" />
      <MemberSignature Language="VB.NET" Value="Public Property BackendAddressPools As IList(Of ApplicationGatewayBackendAddressPool)" />
      <MemberSignature Language="F#" Value="member this.BackendAddressPools : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendAddressPool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGateway.BackendAddressPools" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.backendAddressPools")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendAddressPool&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアプリケーション ゲートウェイ リソースのバックエンド アドレス プールを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackendHttpSettingsCollection">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings&gt; BackendHttpSettingsCollection { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings&gt; BackendHttpSettingsCollection" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGateway.BackendHttpSettingsCollection" />
      <MemberSignature Language="VB.NET" Value="Public Property BackendHttpSettingsCollection As IList(Of ApplicationGatewayBackendHttpSettings)" />
      <MemberSignature Language="F#" Value="member this.BackendHttpSettingsCollection : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGateway.BackendHttpSettingsCollection" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.backendHttpSettingsCollection")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHttpSettings&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはバックエンド アプリケーション ゲートウェイ リソースの http 設定を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableHttp2">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableHttp2 { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableHttp2" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGateway.EnableHttp2" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableHttp2 As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableHttp2 : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGateway.EnableHttp2" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enableHttp2")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または HTTP2 が、アプリケーション ゲートウェイ リソースに対して有効になっているかどうかを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGateway.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGateway.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="etag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、リソースを更新するたびに変化する一意の読み取り専用文字列。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FrontendIPConfigurations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayFrontendIPConfiguration&gt; FrontendIPConfigurations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewayFrontendIPConfiguration&gt; FrontendIPConfigurations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGateway.FrontendIPConfigurations" />
      <MemberSignature Language="VB.NET" Value="Public Property FrontendIPConfigurations As IList(Of ApplicationGatewayFrontendIPConfiguration)" />
      <MemberSignature Language="F#" Value="member this.FrontendIPConfigurations : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayFrontendIPConfiguration&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGateway.FrontendIPConfigurations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.frontendIPConfigurations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayFrontendIPConfiguration&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはフロント エンド アプリケーション ゲートウェイ リソースの IP アドレスを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FrontendPorts">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayFrontendPort&gt; FrontendPorts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewayFrontendPort&gt; FrontendPorts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGateway.FrontendPorts" />
      <MemberSignature Language="VB.NET" Value="Public Property FrontendPorts As IList(Of ApplicationGatewayFrontendPort)" />
      <MemberSignature Language="F#" Value="member this.FrontendPorts : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayFrontendPort&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGateway.FrontendPorts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.frontendPorts")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayFrontendPort&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはフロント エンド アプリケーション ゲートウェイ リソースのポートを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GatewayIPConfigurations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayIPConfiguration&gt; GatewayIPConfigurations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewayIPConfiguration&gt; GatewayIPConfigurations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGateway.GatewayIPConfigurations" />
      <MemberSignature Language="VB.NET" Value="Public Property GatewayIPConfigurations As IList(Of ApplicationGatewayIPConfiguration)" />
      <MemberSignature Language="F#" Value="member this.GatewayIPConfigurations : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayIPConfiguration&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGateway.GatewayIPConfigurations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.gatewayIPConfigurations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayIPConfiguration&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、ゲートウェイ リソースをアプリケーションのサブネットに設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpListeners">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayHttpListener&gt; HttpListeners { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewayHttpListener&gt; HttpListeners" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGateway.HttpListeners" />
      <MemberSignature Language="VB.NET" Value="Public Property HttpListeners As IList(Of ApplicationGatewayHttpListener)" />
      <MemberSignature Language="F#" Value="member this.HttpListeners : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayHttpListener&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGateway.HttpListeners" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.httpListeners")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayHttpListener&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアプリケーション ゲートウェイ リソースの http リスナーを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationalState">
      <MemberSignature Language="C#" Value="public string OperationalState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OperationalState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGateway.OperationalState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OperationalState As String" />
      <MemberSignature Language="F#" Value="member this.OperationalState : string" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGateway.OperationalState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.operationalState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            アプリケーション ゲートウェイ リソースの操作状態を取得します。
            使用可能な値が含まれます: '停止'、'開始'、'実行中'、'停止'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Probes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe&gt; Probes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe&gt; Probes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGateway.Probes" />
      <MemberSignature Language="VB.NET" Value="Public Property Probes As IList(Of ApplicationGatewayProbe)" />
      <MemberSignature Language="F#" Value="member this.Probes : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGateway.Probes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.probes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアプリケーション ゲートウェイ リソースのプローブを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGateway.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGateway.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアプリケーション ゲートウェイ リソースのプロビジョニング状態を設定します。 使用可能な値が: '更新'、'削除' および '失敗' です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RedirectConfigurations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration&gt; RedirectConfigurations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration&gt; RedirectConfigurations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGateway.RedirectConfigurations" />
      <MemberSignature Language="VB.NET" Value="Public Property RedirectConfigurations As IList(Of ApplicationGatewayRedirectConfiguration)" />
      <MemberSignature Language="F#" Value="member this.RedirectConfigurations : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGateway.RedirectConfigurations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.redirectConfigurations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、アプリケーション ゲートウェイのリソースのリダイレクトを構成します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestRoutingRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayRequestRoutingRule&gt; RequestRoutingRules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewayRequestRoutingRule&gt; RequestRoutingRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGateway.RequestRoutingRules" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestRoutingRules As IList(Of ApplicationGatewayRequestRoutingRule)" />
      <MemberSignature Language="F#" Value="member this.RequestRoutingRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayRequestRoutingRule&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGateway.RequestRoutingRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.requestRoutingRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayRequestRoutingRule&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアプリケーション ゲートウェイ リソースの要求のルーティング規則を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceGuid">
      <MemberSignature Language="C#" Value="public string ResourceGuid { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceGuid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGateway.ResourceGuid" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceGuid As String" />
      <MemberSignature Language="F#" Value="member this.ResourceGuid : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGateway.ResourceGuid" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.resourceGuid")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはリソース GUID、アプリケーション ゲートウェイのリソースのプロパティを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.ApplicationGatewaySku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.ApplicationGatewaySku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGateway.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As ApplicationGatewaySku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Network.Models.ApplicationGatewaySku with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGateway.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ApplicationGatewaySku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアプリケーション ゲートウェイ リソースの SKU を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SslCertificates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslCertificate&gt; SslCertificates { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslCertificate&gt; SslCertificates" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGateway.SslCertificates" />
      <MemberSignature Language="VB.NET" Value="Public Property SslCertificates As IList(Of ApplicationGatewaySslCertificate)" />
      <MemberSignature Language="F#" Value="member this.SslCertificates : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslCertificate&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGateway.SslCertificates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sslCertificates")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslCertificate&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアプリケーション ゲートウェイ リソースの SSL 証明書を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SslPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPolicy SslPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPolicy SslPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGateway.SslPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property SslPolicy As ApplicationGatewaySslPolicy" />
      <MemberSignature Language="F#" Value="member this.SslPolicy : Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPolicy with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGateway.SslPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sslPolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアプリケーション ゲートウェイ リソースの SSL ポリシーを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UrlPathMaps">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayUrlPathMap&gt; UrlPathMaps { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewayUrlPathMap&gt; UrlPathMaps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGateway.UrlPathMaps" />
      <MemberSignature Language="VB.NET" Value="Public Property UrlPathMaps As IList(Of ApplicationGatewayUrlPathMap)" />
      <MemberSignature Language="F#" Value="member this.UrlPathMaps : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayUrlPathMap&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGateway.UrlPathMaps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.urlPathMaps")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayUrlPathMap&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアプリケーション ゲートウェイ リソースの URL パスのマップを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGateway.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="applicationGateway.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
    <Member MemberName="WebApplicationFirewallConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.ApplicationGatewayWebApplicationFirewallConfiguration WebApplicationFirewallConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.ApplicationGatewayWebApplicationFirewallConfiguration WebApplicationFirewallConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGateway.WebApplicationFirewallConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property WebApplicationFirewallConfiguration As ApplicationGatewayWebApplicationFirewallConfiguration" />
      <MemberSignature Language="F#" Value="member this.WebApplicationFirewallConfiguration : Microsoft.Azure.Management.Network.Models.ApplicationGatewayWebApplicationFirewallConfiguration with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGateway.WebApplicationFirewallConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.webApplicationFirewallConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ApplicationGatewayWebApplicationFirewallConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または web アプリケーション ファイアウォール構成を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>