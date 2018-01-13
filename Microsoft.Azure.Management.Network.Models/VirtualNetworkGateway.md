<Type Name="VirtualNetworkGateway" FullName="Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway">
  <TypeSignature Language="C#" Value="public class VirtualNetworkGateway : Microsoft.Azure.Management.Network.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualNetworkGateway extends Microsoft.Azure.Management.Network.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualNetworkGateway&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type VirtualNetworkGateway = class&#xA;    inherit Resource" />
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
            一般的なリソースについての一般的なクラス
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualNetworkGateway ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.#ctor" />
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
            VirtualNetworkGateway クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualNetworkGateway (string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayIPConfiguration&gt; ipConfigurations = null, string gatewayType = null, string vpnType = null, Nullable&lt;bool&gt; enableBgp = null, Nullable&lt;bool&gt; activeActive = null, Microsoft.Azure.Management.Network.Models.SubResource gatewayDefaultSite = null, Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewaySku sku = null, Microsoft.Azure.Management.Network.Models.VpnClientConfiguration vpnClientConfiguration = null, Microsoft.Azure.Management.Network.Models.BgpSettings bgpSettings = null, string resourceGuid = null, string provisioningState = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayIPConfiguration&gt; ipConfigurations, string gatewayType, string vpnType, valuetype System.Nullable`1&lt;bool&gt; enableBgp, valuetype System.Nullable`1&lt;bool&gt; activeActive, class Microsoft.Azure.Management.Network.Models.SubResource gatewayDefaultSite, class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewaySku sku, class Microsoft.Azure.Management.Network.Models.VpnClientConfiguration vpnClientConfiguration, class Microsoft.Azure.Management.Network.Models.BgpSettings bgpSettings, string resourceGuid, string provisioningState, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayIPConfiguration},System.String,System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},Microsoft.Azure.Management.Network.Models.SubResource,Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewaySku,Microsoft.Azure.Management.Network.Models.VpnClientConfiguration,Microsoft.Azure.Management.Network.Models.BgpSettings,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayIPConfiguration&gt; * string * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Microsoft.Azure.Management.Network.Models.SubResource * Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewaySku * Microsoft.Azure.Management.Network.Models.VpnClientConfiguration * Microsoft.Azure.Management.Network.Models.BgpSettings * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway" Usage="new Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway (id, name, type, location, tags, ipConfigurations, gatewayType, vpnType, enableBgp, activeActive, gatewayDefaultSite, sku, vpnClientConfiguration, bgpSettings, resourceGuid, provisioningState, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="ipConfigurations" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayIPConfiguration&gt;" />
        <Parameter Name="gatewayType" Type="System.String" />
        <Parameter Name="vpnType" Type="System.String" />
        <Parameter Name="enableBgp" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="activeActive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="gatewayDefaultSite" Type="Microsoft.Azure.Management.Network.Models.SubResource" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewaySku" />
        <Parameter Name="vpnClientConfiguration" Type="Microsoft.Azure.Management.Network.Models.VpnClientConfiguration" />
        <Parameter Name="bgpSettings" Type="Microsoft.Azure.Management.Network.Models.BgpSettings" />
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
        <param name="ipConfigurations">仮想ネットワーク ゲートウェイの IP 構成します。</param>
        <param name="gatewayType">この仮想ネットワーク ゲートウェイの種類。
            使用可能な値が: 'Vpn' と 'ExpressRoute' です。 使用可能な値が含まれます: 'Vpn'、'ExpressRoute'</param>
        <param name="vpnType">この仮想ネットワーク ゲートウェイの種類。
            使用可能な値が: 'PolicyBased' および 'はルートベースで' です。 使用可能な値が含まれます: 'PolicyBased'、'はルートベースで'</param>
        <param name="enableBgp">BGP が有効かどうかこの仮想ネットワーク ゲートウェイのされません。</param>
        <param name="activeActive">ActiveActive フラグ</param>
        <param name="gatewayDefaultSite">既定のルートを持つローカル ネットワーク サイトを表す LocalNetworkGateway リソースの参照です。 既存の既定のサイト設定の削除が発生した場合、Null 値を割り当てます。</param>
        <param name="sku">仮想ネットワーク ゲートウェイ用に選択された SKU を表す VirtualNetworkGatewaySku リソースの参照です。</param>
        <param name="vpnClientConfiguration">P2S がない場合構成を表す VpnClientConfiguration リソースの参照です。</param>
        <param name="bgpSettings">仮想ネットワーク ゲートウェイの BGP スピーカーの設定。</param>
        <param name="resourceGuid">リソース VirtualNetworkGateway リソースの GUID プロパティです。</param>
        <param name="provisioningState">VirtualNetworkGateway リソースのプロビジョニングの状態。 使用可能な値が: '更新'、'削除' および '失敗' です。</param>
        <param name="etag">リソースを更新するたびに変化する一意の読み取り専用文字列を取得します。</param>
        <summary>
            VirtualNetworkGateway クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActiveActive">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ActiveActive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ActiveActive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.ActiveActive" />
      <MemberSignature Language="VB.NET" Value="Public Property ActiveActive As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ActiveActive : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.ActiveActive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.activeActive")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または activeActive フラグを設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BgpSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.BgpSettings BgpSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.BgpSettings BgpSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.BgpSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property BgpSettings As BgpSettings" />
      <MemberSignature Language="F#" Value="member this.BgpSettings : Microsoft.Azure.Management.Network.Models.BgpSettings with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.BgpSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.bgpSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.BgpSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または仮想ネットワーク ゲートウェイの BGP スピーカーの設定を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableBgp">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableBgp { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableBgp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.EnableBgp" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableBgp As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableBgp : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.EnableBgp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enableBgp")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、この仮想ネットワーク ゲートウェイの BGP が有効かどうかを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.Etag" />
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
            リソースを更新するたびに変化する一意の読み取り専用文字列を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GatewayDefaultSite">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.SubResource GatewayDefaultSite { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.SubResource GatewayDefaultSite" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.GatewayDefaultSite" />
      <MemberSignature Language="VB.NET" Value="Public Property GatewayDefaultSite As SubResource" />
      <MemberSignature Language="F#" Value="member this.GatewayDefaultSite : Microsoft.Azure.Management.Network.Models.SubResource with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.GatewayDefaultSite" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.gatewayDefaultSite")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または既定のルートを持つローカル ネットワーク サイトを表す LocalNetworkGateway リソースへの参照を設定します。 既存の既定のサイト設定の削除が発生した場合、Null 値を割り当てます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GatewayType">
      <MemberSignature Language="C#" Value="public string GatewayType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GatewayType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.GatewayType" />
      <MemberSignature Language="VB.NET" Value="Public Property GatewayType As String" />
      <MemberSignature Language="F#" Value="member this.GatewayType : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.GatewayType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.gatewayType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、この仮想ネットワーク ゲートウェイの種類を設定します。 使用可能な値が: 'Vpn' と 'ExpressRoute' です。 使用可能な値が含まれます: 'Vpn'、'ExpressRoute'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IpConfigurations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayIPConfiguration&gt; IpConfigurations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayIPConfiguration&gt; IpConfigurations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.IpConfigurations" />
      <MemberSignature Language="VB.NET" Value="Public Property IpConfigurations As IList(Of VirtualNetworkGatewayIPConfiguration)" />
      <MemberSignature Language="F#" Value="member this.IpConfigurations : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayIPConfiguration&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.IpConfigurations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ipConfigurations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayIPConfiguration&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または仮想ネットワーク ゲートウェイの IP 構成を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.ProvisioningState" />
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
            VirtualNetworkGateway リソースのプロビジョニングの状態を取得します。
            使用可能な値が: '更新'、'削除' および '失敗' です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceGuid">
      <MemberSignature Language="C#" Value="public string ResourceGuid { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceGuid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.ResourceGuid" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceGuid As String" />
      <MemberSignature Language="F#" Value="member this.ResourceGuid : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.ResourceGuid" />
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
            取得またはリソース VirtualNetworkGateway リソースの GUID プロパティを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewaySku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewaySku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As VirtualNetworkGatewaySku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewaySku with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.Sku" />
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
        <ReturnType>Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewaySku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または仮想ネットワーク ゲートウェイ用に選択された SKU を表す VirtualNetworkGatewaySku リソースへの参照を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VpnClientConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.VpnClientConfiguration VpnClientConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.VpnClientConfiguration VpnClientConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.VpnClientConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property VpnClientConfiguration As VpnClientConfiguration" />
      <MemberSignature Language="F#" Value="member this.VpnClientConfiguration : Microsoft.Azure.Management.Network.Models.VpnClientConfiguration with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.VpnClientConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.vpnClientConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.VpnClientConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または P2S がない場合構成を表す VpnClientConfiguration リソースへの参照を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VpnType">
      <MemberSignature Language="C#" Value="public string VpnType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VpnType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.VpnType" />
      <MemberSignature Language="VB.NET" Value="Public Property VpnType As String" />
      <MemberSignature Language="F#" Value="member this.VpnType : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.VpnType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.vpnType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、この仮想ネットワーク ゲートウェイの種類を設定します。 使用可能な値が: 'PolicyBased' および 'はルートベースで' です。 使用可能な値が含まれます: 'PolicyBased'、'はルートベースで'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>