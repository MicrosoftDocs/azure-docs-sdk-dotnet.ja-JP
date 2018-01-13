<Type Name="InboundNatPool" FullName="Microsoft.Azure.Management.Network.Models.InboundNatPool">
  <TypeSignature Language="C#" Value="public class InboundNatPool : Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit InboundNatPool extends Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.InboundNatPool" />
  <TypeSignature Language="VB.NET" Value="Public Class InboundNatPool&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type InboundNatPool = class&#xA;    inherit SubResource" />
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
            ロード バランサーの着信 NAT プールです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public InboundNatPool ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.InboundNatPool.#ctor" />
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
            InboundNatPool クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public InboundNatPool (string protocol, int frontendPortRangeStart, int frontendPortRangeEnd, int backendPort, string id = null, Microsoft.Azure.Management.Network.Models.SubResource frontendIPConfiguration = null, string provisioningState = null, string name = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string protocol, int32 frontendPortRangeStart, int32 frontendPortRangeEnd, int32 backendPort, string id, class Microsoft.Azure.Management.Network.Models.SubResource frontendIPConfiguration, string provisioningState, string name, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.InboundNatPool.#ctor(System.String,System.Int32,System.Int32,System.Int32,System.String,Microsoft.Azure.Management.Network.Models.SubResource,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (protocol As String, frontendPortRangeStart As Integer, frontendPortRangeEnd As Integer, backendPort As Integer, Optional id As String = null, Optional frontendIPConfiguration As SubResource = null, Optional provisioningState As String = null, Optional name As String = null, Optional etag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.InboundNatPool : string * int * int * int * string * Microsoft.Azure.Management.Network.Models.SubResource * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.InboundNatPool" Usage="new Microsoft.Azure.Management.Network.Models.InboundNatPool (protocol, frontendPortRangeStart, frontendPortRangeEnd, backendPort, id, frontendIPConfiguration, provisioningState, name, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="protocol" Type="System.String" />
        <Parameter Name="frontendPortRangeStart" Type="System.Int32" />
        <Parameter Name="frontendPortRangeEnd" Type="System.Int32" />
        <Parameter Name="backendPort" Type="System.Int32" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="frontendIPConfiguration" Type="Microsoft.Azure.Management.Network.Models.SubResource" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="protocol">使用可能な値が含まれます: 'Udp'、'Tcp'、'All'</param>
        <param name="frontendPortRangeStart">ロード バランサーに関連付けられている Nic に受信の Nat を提供するために使用する外部ポートの範囲の最初のポート番号。 許容される値の範囲は 1 ~ 65,534 の範囲です。</param>
        <param name="frontendPortRangeEnd">ロード バランサーに関連付けられている Nic に受信の Nat を提供するために使用する外部ポートの範囲の最後のポート番号。 1 から 65535 までの範囲を指定できる値です。</param>
        <param name="backendPort">エンドポイントの内部接続に使用されるポート。 指定できる値は、1 ~ 65535 の間はします。</param>
        <param name="id">リソースの ID</param>
        <param name="frontendIPConfiguration">フロント エンド IP アドレスへの参照。</param>
        <param name="provisioningState">パブリック Ip リソースのプロビジョニングの状態を取得します。 使用可能な値が: '更新'、'削除' および '失敗' です。</param>
        <param name="name">リソース グループ内で一意であるリソースの名前。 この名前は、リソースへのアクセスに使用できます。</param>
        <param name="etag">読み取り専用する一意の文字列リソースを更新するたびに変化します。</param>
        <summary>
            InboundNatPool クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackendPort">
      <MemberSignature Language="C#" Value="public int BackendPort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 BackendPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.InboundNatPool.BackendPort" />
      <MemberSignature Language="VB.NET" Value="Public Property BackendPort As Integer" />
      <MemberSignature Language="F#" Value="member this.BackendPort : int with get, set" Usage="Microsoft.Azure.Management.Network.Models.InboundNatPool.BackendPort" />
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
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはエンドポイントの内部接続に使用するポートを設定します。 指定できる値は、1 ~ 65535 の間はします。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.InboundNatPool.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.InboundNatPool.Etag" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.InboundNatPool.FrontendIPConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property FrontendIPConfiguration As SubResource" />
      <MemberSignature Language="F#" Value="member this.FrontendIPConfiguration : Microsoft.Azure.Management.Network.Models.SubResource with get, set" Usage="Microsoft.Azure.Management.Network.Models.InboundNatPool.FrontendIPConfiguration" />
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
    <Member MemberName="FrontendPortRangeEnd">
      <MemberSignature Language="C#" Value="public int FrontendPortRangeEnd { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 FrontendPortRangeEnd" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.InboundNatPool.FrontendPortRangeEnd" />
      <MemberSignature Language="VB.NET" Value="Public Property FrontendPortRangeEnd As Integer" />
      <MemberSignature Language="F#" Value="member this.FrontendPortRangeEnd : int with get, set" Usage="Microsoft.Azure.Management.Network.Models.InboundNatPool.FrontendPortRangeEnd" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.frontendPortRangeEnd")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはロード バランサーに関連付けられている Nic に受信の Nat を提供するために使用する外部ポートの範囲の最後のポート番号を設定します。 1 から 65535 までの範囲を指定できる値です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FrontendPortRangeStart">
      <MemberSignature Language="C#" Value="public int FrontendPortRangeStart { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 FrontendPortRangeStart" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.InboundNatPool.FrontendPortRangeStart" />
      <MemberSignature Language="VB.NET" Value="Public Property FrontendPortRangeStart As Integer" />
      <MemberSignature Language="F#" Value="member this.FrontendPortRangeStart : int with get, set" Usage="Microsoft.Azure.Management.Network.Models.InboundNatPool.FrontendPortRangeStart" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.frontendPortRangeStart")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはロード バランサーに関連付けられている Nic に受信の Nat を提供するために使用する外部ポートの範囲の最初のポート番号を設定します。 許容される値の範囲は 1 ~ 65,534 の範囲です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.InboundNatPool.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.InboundNatPool.Name" />
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
    <Member MemberName="Protocol">
      <MemberSignature Language="C#" Value="public string Protocol { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Protocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.InboundNatPool.Protocol" />
      <MemberSignature Language="VB.NET" Value="Public Property Protocol As String" />
      <MemberSignature Language="F#" Value="member this.Protocol : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.InboundNatPool.Protocol" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.InboundNatPool.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.InboundNatPool.ProvisioningState" />
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
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.InboundNatPool.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="inboundNatPool.Validate " />
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
  </Members>
</Type>