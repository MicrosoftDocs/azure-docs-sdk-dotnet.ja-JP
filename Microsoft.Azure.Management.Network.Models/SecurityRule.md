<Type Name="SecurityRule" FullName="Microsoft.Azure.Management.Network.Models.SecurityRule">
  <TypeSignature Language="C#" Value="public class SecurityRule : Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SecurityRule extends Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.SecurityRule" />
  <TypeSignature Language="VB.NET" Value="Public Class SecurityRule&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type SecurityRule = class&#xA;    inherit SubResource" />
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
            ネットワーク セキュリティ規則。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SecurityRule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.SecurityRule.#ctor" />
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
            SecurityRule クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SecurityRule (string protocol, string access, string direction, string id = null, string description = null, string sourcePortRange = null, string destinationPortRange = null, string sourceAddressPrefix = null, System.Collections.Generic.IList&lt;string&gt; sourceAddressPrefixes = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt; sourceApplicationSecurityGroups = null, string destinationAddressPrefix = null, System.Collections.Generic.IList&lt;string&gt; destinationAddressPrefixes = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt; destinationApplicationSecurityGroups = null, System.Collections.Generic.IList&lt;string&gt; sourcePortRanges = null, System.Collections.Generic.IList&lt;string&gt; destinationPortRanges = null, Nullable&lt;int&gt; priority = null, string provisioningState = null, string name = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string protocol, string access, string direction, string id, string description, string sourcePortRange, string destinationPortRange, string sourceAddressPrefix, class System.Collections.Generic.IList`1&lt;string&gt; sourceAddressPrefixes, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt; sourceApplicationSecurityGroups, string destinationAddressPrefix, class System.Collections.Generic.IList`1&lt;string&gt; destinationAddressPrefixes, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt; destinationApplicationSecurityGroups, class System.Collections.Generic.IList`1&lt;string&gt; sourcePortRanges, class System.Collections.Generic.IList`1&lt;string&gt; destinationPortRanges, valuetype System.Nullable`1&lt;int32&gt; priority, string provisioningState, string name, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.SecurityRule.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup},System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup},System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{System.String},System.Nullable{System.Int32},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (protocol As String, access As String, direction As String, Optional id As String = null, Optional description As String = null, Optional sourcePortRange As String = null, Optional destinationPortRange As String = null, Optional sourceAddressPrefix As String = null, Optional sourceAddressPrefixes As IList(Of String) = null, Optional sourceApplicationSecurityGroups As IList(Of ApplicationSecurityGroup) = null, Optional destinationAddressPrefix As String = null, Optional destinationAddressPrefixes As IList(Of String) = null, Optional destinationApplicationSecurityGroups As IList(Of ApplicationSecurityGroup) = null, Optional sourcePortRanges As IList(Of String) = null, Optional destinationPortRanges As IList(Of String) = null, Optional priority As Nullable(Of Integer) = null, Optional provisioningState As String = null, Optional name As String = null, Optional etag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.SecurityRule : string * string * string * string * string * string * string * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt; * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt; * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;int&gt; * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.SecurityRule" Usage="new Microsoft.Azure.Management.Network.Models.SecurityRule (protocol, access, direction, id, description, sourcePortRange, destinationPortRange, sourceAddressPrefix, sourceAddressPrefixes, sourceApplicationSecurityGroups, destinationAddressPrefix, destinationAddressPrefixes, destinationApplicationSecurityGroups, sourcePortRanges, destinationPortRanges, priority, provisioningState, name, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="protocol" Type="System.String" />
        <Parameter Name="access" Type="System.String" />
        <Parameter Name="direction" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="sourcePortRange" Type="System.String" />
        <Parameter Name="destinationPortRange" Type="System.String" />
        <Parameter Name="sourceAddressPrefix" Type="System.String" />
        <Parameter Name="sourceAddressPrefixes" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="sourceApplicationSecurityGroups" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt;" />
        <Parameter Name="destinationAddressPrefix" Type="System.String" />
        <Parameter Name="destinationAddressPrefixes" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="destinationApplicationSecurityGroups" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt;" />
        <Parameter Name="sourcePortRanges" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="destinationPortRanges" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="priority" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="protocol">この規則を適用するネットワーク プロトコルです。
            指定できる値は 'Tcp'、'Udp' および '*' です。使用可能な値が含まれます: 'Tcp'、'Udp'、'*'</param>
        <param name="access">ネットワーク トラフィックが許可または拒否します。
            使用可能な値が: 'Allow' および 'Deny' です。 使用可能な値が含まれます 'の Allow'、'拒否'。</param>
        <param name="direction">ルールの方向です。 方向は、受信または outcoming トラフィック ルールが評価されるかどうかを指定します。 使用可能な値が: '受信' および '送信' です。 使用可能な値が含まれます: '受信'、'送信'</param>
        <param name="id">リソースの ID</param>
        <param name="description">この規則の説明。 140 文字に制限されています。</param>
        <param name="sourcePortRange">発信元ポートまたは範囲。 整数または 0 ~ 65535 の範囲。 アスタリスク ' *' のすべてのポートを一致するようにも使用できます。</param>
        <param name="destinationPortRange">宛先ポートまたは範囲。
            整数または 0 ~ 65535 の範囲。 アスタリスク ' *' のすべてのポートを一致するようにも使用できます。</param>
        <param name="sourceAddressPrefix">CIDR、発信元 IP の範囲です。
            アスタリスク ' *' すべてのソース Ip に一致するようにも使用できます。 既定値は、'VirtualNetwork'、'AzureLoadBalancer' および 'Internet' こともできますなど、タグ付けします。 場合、受信の規則からのネットワーク トラフィックの発生源を指定します。 </param>
        <param name="sourceAddressPrefixes">CIDR、発信元 IP の範囲です。</param>
        <param name="sourceApplicationSecurityGroups">ソースとして指定されたアプリケーションのセキュリティ グループ。</param>
        <param name="destinationAddressPrefix">移行先のアドレス プレフィックス。 CIDR または接続先 IP の範囲。 アスタリスク ' *' すべてのソース Ip に一致するようにも使用できます。 既定値は、'VirtualNetwork'、'AzureLoadBalancer' および 'Internet' こともできますなど、タグ付けします。</param>
        <param name="destinationAddressPrefixes">移行先のアドレス プレフィックス。 CIDR または接続先 IP の範囲です。</param>
        <param name="destinationApplicationSecurityGroups">移行先として指定されたアプリケーションのセキュリティ グループです。</param>
        <param name="sourcePortRanges">ソースのポート範囲です。</param>
        <param name="destinationPortRanges">移行先のポート範囲です。</param>
        <param name="priority">ルールの優先度です。 値は、100 ~ 4096 の範囲指定できます。 優先順位番号は、コレクション内の各規則に対して一意でなければなりません。 優先度番号が低いほど、規則の優先度が高くなります。</param>
        <param name="provisioningState">パブリック IP リソースのプロビジョニングの状態。 使用可能な値が: '更新'、'削除' および '失敗' です。</param>
        <param name="name">リソース グループ内で一意であるリソースの名前。 この名前は、リソースへのアクセスに使用できます。</param>
        <param name="etag">読み取り専用する一意の文字列リソースを更新するたびに変化します。</param>
        <summary>
            SecurityRule クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Access">
      <MemberSignature Language="C#" Value="public string Access { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Access" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.SecurityRule.Access" />
      <MemberSignature Language="VB.NET" Value="Public Property Access As String" />
      <MemberSignature Language="F#" Value="member this.Access : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.SecurityRule.Access" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.access")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、ネットワーク トラフィックを許可または拒否します。 使用可能な値が: 'Allow' および 'Deny' です。 使用可能な値が含まれます 'の Allow'、'拒否'。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.SecurityRule.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.SecurityRule.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.description")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、この規則の説明を設定します。 140 文字に制限されています。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DestinationAddressPrefix">
      <MemberSignature Language="C#" Value="public string DestinationAddressPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DestinationAddressPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.SecurityRule.DestinationAddressPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property DestinationAddressPrefix As String" />
      <MemberSignature Language="F#" Value="member this.DestinationAddressPrefix : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.SecurityRule.DestinationAddressPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.destinationAddressPrefix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または宛先アドレス プレフィックスを設定します。 CIDR または接続先 IP の範囲。 アスタリスク ' *' すべてのソース Ip に一致するようにも使用できます。
            既定値は、'VirtualNetwork'、'AzureLoadBalancer' および 'Internet' こともできますなど、タグ付けします。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DestinationAddressPrefixes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; DestinationAddressPrefixes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; DestinationAddressPrefixes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.SecurityRule.DestinationAddressPrefixes" />
      <MemberSignature Language="VB.NET" Value="Public Property DestinationAddressPrefixes As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.DestinationAddressPrefixes : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.SecurityRule.DestinationAddressPrefixes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.destinationAddressPrefixes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアドレス プレフィックスの送信先を設定します。 CIDR または接続先 IP の範囲です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DestinationApplicationSecurityGroups">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt; DestinationApplicationSecurityGroups { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt; DestinationApplicationSecurityGroups" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.SecurityRule.DestinationApplicationSecurityGroups" />
      <MemberSignature Language="VB.NET" Value="Public Property DestinationApplicationSecurityGroups As IList(Of ApplicationSecurityGroup)" />
      <MemberSignature Language="F#" Value="member this.DestinationApplicationSecurityGroups : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.SecurityRule.DestinationApplicationSecurityGroups" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.destinationApplicationSecurityGroups")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または変換先として指定されたアプリケーションのセキュリティ グループを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DestinationPortRange">
      <MemberSignature Language="C#" Value="public string DestinationPortRange { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DestinationPortRange" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.SecurityRule.DestinationPortRange" />
      <MemberSignature Language="VB.NET" Value="Public Property DestinationPortRange As String" />
      <MemberSignature Language="F#" Value="member this.DestinationPortRange : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.SecurityRule.DestinationPortRange" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.destinationPortRange")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または宛先ポートまたは範囲を設定します。 整数または 0 ~ 65535 の範囲。 アスタリスク ' *' のすべてのポートを一致するようにも使用できます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DestinationPortRanges">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; DestinationPortRanges { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; DestinationPortRanges" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.SecurityRule.DestinationPortRanges" />
      <MemberSignature Language="VB.NET" Value="Public Property DestinationPortRanges As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.DestinationPortRanges : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.SecurityRule.DestinationPortRanges" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.destinationPortRanges")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または送信先のポート範囲を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Direction">
      <MemberSignature Language="C#" Value="public string Direction { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Direction" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.SecurityRule.Direction" />
      <MemberSignature Language="VB.NET" Value="Public Property Direction As String" />
      <MemberSignature Language="F#" Value="member this.Direction : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.SecurityRule.Direction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.direction")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはルールの方向を設定します。 方向は、受信または outcoming トラフィック ルールが評価されるかどうかを指定します。 使用可能な値が: '受信' および '送信' です。 使用可能な値が含まれます: '受信'、'送信'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.SecurityRule.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.SecurityRule.Etag" />
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
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.SecurityRule.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.SecurityRule.Name" />
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
    <Member MemberName="Priority">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Priority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Priority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.SecurityRule.Priority" />
      <MemberSignature Language="VB.NET" Value="Public Property Priority As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Priority : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.SecurityRule.Priority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.priority")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはルールの優先順位を設定します。 値は、100 ~ 4096 の範囲指定できます。 優先順位番号は、コレクション内の各規則に対して一意でなければなりません。 優先度番号が低いほど、規則の優先度が高くなります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Protocol">
      <MemberSignature Language="C#" Value="public string Protocol { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Protocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.SecurityRule.Protocol" />
      <MemberSignature Language="VB.NET" Value="Public Property Protocol As String" />
      <MemberSignature Language="F#" Value="member this.Protocol : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.SecurityRule.Protocol" />
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
            取得または、この規則の適用先のネットワーク プロトコルを設定します。 指定できる値は 'Tcp'、'Udp' および '*' です。使用可能な値が含まれます: 'Tcp'、'Udp'、'*'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.SecurityRule.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.SecurityRule.ProvisioningState" />
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
    <Member MemberName="SourceAddressPrefix">
      <MemberSignature Language="C#" Value="public string SourceAddressPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceAddressPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.SecurityRule.SourceAddressPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceAddressPrefix As String" />
      <MemberSignature Language="F#" Value="member this.SourceAddressPrefix : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.SecurityRule.SourceAddressPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sourceAddressPrefix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または CIDR、発信元 IP の範囲を設定します。 アスタリスク ' *' すべてのソース Ip に一致するようにも使用できます。 既定値は、'VirtualNetwork'、'AzureLoadBalancer' および 'Internet' こともできますなど、タグ付けします。 場合、受信の規則からのネットワーク トラフィックの発生源を指定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceAddressPrefixes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; SourceAddressPrefixes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; SourceAddressPrefixes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.SecurityRule.SourceAddressPrefixes" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceAddressPrefixes As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.SourceAddressPrefixes : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.SecurityRule.SourceAddressPrefixes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sourceAddressPrefixes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または CIDR、発信元 IP の範囲を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceApplicationSecurityGroups">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt; SourceApplicationSecurityGroups { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt; SourceApplicationSecurityGroups" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.SecurityRule.SourceApplicationSecurityGroups" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceApplicationSecurityGroups As IList(Of ApplicationSecurityGroup)" />
      <MemberSignature Language="F#" Value="member this.SourceApplicationSecurityGroups : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.SecurityRule.SourceApplicationSecurityGroups" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sourceApplicationSecurityGroups")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはソースとして指定されたアプリケーションのセキュリティ グループを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourcePortRange">
      <MemberSignature Language="C#" Value="public string SourcePortRange { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourcePortRange" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.SecurityRule.SourcePortRange" />
      <MemberSignature Language="VB.NET" Value="Public Property SourcePortRange As String" />
      <MemberSignature Language="F#" Value="member this.SourcePortRange : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.SecurityRule.SourcePortRange" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sourcePortRange")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または送信元ポートまたは範囲を設定します。 整数または 0 ~ 65535 の範囲。 アスタリスク ' *' のすべてのポートを一致するようにも使用できます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourcePortRanges">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; SourcePortRanges { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; SourcePortRanges" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.SecurityRule.SourcePortRanges" />
      <MemberSignature Language="VB.NET" Value="Public Property SourcePortRanges As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.SourcePortRanges : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.SecurityRule.SourcePortRanges" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sourcePortRanges")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはソース ポート範囲を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.SecurityRule.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="securityRule.Validate " />
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