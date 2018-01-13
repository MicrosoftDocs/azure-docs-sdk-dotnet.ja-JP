<Type Name="BackendAddressPool" FullName="Microsoft.Azure.Management.Network.Models.BackendAddressPool">
  <TypeSignature Language="C#" Value="public class BackendAddressPool : Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BackendAddressPool extends Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.BackendAddressPool" />
  <TypeSignature Language="VB.NET" Value="Public Class BackendAddressPool&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type BackendAddressPool = class&#xA;    inherit SubResource" />
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
            バックエンド IP アドレスのプールです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackendAddressPool ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.BackendAddressPool.#ctor" />
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
            BackendAddressPool クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackendAddressPool (string id = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt; backendIPConfigurations = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt; loadBalancingRules = null, Microsoft.Azure.Management.Network.Models.SubResource outboundNatRule = null, string provisioningState = null, string name = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt; backendIPConfigurations, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.SubResource&gt; loadBalancingRules, class Microsoft.Azure.Management.Network.Models.SubResource outboundNatRule, string provisioningState, string name, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.BackendAddressPool.#ctor(System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.SubResource},Microsoft.Azure.Management.Network.Models.SubResource,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional backendIPConfigurations As IList(Of NetworkInterfaceIPConfiguration) = null, Optional loadBalancingRules As IList(Of SubResource) = null, Optional outboundNatRule As SubResource = null, Optional provisioningState As String = null, Optional name As String = null, Optional etag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.BackendAddressPool : string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt; * Microsoft.Azure.Management.Network.Models.SubResource * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.BackendAddressPool" Usage="new Microsoft.Azure.Management.Network.Models.BackendAddressPool (id, backendIPConfigurations, loadBalancingRules, outboundNatRule, provisioningState, name, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="backendIPConfigurations" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;" />
        <Parameter Name="loadBalancingRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt;" />
        <Parameter Name="outboundNatRule" Type="Microsoft.Azure.Management.Network.Models.SubResource" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">リソースの ID</param>
        <param name="backendIPConfigurations">ネットワーク インターフェイスで定義されている IP アドレスへの参照のコレクションを取得します。</param>
        <param name="loadBalancingRules">このバックエンド アドレス プールを使用するルールを分散ロードを取得します。</param>
        <param name="outboundNatRule">このバックエンド アドレス プールを使用する送信規則を取得します。</param>
        <param name="provisioningState">パブリック IP リソースの状態のプロビジョニングを取得します。 使用可能な値が: '更新'、'削除' および '失敗' です。</param>
        <param name="name">リソース グループ内で一意であるリソースの名前を取得します。 この名前は、リソースへのアクセスに使用できます。</param>
        <param name="etag">読み取り専用する一意の文字列リソースを更新するたびに変化します。</param>
        <summary>
            BackendAddressPool クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackendIPConfigurations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt; BackendIPConfigurations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt; BackendIPConfigurations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.BackendAddressPool.BackendIPConfigurations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackendIPConfigurations As IList(Of NetworkInterfaceIPConfiguration)" />
      <MemberSignature Language="F#" Value="member this.BackendIPConfigurations : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;" Usage="Microsoft.Azure.Management.Network.Models.BackendAddressPool.BackendIPConfigurations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.backendIPConfigurations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ネットワーク インターフェイスで定義されている IP アドレスへの参照のコレクションを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.BackendAddressPool.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.BackendAddressPool.Etag" />
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
    <Member MemberName="LoadBalancingRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt; LoadBalancingRules { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.SubResource&gt; LoadBalancingRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.BackendAddressPool.LoadBalancingRules" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LoadBalancingRules As IList(Of SubResource)" />
      <MemberSignature Language="F#" Value="member this.LoadBalancingRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt;" Usage="Microsoft.Azure.Management.Network.Models.BackendAddressPool.LoadBalancingRules" />
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
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このバックエンド アドレス プールを使用するルールを分散ロードを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.BackendAddressPool.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.BackendAddressPool.Name" />
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
    <Member MemberName="OutboundNatRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.SubResource OutboundNatRule { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.SubResource OutboundNatRule" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.BackendAddressPool.OutboundNatRule" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OutboundNatRule As SubResource" />
      <MemberSignature Language="F#" Value="member this.OutboundNatRule : Microsoft.Azure.Management.Network.Models.SubResource" Usage="Microsoft.Azure.Management.Network.Models.BackendAddressPool.OutboundNatRule" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.outboundNatRule")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このバックエンド アドレス プールを使用する送信規則を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.BackendAddressPool.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.BackendAddressPool.ProvisioningState" />
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
            取得または get、パブリック IP リソースのプロビジョニング状態を設定します。
            使用可能な値が: '更新'、'削除' および '失敗' です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>