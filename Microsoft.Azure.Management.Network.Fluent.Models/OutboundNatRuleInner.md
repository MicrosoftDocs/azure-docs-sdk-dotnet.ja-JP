<Type Name="OutboundNatRuleInner" FullName="Microsoft.Azure.Management.Network.Fluent.Models.OutboundNatRuleInner">
  <TypeSignature Language="C#" Value="public class OutboundNatRuleInner : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OutboundNatRuleInner extends Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.OutboundNatRuleInner" />
  <TypeSignature Language="VB.NET" Value="Public Class OutboundNatRuleInner&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type OutboundNatRuleInner = class&#xA;    inherit SubResource" />
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
            ロード バランサーの発信 NAT プールです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OutboundNatRuleInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.OutboundNatRuleInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            OutboundNatRuleInner クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OutboundNatRuleInner (Microsoft.Azure.Management.ResourceManager.Fluent.SubResource backendAddressPool, string id = null, Nullable&lt;int&gt; allocatedOutboundPorts = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt; frontendIPConfigurations = null, string provisioningState = null, string name = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource backendAddressPool, string id, valuetype System.Nullable`1&lt;int32&gt; allocatedOutboundPorts, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt; frontendIPConfigurations, string provisioningState, string name, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.OutboundNatRuleInner.#ctor(Microsoft.Azure.Management.ResourceManager.Fluent.SubResource,System.String,System.Nullable{System.Int32},System.Collections.Generic.IList{Microsoft.Azure.Management.ResourceManager.Fluent.SubResource},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (backendAddressPool As SubResource, Optional id As String = null, Optional allocatedOutboundPorts As Nullable(Of Integer) = null, Optional frontendIPConfigurations As IList(Of SubResource) = null, Optional provisioningState As String = null, Optional name As String = null, Optional etag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.OutboundNatRuleInner : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource * string * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt; * string * string * string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.OutboundNatRuleInner" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.OutboundNatRuleInner (backendAddressPool, id, allocatedOutboundPorts, frontendIPConfigurations, provisioningState, name, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="backendAddressPool" Type="Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="allocatedOutboundPorts" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="frontendIPConfigurations" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt;" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="backendAddressPool">Dip のプールへの参照。
            送信トラフィックは、バックエンド ip アドレスで ip アドレスの間で分散ロードではランダムにです。</param>
        <param name="id">To be added.</param>
        <param name="allocatedOutboundPorts">Nat の外側に使用する送信ポートの数</param>
        <param name="frontendIPConfigurations">ロード バランサーのフロント エンド IP アドレス。</param>
        <param name="provisioningState">パブリック Ip リソースのプロビジョニングの状態を取得します。 使用可能な値が: '更新'、'削除' および '失敗' です。</param>
        <param name="name">リソース グループ内で一意であるリソースの名前。 この名前は、リソースへのアクセスに使用できます。</param>
        <param name="etag">読み取り専用する一意の文字列リソースを更新するたびに変化します。</param>
        <summary>
            OutboundNatRuleInner クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllocatedOutboundPorts">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; AllocatedOutboundPorts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; AllocatedOutboundPorts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.OutboundNatRuleInner.AllocatedOutboundPorts" />
      <MemberSignature Language="VB.NET" Value="Public Property AllocatedOutboundPorts As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.AllocatedOutboundPorts : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.OutboundNatRuleInner.AllocatedOutboundPorts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.allocatedOutboundPorts")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の nat の外側に使用する送信ポートの数
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackendAddressPool">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.SubResource BackendAddressPool { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource BackendAddressPool" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.OutboundNatRuleInner.BackendAddressPool" />
      <MemberSignature Language="VB.NET" Value="Public Property BackendAddressPool As SubResource" />
      <MemberSignature Language="F#" Value="member this.BackendAddressPool : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.OutboundNatRuleInner.BackendAddressPool" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.backendAddressPool")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Dip のプールへの参照を設定します。 送信トラフィックは、バックエンド ip アドレスで ip アドレスの間で分散ロードではランダムにです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.OutboundNatRuleInner.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.OutboundNatRuleInner.Etag" />
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
    <Member MemberName="FrontendIPConfigurations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt; FrontendIPConfigurations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt; FrontendIPConfigurations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.OutboundNatRuleInner.FrontendIPConfigurations" />
      <MemberSignature Language="VB.NET" Value="Public Property FrontendIPConfigurations As IList(Of SubResource)" />
      <MemberSignature Language="F#" Value="member this.FrontendIPConfigurations : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.OutboundNatRuleInner.FrontendIPConfigurations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.frontendIPConfigurations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアドレスのロード バランサーのフロント エンド IP を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.OutboundNatRuleInner.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.OutboundNatRuleInner.Name" />
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
            取得またはリソース グループ内で一意であるリソースの名前を設定します。 この名前は、リソースへのアクセスに使用できます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.OutboundNatRuleInner.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.OutboundNatRuleInner.ProvisioningState" />
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
            パブリック Ip リソースのプロビジョニングの状態を取得します。 使用可能な値が: '更新'、'削除' および '失敗' です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.OutboundNatRuleInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="outboundNatRuleInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
  </Members>
</Type>