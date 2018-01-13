<Type Name="ApplicationGatewayProbe" FullName="Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe">
  <TypeSignature Language="C#" Value="public class ApplicationGatewayProbe : Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationGatewayProbe extends Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationGatewayProbe&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type ApplicationGatewayProbe = class&#xA;    inherit SubResource" />
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
            アプリケーション ゲートウェイをプローブします。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewayProbe ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.#ctor" />
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
            ApplicationGatewayProbe クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewayProbe (string id = null, string protocol = null, string host = null, string path = null, Nullable&lt;int&gt; interval = null, Nullable&lt;int&gt; timeout = null, Nullable&lt;int&gt; unhealthyThreshold = null, Nullable&lt;bool&gt; pickHostNameFromBackendHttpSettings = null, Nullable&lt;int&gt; minServers = null, Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbeHealthResponseMatch match = null, string provisioningState = null, string name = null, string etag = null, string type = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string protocol, string host, string path, valuetype System.Nullable`1&lt;int32&gt; interval, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;int32&gt; unhealthyThreshold, valuetype System.Nullable`1&lt;bool&gt; pickHostNameFromBackendHttpSettings, valuetype System.Nullable`1&lt;int32&gt; minServers, class Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbeHealthResponseMatch match, string provisioningState, string name, string etag, string type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.#ctor(System.String,System.String,System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Boolean},System.Nullable{System.Int32},Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbeHealthResponseMatch,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional protocol As String = null, Optional host As String = null, Optional path As String = null, Optional interval As Nullable(Of Integer) = null, Optional timeout As Nullable(Of Integer) = null, Optional unhealthyThreshold As Nullable(Of Integer) = null, Optional pickHostNameFromBackendHttpSettings As Nullable(Of Boolean) = null, Optional minServers As Nullable(Of Integer) = null, Optional match As ApplicationGatewayProbeHealthResponseMatch = null, Optional provisioningState As String = null, Optional name As String = null, Optional etag As String = null, Optional type As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe : string * string * string * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;bool&gt; * Nullable&lt;int&gt; * Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbeHealthResponseMatch * string * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe" Usage="new Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe (id, protocol, host, path, interval, timeout, unhealthyThreshold, pickHostNameFromBackendHttpSettings, minServers, match, provisioningState, name, etag, type)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="protocol" Type="System.String" />
        <Parameter Name="host" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="interval" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="unhealthyThreshold" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="pickHostNameFromBackendHttpSettings" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="minServers" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="match" Type="Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbeHealthResponseMatch" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">リソースの ID</param>
        <param name="protocol">プロトコルです。 使用可能な値が含まれます 'Http'、'Https'。</param>
        <param name="host">送信するプローブ ホスト名です。</param>
        <param name="path">プローブの相対パス。 有効なパスを開始 '/' です。 プローブに送信される&lt;プロトコル&gt;://&lt;ホスト&gt;:&lt;ポート&gt;&lt;パス&gt;</param>
        <param name="interval">プローブ間隔 (秒)。 2 つの連続するプローブの時間間隔。 使用可能な値は、1 秒 ~ 86400 秒です。</param>
        <param name="timeout">プローブのタイムアウト (秒)。 プローブは、このタイムアウト期間の有効な応答が受信されない場合を失敗としてマークされます。
            使用可能な値は、1 秒 ~ 86400 秒です。</param>
        <param name="unhealthyThreshold">プローブの再試行回数です。 バックエンド サーバーは、連続するプローブに失敗した回数 UnhealthyThreshold に到達した後、ダウンをマークされます。 許容される値は、1 秒です。
            20.</param>
        <param name="pickHostNameFromBackendHttpSettings">かどうか、ホスト ヘッダーは、バックエンド http 設定から選択する必要があります。 既定値は false です。</param>
        <param name="minServers">常に正常な状態マークされているサーバーの最小数。 既定値は 0 です。</param>
        <param name="match">異常な状態のプローブ応答を分類するための条件です。</param>
        <param name="provisioningState">バックエンド http 設定リソースのプロビジョニング状態。 使用可能な値が: '更新'、'削除' および '失敗' です。</param>
        <param name="name">リソース グループ内で一意であるリソースの名前です。 この名前は、リソースへのアクセスに使用できます。</param>
        <param name="etag">読み取り専用する一意の文字列リソースを更新するたびに変化します。</param>
        <param name="type">リソースの種類。</param>
        <summary>
            ApplicationGatewayProbe クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.Etag" />
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
    <Member MemberName="Host">
      <MemberSignature Language="C#" Value="public string Host { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Host" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.Host" />
      <MemberSignature Language="VB.NET" Value="Public Property Host As String" />
      <MemberSignature Language="F#" Value="member this.Host : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.Host" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.host")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定するプローブを送信するホスト名。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Interval">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Interval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Interval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.Interval" />
      <MemberSignature Language="VB.NET" Value="Public Property Interval As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Interval : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.Interval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.interval")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプローブの間隔を秒単位で設定します。 2 つの連続するプローブの時間間隔。 使用可能な値は、1 秒 ~ 86400 秒です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Match">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbeHealthResponseMatch Match { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbeHealthResponseMatch Match" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.Match" />
      <MemberSignature Language="VB.NET" Value="Public Property Match As ApplicationGatewayProbeHealthResponseMatch" />
      <MemberSignature Language="F#" Value="member this.Match : Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbeHealthResponseMatch with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.Match" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.match")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbeHealthResponseMatch</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または異常な状態のプローブ応答を分類するための条件を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinServers">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MinServers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MinServers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.MinServers" />
      <MemberSignature Language="VB.NET" Value="Public Property MinServers As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MinServers : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.MinServers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.minServers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または常に正常な状態マークされているサーバーの最小数を設定します。 既定値は 0 です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.Name" />
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
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.Path" />
      <MemberSignature Language="VB.NET" Value="Public Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.path")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプローブの相対パスを設定します。 有効なパスを開始 '/' です。
            プローブに送信される&amp;lt;プロトコル&amp;gt;://&amp;lt; ホスト&amp;gt;:&amp;lt; port&amp;gt;&amp;lt; パス&amp;gt;
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PickHostNameFromBackendHttpSettings">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; PickHostNameFromBackendHttpSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; PickHostNameFromBackendHttpSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.PickHostNameFromBackendHttpSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property PickHostNameFromBackendHttpSettings As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.PickHostNameFromBackendHttpSettings : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.PickHostNameFromBackendHttpSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.pickHostNameFromBackendHttpSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはバックエンド http 設定から、ホスト ヘッダーを選択する必要があるかどうかを設定します。 既定値は false です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Protocol">
      <MemberSignature Language="C#" Value="public string Protocol { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Protocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.Protocol" />
      <MemberSignature Language="VB.NET" Value="Public Property Protocol As String" />
      <MemberSignature Language="F#" Value="member this.Protocol : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.Protocol" />
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
            プロトコル取得または設定します。 使用可能な値が含まれます 'Http'、'Https'。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.ProvisioningState" />
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
            取得またはバックエンド http 設定リソースのプロビジョニング状態を設定します。 使用可能な値が: '更新'、'削除' および '失敗' です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Timeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Timeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.Timeout" />
      <MemberSignature Language="VB.NET" Value="Public Property Timeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Timeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.Timeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.timeout")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプローブのタイムアウトを秒単位で設定します。 プローブは、このタイムアウト期間の有効な応答が受信されない場合を失敗としてマークされます。
            使用可能な値は、1 秒 ~ 86400 秒です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはリソースの種類を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnhealthyThreshold">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; UnhealthyThreshold { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; UnhealthyThreshold" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.UnhealthyThreshold" />
      <MemberSignature Language="VB.NET" Value="Public Property UnhealthyThreshold As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.UnhealthyThreshold : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.UnhealthyThreshold" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.unhealthyThreshold")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプローブの再試行回数を設定します。 バックエンド サーバーは、連続するプローブに失敗した回数 UnhealthyThreshold に到達した後、ダウンをマークされます。
            使用可能な値は、1 秒 ~ 20 です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>