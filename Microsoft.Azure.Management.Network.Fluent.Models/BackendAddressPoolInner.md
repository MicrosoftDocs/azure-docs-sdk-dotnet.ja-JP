<Type Name="BackendAddressPoolInner" FullName="Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner">
  <TypeSignature Language="C#" Value="public class BackendAddressPoolInner : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BackendAddressPoolInner extends Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner" />
  <TypeSignature Language="VB.NET" Value="Public Class BackendAddressPoolInner&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type BackendAddressPoolInner = class&#xA;    inherit SubResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.SubResource</BaseTypeName>
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
      <MemberSignature Language="C#" Value="public BackendAddressPoolInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            BackendAddressPoolInner クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackendAddressPoolInner (string id = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceIPConfigurationInner&gt; backendIPConfigurations = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt; loadBalancingRules = null, Microsoft.Azure.Management.ResourceManager.Fluent.SubResource outboundNatRule = null, string provisioningState = null, string name = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceIPConfigurationInner&gt; backendIPConfigurations, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt; loadBalancingRules, class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource outboundNatRule, string provisioningState, string name, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner.#ctor(System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceIPConfigurationInner},System.Collections.Generic.IList{Microsoft.Azure.Management.ResourceManager.Fluent.SubResource},Microsoft.Azure.Management.ResourceManager.Fluent.SubResource,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional backendIPConfigurations As IList(Of NetworkInterfaceIPConfigurationInner) = null, Optional loadBalancingRules As IList(Of SubResource) = null, Optional outboundNatRule As SubResource = null, Optional provisioningState As String = null, Optional name As String = null, Optional etag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner : string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceIPConfigurationInner&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt; * Microsoft.Azure.Management.ResourceManager.Fluent.SubResource * string * string * string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner (id, backendIPConfigurations, loadBalancingRules, outboundNatRule, provisioningState, name, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="backendIPConfigurations" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceIPConfigurationInner&gt;" />
        <Parameter Name="loadBalancingRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt;" />
        <Parameter Name="outboundNatRule" Type="Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">To be added.</param>
        <param name="backendIPConfigurations">ネットワーク インターフェイスで定義されている IP アドレスへの参照のコレクションを取得します。</param>
        <param name="loadBalancingRules">このバックエンド アドレス プールを使用するルールを分散ロードを取得します。</param>
        <param name="outboundNatRule">このバックエンド アドレス プールを使用する送信規則を取得します。</param>
        <param name="provisioningState">パブリック IP リソースの状態のプロビジョニングを取得します。 使用可能な値が: '更新'、'削除' および '失敗' です。</param>
        <param name="name">リソース グループ内で一意であるリソースの名前を取得します。 この名前は、リソースへのアクセスに使用できます。</param>
        <param name="etag">読み取り専用する一意の文字列リソースを更新するたびに変化します。</param>
        <summary>
            BackendAddressPoolInner クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackendIPConfigurations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceIPConfigurationInner&gt; BackendIPConfigurations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceIPConfigurationInner&gt; BackendIPConfigurations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner.BackendIPConfigurations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackendIPConfigurations As IList(Of NetworkInterfaceIPConfigurationInner)" />
      <MemberSignature Language="F#" Value="member this.BackendIPConfigurations : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceIPConfigurationInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner.BackendIPConfigurations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.backendIPConfigurations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceIPConfigurationInner&gt;</ReturnType>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt; LoadBalancingRules { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt; LoadBalancingRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner.LoadBalancingRules" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LoadBalancingRules As IList(Of SubResource)" />
      <MemberSignature Language="F#" Value="member this.LoadBalancingRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner.LoadBalancingRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.loadBalancingRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt;</ReturnType>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.SubResource OutboundNatRule { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource OutboundNatRule" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner.OutboundNatRule" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OutboundNatRule As SubResource" />
      <MemberSignature Language="F#" Value="member this.OutboundNatRule : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" Usage="Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner.OutboundNatRule" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.outboundNatRule")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.SubResource</ReturnType>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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