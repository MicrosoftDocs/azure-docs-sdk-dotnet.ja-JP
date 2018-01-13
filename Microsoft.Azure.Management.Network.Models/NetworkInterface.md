<Type Name="NetworkInterface" FullName="Microsoft.Azure.Management.Network.Models.NetworkInterface">
  <TypeSignature Language="C#" Value="public class NetworkInterface : Microsoft.Azure.Management.Network.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NetworkInterface extends Microsoft.Azure.Management.Network.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.NetworkInterface" />
  <TypeSignature Language="VB.NET" Value="Public Class NetworkInterface&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type NetworkInterface = class&#xA;    inherit Resource" />
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
            リソース グループ内のネットワーク インターフェイスです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkInterface ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.NetworkInterface.#ctor" />
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
            NetworkInterface クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkInterface (string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.Network.Models.SubResource virtualMachine = null, Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup networkSecurityGroup = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt; ipConfigurations = null, Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings dnsSettings = null, string macAddress = null, Nullable&lt;bool&gt; primary = null, Nullable&lt;bool&gt; enableAcceleratedNetworking = null, Nullable&lt;bool&gt; enableIPForwarding = null, string resourceGuid = null, string provisioningState = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.Network.Models.SubResource virtualMachine, class Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup networkSecurityGroup, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt; ipConfigurations, class Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings dnsSettings, string macAddress, valuetype System.Nullable`1&lt;bool&gt; primary, valuetype System.Nullable`1&lt;bool&gt; enableAcceleratedNetworking, valuetype System.Nullable`1&lt;bool&gt; enableIPForwarding, string resourceGuid, string provisioningState, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.NetworkInterface.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.Network.Models.SubResource,Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration},Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings,System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.NetworkInterface : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.Network.Models.SubResource * Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt; * Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.NetworkInterface" Usage="new Microsoft.Azure.Management.Network.Models.NetworkInterface (id, name, type, location, tags, virtualMachine, networkSecurityGroup, ipConfigurations, dnsSettings, macAddress, primary, enableAcceleratedNetworking, enableIPForwarding, resourceGuid, provisioningState, etag)" />
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
        <Parameter Name="virtualMachine" Type="Microsoft.Azure.Management.Network.Models.SubResource" />
        <Parameter Name="networkSecurityGroup" Type="Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup" />
        <Parameter Name="ipConfigurations" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;" />
        <Parameter Name="dnsSettings" Type="Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings" />
        <Parameter Name="macAddress" Type="System.String" />
        <Parameter Name="primary" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="enableAcceleratedNetworking" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="enableIPForwarding" Type="System.Nullable&lt;System.Boolean&gt;" />
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
        <param name="virtualMachine">仮想マシンの参照です。</param>
        <param name="networkSecurityGroup">NetworkSecurityGroup リソースの参照です。</param>
        <param name="ipConfigurations">ネットワーク インターフェイスの ip 構成の一覧。</param>
        <param name="dnsSettings">ネットワーク インターフェイスで DNS 設定します。</param>
        <param name="macAddress">ネットワーク インターフェイスの MAC アドレス。</param>
        <param name="primary">これは、仮想マシン上のプライマリ ネットワーク インターフェイスであるかどうかを取得します。</param>
        <param name="enableAcceleratedNetworking">ネットワーク インターフェイスのネットワークが高速化が有効になります。</param>
        <param name="enableIPForwarding">このネットワーク インターフェイスの IP 転送が有効になっているかどうかを示します。</param>
        <param name="resourceGuid">リソース GUID、ネットワーク インターフェイスのリソースのプロパティです。</param>
        <param name="provisioningState">パブリック IP リソースのプロビジョニングの状態。 使用可能な値が: '更新'、'削除' および '失敗' です。</param>
        <param name="etag">読み取り専用する一意の文字列リソースを更新するたびに変化します。</param>
        <summary>
            NetworkInterface クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DnsSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings DnsSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings DnsSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterface.DnsSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property DnsSettings As NetworkInterfaceDnsSettings" />
      <MemberSignature Language="F#" Value="member this.DnsSettings : Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterface.DnsSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dnsSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはネットワーク インターフェイスで DNS 設定を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableAcceleratedNetworking">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableAcceleratedNetworking { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableAcceleratedNetworking" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterface.EnableAcceleratedNetworking" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableAcceleratedNetworking As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableAcceleratedNetworking : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterface.EnableAcceleratedNetworking" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enableAcceleratedNetworking")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、ネットワーク インターフェイスがある場合は、有効になっているネットワークを高速化。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableIPForwarding">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableIPForwarding { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableIPForwarding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterface.EnableIPForwarding" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableIPForwarding As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableIPForwarding : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterface.EnableIPForwarding" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enableIPForwarding")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、このネットワーク インターフェイスの IP 転送が有効になっているかどうかを示します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterface.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterface.Etag" />
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
    <Member MemberName="IpConfigurations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt; IpConfigurations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt; IpConfigurations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterface.IpConfigurations" />
      <MemberSignature Language="VB.NET" Value="Public Property IpConfigurations As IList(Of NetworkInterfaceIPConfiguration)" />
      <MemberSignature Language="F#" Value="member this.IpConfigurations : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterface.IpConfigurations" />
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
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはネットワーク インターフェイスの ip 構成の一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MacAddress">
      <MemberSignature Language="C#" Value="public string MacAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MacAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterface.MacAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property MacAddress As String" />
      <MemberSignature Language="F#" Value="member this.MacAddress : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterface.MacAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.macAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはネットワーク インターフェイスの MAC アドレスを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkSecurityGroup">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup NetworkSecurityGroup { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup NetworkSecurityGroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterface.NetworkSecurityGroup" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkSecurityGroup As NetworkSecurityGroup" />
      <MemberSignature Language="F#" Value="member this.NetworkSecurityGroup : Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterface.NetworkSecurityGroup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.networkSecurityGroup")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または NetworkSecurityGroup リソースへの参照を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Primary">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Primary { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Primary" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterface.Primary" />
      <MemberSignature Language="VB.NET" Value="Public Property Primary As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Primary : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterface.Primary" />
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
            これは、仮想マシン上のプライマリ ネットワーク インターフェイスであるかどうかを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterface.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterface.ProvisioningState" />
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
            取得またはパブリック IP リソースのプロビジョニングの状態を設定します。
            使用可能な値が: '更新'、'削除' および '失敗' です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceGuid">
      <MemberSignature Language="C#" Value="public string ResourceGuid { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceGuid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterface.ResourceGuid" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceGuid As String" />
      <MemberSignature Language="F#" Value="member this.ResourceGuid : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterface.ResourceGuid" />
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
            取得またはリソース GUID、ネットワーク インターフェイスのリソースのプロパティを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachine">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.SubResource VirtualMachine { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.SubResource VirtualMachine" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterface.VirtualMachine" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualMachine As SubResource" />
      <MemberSignature Language="F#" Value="member this.VirtualMachine : Microsoft.Azure.Management.Network.Models.SubResource with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterface.VirtualMachine" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.virtualMachine")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または仮想マシンへの参照を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>