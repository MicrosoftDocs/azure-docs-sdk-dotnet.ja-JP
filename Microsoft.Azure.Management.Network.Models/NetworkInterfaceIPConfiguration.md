<Type Name="NetworkInterfaceIPConfiguration" FullName="Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration">
  <TypeSignature Language="C#" Value="public class NetworkInterfaceIPConfiguration : Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NetworkInterfaceIPConfiguration extends Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class NetworkInterfaceIPConfiguration&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type NetworkInterfaceIPConfiguration = class&#xA;    inherit SubResource" />
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
            ネットワーク インターフェイスの ip を構成します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkInterfaceIPConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.#ctor" />
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
            NetworkInterfaceIPConfiguration クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkInterfaceIPConfiguration (string id = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendAddressPool&gt; applicationGatewayBackendAddressPools = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt; loadBalancerBackendAddressPools = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.InboundNatRule&gt; loadBalancerInboundNatRules = null, string privateIPAddress = null, string privateIPAllocationMethod = null, string privateIPAddressVersion = null, Microsoft.Azure.Management.Network.Models.Subnet subnet = null, Nullable&lt;bool&gt; primary = null, Microsoft.Azure.Management.Network.Models.PublicIPAddress publicIPAddress = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt; applicationSecurityGroups = null, string provisioningState = null, string name = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendAddressPool&gt; applicationGatewayBackendAddressPools, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt; loadBalancerBackendAddressPools, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.InboundNatRule&gt; loadBalancerInboundNatRules, string privateIPAddress, string privateIPAllocationMethod, string privateIPAddressVersion, class Microsoft.Azure.Management.Network.Models.Subnet subnet, valuetype System.Nullable`1&lt;bool&gt; primary, class Microsoft.Azure.Management.Network.Models.PublicIPAddress publicIPAddress, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt; applicationSecurityGroups, string provisioningState, string name, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.#ctor(System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendAddressPool},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.BackendAddressPool},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.InboundNatRule},System.String,System.String,System.String,Microsoft.Azure.Management.Network.Models.Subnet,System.Nullable{System.Boolean},Microsoft.Azure.Management.Network.Models.PublicIPAddress,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup},System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration : string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendAddressPool&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.InboundNatRule&gt; * string * string * string * Microsoft.Azure.Management.Network.Models.Subnet * Nullable&lt;bool&gt; * Microsoft.Azure.Management.Network.Models.PublicIPAddress * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt; * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration" Usage="new Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration (id, applicationGatewayBackendAddressPools, loadBalancerBackendAddressPools, loadBalancerInboundNatRules, privateIPAddress, privateIPAllocationMethod, privateIPAddressVersion, subnet, primary, publicIPAddress, applicationSecurityGroups, provisioningState, name, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="applicationGatewayBackendAddressPools" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendAddressPool&gt;" />
        <Parameter Name="loadBalancerBackendAddressPools" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt;" />
        <Parameter Name="loadBalancerInboundNatRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.InboundNatRule&gt;" />
        <Parameter Name="privateIPAddress" Type="System.String" />
        <Parameter Name="privateIPAllocationMethod" Type="System.String" />
        <Parameter Name="privateIPAddressVersion" Type="System.String" />
        <Parameter Name="subnet" Type="Microsoft.Azure.Management.Network.Models.Subnet" />
        <Parameter Name="primary" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="publicIPAddress" Type="Microsoft.Azure.Management.Network.Models.PublicIPAddress" />
        <Parameter Name="applicationSecurityGroups" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt;" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">リソースの ID</param>
        <param name="applicationGatewayBackendAddressPools">ApplicationGatewayBackendAddressPool リソースの参照です。</param>
        <param name="loadBalancerBackendAddressPools">LoadBalancerBackendAddressPool リソースの参照です。</param>
        <param name="loadBalancerInboundNatRules">LoadBalancerInboundNatRules の参照の一覧です。</param>
        <param name="privateIPAddress">IP 構成のプライベート IP アドレスです。</param>
        <param name="privateIPAllocationMethod">プライベート IP アドレスが割り当てられる方法を定義します。 使用可能な値が: 'Static' と 'Dynamic' です。
            使用可能な値が含まれます: 'Static'、'Dynamic'</param>
        <param name="privateIPAddressVersion">Api-バージョン 2016年-03-30 から使用可能な以降、そのかどうかを特定の ip 構成は、IPv4 または IPv6 です。 既定値は、IPv4 と見なされます。
            使用可能な値が: 'IPv4' および 'IPv6' です。 使用可能な値が含まれます: 'IPv4'、'IPv6'</param>
        <param name="subnet">サブネットは、IP 構成にバインドされます。</param>
        <param name="primary">ネットワーク インターフェイスのアドレスが 1 の顧客であるかどうかを取得します。</param>
        <param name="publicIPAddress">パブリック IP アドレスは、IP 構成にバインドします。</param>
        <param name="applicationSecurityGroups">IP 構成が含まれているアプリケーションのセキュリティ グループ。</param>
        <param name="provisioningState">ネットワーク インターフェイス IP 構成のプロビジョニングの状態。 使用可能な値が: '更新'、'削除' および '失敗' です。</param>
        <param name="name">リソース グループ内で一意であるリソースの名前。 この名前は、リソースへのアクセスに使用できます。</param>
        <param name="etag">読み取り専用する一意の文字列リソースを更新するたびに変化します。</param>
        <summary>
            NetworkInterfaceIPConfiguration クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationGatewayBackendAddressPools">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendAddressPool&gt; ApplicationGatewayBackendAddressPools { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendAddressPool&gt; ApplicationGatewayBackendAddressPools" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.ApplicationGatewayBackendAddressPools" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationGatewayBackendAddressPools As IList(Of ApplicationGatewayBackendAddressPool)" />
      <MemberSignature Language="F#" Value="member this.ApplicationGatewayBackendAddressPools : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendAddressPool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.ApplicationGatewayBackendAddressPools" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.applicationGatewayBackendAddressPools")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendAddressPool&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または ApplicationGatewayBackendAddressPool リソースへの参照を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationSecurityGroups">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt; ApplicationSecurityGroups { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt; ApplicationSecurityGroups" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.ApplicationSecurityGroups" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationSecurityGroups As IList(Of ApplicationSecurityGroup)" />
      <MemberSignature Language="F#" Value="member this.ApplicationSecurityGroups : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.ApplicationSecurityGroups" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.applicationSecurityGroups")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または IP 構成が含まれているアプリケーションのセキュリティ グループを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.Etag" />
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
    <Member MemberName="LoadBalancerBackendAddressPools">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt; LoadBalancerBackendAddressPools { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt; LoadBalancerBackendAddressPools" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.LoadBalancerBackendAddressPools" />
      <MemberSignature Language="VB.NET" Value="Public Property LoadBalancerBackendAddressPools As IList(Of BackendAddressPool)" />
      <MemberSignature Language="F#" Value="member this.LoadBalancerBackendAddressPools : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.LoadBalancerBackendAddressPools" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.loadBalancerBackendAddressPools")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または LoadBalancerBackendAddressPool リソースへの参照を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadBalancerInboundNatRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.InboundNatRule&gt; LoadBalancerInboundNatRules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.InboundNatRule&gt; LoadBalancerInboundNatRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.LoadBalancerInboundNatRules" />
      <MemberSignature Language="VB.NET" Value="Public Property LoadBalancerInboundNatRules As IList(Of InboundNatRule)" />
      <MemberSignature Language="F#" Value="member this.LoadBalancerInboundNatRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.InboundNatRule&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.LoadBalancerInboundNatRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.loadBalancerInboundNatRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.InboundNatRule&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または LoadBalancerInboundNatRules の参照の一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.Name" />
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
            取得またはリソース グループ内で一意であるリソースの名前を設定します。 この名前は、リソースへのアクセスに使用できます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Primary">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Primary { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Primary" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.Primary" />
      <MemberSignature Language="VB.NET" Value="Public Property Primary As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Primary : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.Primary" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.primary")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ネットワーク インターフェイスのアドレスが 1 の顧客であるかどうかを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrivateIPAddress">
      <MemberSignature Language="C#" Value="public string PrivateIPAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrivateIPAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.PrivateIPAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property PrivateIPAddress As String" />
      <MemberSignature Language="F#" Value="member this.PrivateIPAddress : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.PrivateIPAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.privateIPAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または IP 構成のプライベート IP アドレスを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrivateIPAddressVersion">
      <MemberSignature Language="C#" Value="public string PrivateIPAddressVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrivateIPAddressVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.PrivateIPAddressVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property PrivateIPAddressVersion As String" />
      <MemberSignature Language="F#" Value="member this.PrivateIPAddressVersion : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.PrivateIPAddressVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.privateIPAddressVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定 Api-バージョン 2016年-03-30 から使用可能な以降、特定の ip 構成が IPv4 または IPv6 であるかどうかを表します。
            既定値は、IPv4 と見なされます。  使用可能な値が: 'IPv4' および 'IPv6' です。
            使用可能な値が含まれます: 'IPv4'、'IPv6'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrivateIPAllocationMethod">
      <MemberSignature Language="C#" Value="public string PrivateIPAllocationMethod { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrivateIPAllocationMethod" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.PrivateIPAllocationMethod" />
      <MemberSignature Language="VB.NET" Value="Public Property PrivateIPAllocationMethod As String" />
      <MemberSignature Language="F#" Value="member this.PrivateIPAllocationMethod : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.PrivateIPAllocationMethod" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.privateIPAllocationMethod")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、プライベート IP アドレスが割り当てられる方法を定義します。 使用可能な値が: 'Static' と 'Dynamic' です。 使用可能な値が含まれます: 'Static'、'Dynamic'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.ProvisioningState" />
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
            取得またはネットワーク インターフェイス IP 構成のプロビジョニングの状態を設定します。 使用可能な値が: '更新'、'削除' および '失敗' です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublicIPAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.PublicIPAddress PublicIPAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.PublicIPAddress PublicIPAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.PublicIPAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property PublicIPAddress As PublicIPAddress" />
      <MemberSignature Language="F#" Value="member this.PublicIPAddress : Microsoft.Azure.Management.Network.Models.PublicIPAddress with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.PublicIPAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.publicIPAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.PublicIPAddress</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または IP 構成にバインドされているパブリック IP アドレスを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Subnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.Subnet Subnet { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.Subnet Subnet" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.Subnet" />
      <MemberSignature Language="VB.NET" Value="Public Property Subnet As Subnet" />
      <MemberSignature Language="F#" Value="member this.Subnet : Microsoft.Azure.Management.Network.Models.Subnet with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.Subnet" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.subnet")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.Subnet</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはサブネットの IP 構成にバインドを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>