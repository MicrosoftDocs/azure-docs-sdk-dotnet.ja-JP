<Type Name="VirtualNetwork" FullName="Microsoft.Azure.Management.Network.Models.VirtualNetwork">
  <TypeSignature Language="C#" Value="public class VirtualNetwork : Microsoft.Azure.Management.Network.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualNetwork extends Microsoft.Azure.Management.Network.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.VirtualNetwork" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualNetwork&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type VirtualNetwork = class&#xA;    inherit Resource" />
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
            仮想ネットワークのリソースです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualNetwork ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.VirtualNetwork.#ctor" />
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
            VirtualNetwork クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualNetwork (string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.Network.Models.AddressSpace addressSpace = null, Microsoft.Azure.Management.Network.Models.DhcpOptions dhcpOptions = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt; subnets = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt; virtualNetworkPeerings = null, string resourceGuid = null, string provisioningState = null, Nullable&lt;bool&gt; enableDdosProtection = null, Nullable&lt;bool&gt; enableVmProtection = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.Network.Models.AddressSpace addressSpace, class Microsoft.Azure.Management.Network.Models.DhcpOptions dhcpOptions, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.Subnet&gt; subnets, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt; virtualNetworkPeerings, string resourceGuid, string provisioningState, valuetype System.Nullable`1&lt;bool&gt; enableDdosProtection, valuetype System.Nullable`1&lt;bool&gt; enableVmProtection, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.VirtualNetwork.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.Network.Models.AddressSpace,Microsoft.Azure.Management.Network.Models.DhcpOptions,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.Subnet},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering},System.String,System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.VirtualNetwork : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.Network.Models.AddressSpace * Microsoft.Azure.Management.Network.Models.DhcpOptions * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt; * string * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * string -&gt; Microsoft.Azure.Management.Network.Models.VirtualNetwork" Usage="new Microsoft.Azure.Management.Network.Models.VirtualNetwork (id, name, type, location, tags, addressSpace, dhcpOptions, subnets, virtualNetworkPeerings, resourceGuid, provisioningState, enableDdosProtection, enableVmProtection, etag)" />
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
        <Parameter Name="addressSpace" Type="Microsoft.Azure.Management.Network.Models.AddressSpace" />
        <Parameter Name="dhcpOptions" Type="Microsoft.Azure.Management.Network.Models.DhcpOptions" />
        <Parameter Name="subnets" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt;" />
        <Parameter Name="virtualNetworkPeerings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt;" />
        <Parameter Name="resourceGuid" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="enableDdosProtection" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="enableVmProtection" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">リソースの ID</param>
        <param name="name">リソース名。</param>
        <param name="type">リソースの種類。</param>
        <param name="location">リソースの場所。</param>
        <param name="tags">リソース タグ。</param>
        <param name="addressSpace">サブネットで使用できる IP アドレス範囲の配列を含む AddressSpace です。</param>
        <param name="dhcpOptions">仮想ネットワークにデプロイされた Vm で利用できる DNS サーバーの配列を含む dhcpOptions です。</param>
        <param name="subnets">仮想ネットワークのサブネットの一覧。</param>
        <param name="virtualNetworkPeerings">仮想ネットワーク内のピアリングの一覧。</param>
        <param name="resourceGuid">仮想ネットワーク リソースの resourceGuid プロパティです。</param>
        <param name="provisioningState">パブリック Ip リソースのプロビジョニングの状態。 使用可能な値が: '更新'、'削除' および '失敗' です。</param>
        <param name="enableDdosProtection">Ddos に対する防御が仮想ネットワーク内のすべての保護されたリソースに対して有効になっているかどうかを示します。</param>
        <param name="enableVmProtection">仮想ネットワーク内のすべてのサブネットの Vm の保護が有効になっているかどうかを示します。</param>
        <param name="etag">リソースを更新するたびに変化する一意の読み取り専用文字列を取得します。</param>
        <summary>
            VirtualNetwork クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddressSpace">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.AddressSpace AddressSpace { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.AddressSpace AddressSpace" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetwork.AddressSpace" />
      <MemberSignature Language="VB.NET" Value="Public Property AddressSpace As AddressSpace" />
      <MemberSignature Language="F#" Value="member this.AddressSpace : Microsoft.Azure.Management.Network.Models.AddressSpace with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetwork.AddressSpace" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.addressSpace")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.AddressSpace</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはサブネットで使用できる IP アドレス範囲の配列を含む AddressSpace を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DhcpOptions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.DhcpOptions DhcpOptions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.DhcpOptions DhcpOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetwork.DhcpOptions" />
      <MemberSignature Language="VB.NET" Value="Public Property DhcpOptions As DhcpOptions" />
      <MemberSignature Language="F#" Value="member this.DhcpOptions : Microsoft.Azure.Management.Network.Models.DhcpOptions with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetwork.DhcpOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dhcpOptions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.DhcpOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または仮想ネットワークにデプロイされた Vm で利用できる DNS サーバーの配列を含む dhcpOptions を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableDdosProtection">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableDdosProtection { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableDdosProtection" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetwork.EnableDdosProtection" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableDdosProtection As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableDdosProtection : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetwork.EnableDdosProtection" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enableDdosProtection")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、仮想ネットワーク内のすべての保護されたリソースに対する ddos に対する防御が有効になっているかどうかを示します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableVmProtection">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableVmProtection { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableVmProtection" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetwork.EnableVmProtection" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableVmProtection As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableVmProtection : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetwork.EnableVmProtection" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enableVmProtection")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、仮想ネットワーク内のすべてのサブネットの Vm の保護が有効になっているかどうかを示します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetwork.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetwork.Etag" />
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
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetwork.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetwork.ProvisioningState" />
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
            取得またはパブリック Ip リソースのプロビジョニングの状態を設定します。
            使用可能な値が: '更新'、'削除' および '失敗' です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceGuid">
      <MemberSignature Language="C#" Value="public string ResourceGuid { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceGuid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetwork.ResourceGuid" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceGuid As String" />
      <MemberSignature Language="F#" Value="member this.ResourceGuid : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetwork.ResourceGuid" />
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
            取得または仮想ネットワーク リソースの resourceGuid プロパティを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Subnets">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt; Subnets { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.Subnet&gt; Subnets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetwork.Subnets" />
      <MemberSignature Language="VB.NET" Value="Public Property Subnets As IList(Of Subnet)" />
      <MemberSignature Language="F#" Value="member this.Subnets : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetwork.Subnets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.subnets")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または仮想ネットワークのサブネットのリストを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualNetworkPeerings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt; VirtualNetworkPeerings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt; VirtualNetworkPeerings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetwork.VirtualNetworkPeerings" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualNetworkPeerings As IList(Of VirtualNetworkPeering)" />
      <MemberSignature Language="F#" Value="member this.VirtualNetworkPeerings : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetwork.VirtualNetworkPeerings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.virtualNetworkPeerings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または仮想ネットワークのピアリングの一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>