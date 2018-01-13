<Type Name="LoadBalancer" FullName="Microsoft.Azure.Management.Network.Models.LoadBalancer">
  <TypeSignature Language="C#" Value="public class LoadBalancer : Microsoft.Azure.Management.Network.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit LoadBalancer extends Microsoft.Azure.Management.Network.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.LoadBalancer" />
  <TypeSignature Language="VB.NET" Value="Public Class LoadBalancer&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type LoadBalancer = class&#xA;    inherit Resource" />
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
            ロード バランサー リソース
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LoadBalancer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.LoadBalancer.#ctor" />
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
            ロード バランサー クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LoadBalancer (string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.Network.Models.LoadBalancerSku sku = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.FrontendIPConfiguration&gt; frontendIPConfigurations = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt; backendAddressPools = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.LoadBalancingRule&gt; loadBalancingRules = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Probe&gt; probes = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.InboundNatRule&gt; inboundNatRules = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.InboundNatPool&gt; inboundNatPools = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.OutboundNatRule&gt; outboundNatRules = null, string resourceGuid = null, string provisioningState = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.Network.Models.LoadBalancerSku sku, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.FrontendIPConfiguration&gt; frontendIPConfigurations, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt; backendAddressPools, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.LoadBalancingRule&gt; loadBalancingRules, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.Probe&gt; probes, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.InboundNatRule&gt; inboundNatRules, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.InboundNatPool&gt; inboundNatPools, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.OutboundNatRule&gt; outboundNatRules, string resourceGuid, string provisioningState, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.LoadBalancer.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.Network.Models.LoadBalancerSku,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.FrontendIPConfiguration},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.BackendAddressPool},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.LoadBalancingRule},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.Probe},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.InboundNatRule},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.InboundNatPool},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.OutboundNatRule},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional location As String = null, Optional tags As IDictionary(Of String, String) = null, Optional sku As LoadBalancerSku = null, Optional frontendIPConfigurations As IList(Of FrontendIPConfiguration) = null, Optional backendAddressPools As IList(Of BackendAddressPool) = null, Optional loadBalancingRules As IList(Of LoadBalancingRule) = null, Optional probes As IList(Of Probe) = null, Optional inboundNatRules As IList(Of InboundNatRule) = null, Optional inboundNatPools As IList(Of InboundNatPool) = null, Optional outboundNatRules As IList(Of OutboundNatRule) = null, Optional resourceGuid As String = null, Optional provisioningState As String = null, Optional etag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.LoadBalancer : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.Network.Models.LoadBalancerSku * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.FrontendIPConfiguration&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.LoadBalancingRule&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Probe&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.InboundNatRule&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.InboundNatPool&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.OutboundNatRule&gt; * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.LoadBalancer" Usage="new Microsoft.Azure.Management.Network.Models.LoadBalancer (id, name, type, location, tags, sku, frontendIPConfigurations, backendAddressPools, loadBalancingRules, probes, inboundNatRules, inboundNatPools, outboundNatRules, resourceGuid, provisioningState, etag)" />
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
        <Parameter Name="sku" Type="Microsoft.Azure.Management.Network.Models.LoadBalancerSku" />
        <Parameter Name="frontendIPConfigurations" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.FrontendIPConfiguration&gt;" />
        <Parameter Name="backendAddressPools" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt;" />
        <Parameter Name="loadBalancingRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.LoadBalancingRule&gt;" />
        <Parameter Name="probes" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Probe&gt;" />
        <Parameter Name="inboundNatRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.InboundNatRule&gt;" />
        <Parameter Name="inboundNatPools" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.InboundNatPool&gt;" />
        <Parameter Name="outboundNatRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.OutboundNatRule&gt;" />
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
        <param name="sku">ロード バランサー SKU。</param>
        <param name="frontendIPConfigurations">フロント エンド ロード バランサーに使用する ip アドレスを表すオブジェクト</param>
        <param name="backendAddressPools">ロード バランサーが使用するバックエンド アドレス プールのコレクション</param>
        <param name="loadBalancingRules">負荷分散規則を表すオブジェクト コレクションのプロビジョニングを取得します。 </param>
        <param name="probes">ロード バランサーで使用されるプローブ オブジェクトのコレクション</param>
        <param name="inboundNatRules">ロード バランサーによって使用される受信の NAT 規則のコレクションです。 ロード バランサーの受信 NAT 規則を定義するは、着信 NAT プールの定義で相互に排他的です。
            着信 NAT プールは、仮想マシン スケール セットから参照されます。
            個々 の仮想マシンに関連付けられている Nic には、着信 NAT プールを参照できません。 個々 の受信 NAT 規則を参照する必要があります。</param>
        <param name="inboundNatPools">ロード バランサーに関連付けられている Nic で 1 台のバックエンド ポートへの着信 NAT を外部ポート範囲を定義します。 この範囲から外部ポートを使用するロード バランサーに関連付けられている各 NIC の受信 NAT 規則が自動的に作成されます。 受信 Nat 規則の定義で相互に排他的では、ロード バランサーの着信 NAT プールを定義します。 着信 NAT プールは、仮想マシン スケール セットから参照されます。 個々 の仮想マシンに関連付けられている Nic には、受信の NAT プールを参照できません。 個々 の受信 NAT 規則を参照する必要があります。</param>
        <param name="outboundNatRules">発信 NAT ルール。</param>
        <param name="resourceGuid">リソース GUID、ロード バランサーのリソースのプロパティです。</param>
        <param name="provisioningState">パブリック Ip リソースのプロビジョニングの状態を取得します。 使用可能な値が: '更新'、'削除' および '失敗' です。</param>
        <param name="etag">読み取り専用する一意の文字列リソースを更新するたびに変化します。</param>
        <summary>
            ロード バランサー クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackendAddressPools">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt; BackendAddressPools { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt; BackendAddressPools" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.LoadBalancer.BackendAddressPools" />
      <MemberSignature Language="VB.NET" Value="Public Property BackendAddressPools As IList(Of BackendAddressPool)" />
      <MemberSignature Language="F#" Value="member this.BackendAddressPools : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.LoadBalancer.BackendAddressPools" />
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
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定のロード バランサーによって使用されるバックエンド アドレス プールのコレクション
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.LoadBalancer.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.LoadBalancer.Etag" />
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
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.FrontendIPConfiguration&gt; FrontendIPConfigurations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.FrontendIPConfiguration&gt; FrontendIPConfigurations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.LoadBalancer.FrontendIPConfigurations" />
      <MemberSignature Language="VB.NET" Value="Public Property FrontendIPConfigurations As IList(Of FrontendIPConfiguration)" />
      <MemberSignature Language="F#" Value="member this.FrontendIPConfigurations : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.FrontendIPConfiguration&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.LoadBalancer.FrontendIPConfigurations" />
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
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.FrontendIPConfiguration&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定するフロント エンド ロード バランサーに使用する ip アドレスを表すオブジェクト
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InboundNatPools">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.InboundNatPool&gt; InboundNatPools { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.InboundNatPool&gt; InboundNatPools" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.LoadBalancer.InboundNatPools" />
      <MemberSignature Language="VB.NET" Value="Public Property InboundNatPools As IList(Of InboundNatPool)" />
      <MemberSignature Language="F#" Value="member this.InboundNatPools : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.InboundNatPool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.LoadBalancer.InboundNatPools" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.inboundNatPools")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.InboundNatPool&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、ロード バランサーに関連付けられている Nic で 1 台のバックエンド ポートへの着信 NAT を外部ポート範囲を定義します。
            この範囲から外部ポートを使用するロード バランサーに関連付けられている各 NIC の受信 NAT 規則が自動的に作成されます。
            受信 Nat 規則の定義で相互に排他的では、ロード バランサーの着信 NAT プールを定義します。 着信 NAT プールは、仮想マシン スケール セットから参照されます。 個々 の仮想マシンに関連付けられている Nic には、受信の NAT プールを参照できません。 個々 の受信 NAT 規則を参照する必要があります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InboundNatRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.InboundNatRule&gt; InboundNatRules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.InboundNatRule&gt; InboundNatRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.LoadBalancer.InboundNatRules" />
      <MemberSignature Language="VB.NET" Value="Public Property InboundNatRules As IList(Of InboundNatRule)" />
      <MemberSignature Language="F#" Value="member this.InboundNatRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.InboundNatRule&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.LoadBalancer.InboundNatRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.inboundNatRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.InboundNatRule&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはロード バランサーによって使用される受信の NAT 規則のコレクションを設定します。 ロード バランサーの受信 NAT 規則を定義するは、着信 NAT プールの定義で相互に排他的です。 着信 NAT プールは、仮想マシン スケール セットから参照されます。 個々 の仮想マシンに関連付けられている Nic には、着信 NAT プールを参照できません。 個々 の受信 NAT 規則を参照する必要があります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadBalancingRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.LoadBalancingRule&gt; LoadBalancingRules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.LoadBalancingRule&gt; LoadBalancingRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.LoadBalancer.LoadBalancingRules" />
      <MemberSignature Language="VB.NET" Value="Public Property LoadBalancingRules As IList(Of LoadBalancingRule)" />
      <MemberSignature Language="F#" Value="member this.LoadBalancingRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.LoadBalancingRule&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.LoadBalancer.LoadBalancingRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.loadBalancingRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.LoadBalancingRule&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または負荷分散の規則の取得を表すオブジェクト コレクションのプロビジョニングを設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutboundNatRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.OutboundNatRule&gt; OutboundNatRules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.OutboundNatRule&gt; OutboundNatRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.LoadBalancer.OutboundNatRules" />
      <MemberSignature Language="VB.NET" Value="Public Property OutboundNatRules As IList(Of OutboundNatRule)" />
      <MemberSignature Language="F#" Value="member this.OutboundNatRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.OutboundNatRule&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.LoadBalancer.OutboundNatRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.outboundNatRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.OutboundNatRule&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または送信 NAT 規則を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Probes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Probe&gt; Probes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.Probe&gt; Probes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.LoadBalancer.Probes" />
      <MemberSignature Language="VB.NET" Value="Public Property Probes As IList(Of Probe)" />
      <MemberSignature Language="F#" Value="member this.Probes : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Probe&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.LoadBalancer.Probes" />
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
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Probe&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定のロード バランサーで使用されるプローブ オブジェクトのコレクション
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.LoadBalancer.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.LoadBalancer.ProvisioningState" />
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
            パブリック Ip リソースのプロビジョニングの状態を取得します。 使用可能な値が: '更新'、'削除' および '失敗' です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceGuid">
      <MemberSignature Language="C#" Value="public string ResourceGuid { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceGuid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.LoadBalancer.ResourceGuid" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceGuid As String" />
      <MemberSignature Language="F#" Value="member this.ResourceGuid : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.LoadBalancer.ResourceGuid" />
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
            取得またはリソース GUID、ロード バランサーのリソースのプロパティを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.LoadBalancerSku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.LoadBalancerSku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.LoadBalancer.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As LoadBalancerSku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Network.Models.LoadBalancerSku with get, set" Usage="Microsoft.Azure.Management.Network.Models.LoadBalancer.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.LoadBalancerSku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはロード バランサーの SKU を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>