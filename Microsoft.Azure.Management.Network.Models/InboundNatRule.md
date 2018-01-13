<Type Name="InboundNatRule" FullName="Microsoft.Azure.Management.Network.Models.InboundNatRule">
  <TypeSignature Language="C#" Value="public class InboundNatRule : Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit InboundNatRule extends Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.InboundNatRule" />
  <TypeSignature Language="VB.NET" Value="Public Class InboundNatRule&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type InboundNatRule = class&#xA;    inherit SubResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Network.Models.SubResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            ロード バランサーの着信 NAT ルール。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public InboundNatRule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.InboundNatRule.#ctor" />
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
            InboundNatRule クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public InboundNatRule (string id = null, Microsoft.Azure.Management.Network.Models.SubResource frontendIPConfiguration = null, Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration backendIPConfiguration = null, string protocol = null, Nullable&lt;int&gt; frontendPort = null, Nullable&lt;int&gt; backendPort = null, Nullable&lt;int&gt; idleTimeoutInMinutes = null, Nullable&lt;bool&gt; enableFloatingIP = null, string provisioningState = null, string name = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, class Microsoft.Azure.Management.Network.Models.SubResource frontendIPConfiguration, class Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration backendIPConfiguration, string protocol, valuetype System.Nullable`1&lt;int32&gt; frontendPort, valuetype System.Nullable`1&lt;int32&gt; backendPort, valuetype System.Nullable`1&lt;int32&gt; idleTimeoutInMinutes, valuetype System.Nullable`1&lt;bool&gt; enableFloatingIP, string provisioningState, string name, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.InboundNatRule.#ctor(System.String,Microsoft.Azure.Management.Network.Models.SubResource,Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Boolean},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional frontendIPConfiguration As SubResource = null, Optional backendIPConfiguration As NetworkInterfaceIPConfiguration = null, Optional protocol As String = null, Optional frontendPort As Nullable(Of Integer) = null, Optional backendPort As Nullable(Of Integer) = null, Optional idleTimeoutInMinutes As Nullable(Of Integer) = null, Optional enableFloatingIP As Nullable(Of Boolean) = null, Optional provisioningState As String = null, Optional name As String = null, Optional etag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.InboundNatRule : string * Microsoft.Azure.Management.Network.Models.SubResource * Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;bool&gt; * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.InboundNatRule" Usage="new Microsoft.Azure.Management.Network.Models.InboundNatRule (id, frontendIPConfiguration, backendIPConfiguration, protocol, frontendPort, backendPort, idleTimeoutInMinutes, enableFloatingIP, provisioningState, name, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="frontendIPConfiguration" Type="Microsoft.Azure.Management.Network.Models.SubResource" />
        <Parameter Name="backendIPConfiguration" Type="Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration" />
        <Parameter Name="protocol" Type="System.String" />
        <Parameter Name="frontendPort" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="backendPort" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="idleTimeoutInMinutes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="enableFloatingIP" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">リソースの ID</param>
        <param name="frontendIPConfiguration">フロント エンド IP アドレスへの参照。</param>
        <param name="backendIPConfiguration">VM のネットワーク インターフェイスで定義されているプライベート IP アドレスへの参照。 各フロント エンド IP 構成のフロント エンド ポートに送信されるトラフィックは、バックエンド ip アドレスに転送されます。</param>
        <param name="protocol">使用可能な値が含まれます: 'Udp'、'Tcp'、'All'</param>
        <param name="frontendPort">外部エンドポイントのポートです。 各規則のポート番号は、ロード バランサー内で一意でなければなりません。
            許容される値の範囲は 1 ~ 65534 です。</param>
        <param name="backendPort">内部エンドポイントで使用されるポートです。
            許容される値の範囲は 1 ~ 65535 です。</param>
        <param name="idleTimeoutInMinutes">TCP アイドル接続のタイムアウト。 値は、4 ~ 30 分間に設定できます。 既定値は、4 分です。 この要素は、プロトコルが TCP に設定されている場合にのみ使用します。</param>
        <param name="enableFloatingIP">SQL AlwaysOn 可用性グループの構成に必要な floating IP 機能用に仮想マシンのエンドポイントを構成します。 SQL server で SQL AlwaysOn 可用性グループを使用する場合、この設定が必要です。 エンドポイントを作成した後、この設定を変更することはできません。</param>
        <param name="provisioningState">パブリック IP リソースのプロビジョニングの状態を取得します。 使用可能な値が: '更新'、'削除' および '失敗' です。</param>
        <param name="name">リソース グループ内で一意であるリソースの名前を取得します。 この名前は、リソースへのアクセスに使用できます。</param>
        <param name="etag">読み取り専用する一意の文字列リソースを更新するたびに変化します。</param>
        <summary>
            InboundNatRule クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackendIPConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration BackendIPConfiguration { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration BackendIPConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.InboundNatRule.BackendIPConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackendIPConfiguration As NetworkInterfaceIPConfiguration" />
      <MemberSignature Language="F#" Value="member this.BackendIPConfiguration : Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration" Usage="Microsoft.Azure.Management.Network.Models.InboundNatRule.BackendIPConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.backendIPConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            VM のネットワーク インターフェイスで定義されているプライベート IP アドレスへの参照を取得します。 各フロント エンド IP 構成のフロント エンド ポートに送信されるトラフィックは、バックエンド ip アドレスに転送されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackendPort">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; BackendPort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; BackendPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.InboundNatRule.BackendPort" />
      <MemberSignature Language="VB.NET" Value="Public Property BackendPort As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.BackendPort : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.InboundNatRule.BackendPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.backendPort")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または内部エンドポイントで使用されるポートを設定します。 許容される値の範囲は 1 ~ 65535 です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableFloatingIP">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableFloatingIP { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableFloatingIP" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.InboundNatRule.EnableFloatingIP" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableFloatingIP As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableFloatingIP : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.InboundNatRule.EnableFloatingIP" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enableFloatingIP")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、SQL AlwaysOn 可用性グループの構成に必要な floating IP 機能用に仮想マシンのエンドポイントを構成します。 SQL server で SQL AlwaysOn 可用性グループを使用する場合、この設定が必要です。 エンドポイントを作成した後、この設定を変更することはできません。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.InboundNatRule.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.InboundNatRule.Etag" />
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
    <Member MemberName="FrontendIPConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.SubResource FrontendIPConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.SubResource FrontendIPConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.InboundNatRule.FrontendIPConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property FrontendIPConfiguration As SubResource" />
      <MemberSignature Language="F#" Value="member this.FrontendIPConfiguration : Microsoft.Azure.Management.Network.Models.SubResource with get, set" Usage="Microsoft.Azure.Management.Network.Models.InboundNatRule.FrontendIPConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.frontendIPConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはフロント エンド IP アドレスへの参照を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FrontendPort">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; FrontendPort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; FrontendPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.InboundNatRule.FrontendPort" />
      <MemberSignature Language="VB.NET" Value="Public Property FrontendPort As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.FrontendPort : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.InboundNatRule.FrontendPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.frontendPort")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または外部エンドポイントのポートを設定します。 各規則のポート番号は、ロード バランサー内で一意でなければなりません。 許容される値の範囲は 1 ~ 65534 です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IdleTimeoutInMinutes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; IdleTimeoutInMinutes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; IdleTimeoutInMinutes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.InboundNatRule.IdleTimeoutInMinutes" />
      <MemberSignature Language="VB.NET" Value="Public Property IdleTimeoutInMinutes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.IdleTimeoutInMinutes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.InboundNatRule.IdleTimeoutInMinutes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.idleTimeoutInMinutes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または TCP アイドル接続のタイムアウトを設定します。 値は、4 ~ 30 分間に設定できます。 既定値は、4 分です。
            この要素は、プロトコルが TCP に設定されている場合にのみ使用します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.InboundNatRule.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.InboundNatRule.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            リソース グループ内で一意であるリソースの名前を取得します。
            この名前は、リソースへのアクセスに使用できます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Protocol">
      <MemberSignature Language="C#" Value="public string Protocol { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Protocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.InboundNatRule.Protocol" />
      <MemberSignature Language="VB.NET" Value="Public Property Protocol As String" />
      <MemberSignature Language="F#" Value="member this.Protocol : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.InboundNatRule.Protocol" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.protocol")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定可能な値が含まれます: 'Udp'、'Tcp'、'All'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.InboundNatRule.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.InboundNatRule.ProvisioningState" />
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
            パブリック IP リソースのプロビジョニングの状態を取得します。 使用可能な値が: '更新'、'削除' および '失敗' です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>