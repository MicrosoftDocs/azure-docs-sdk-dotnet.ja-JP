<Type Name="HiveLinkedService" FullName="Microsoft.Azure.Management.DataFactory.Models.HiveLinkedService">
  <TypeSignature Language="C#" Value="public class HiveLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HiveLinkedService extends Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.HiveLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class HiveLinkedService&#xA;Inherits LinkedService" />
  <TypeSignature Language="F#" Value="type HiveLinkedService = class&#xA;    inherit LinkedService" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.LinkedService</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Hive")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            リンクされたサービスを hive します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HiveLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.HiveLinkedService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            HiveLinkedService クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HiveLinkedService (object host, string authenticationType, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia = null, string description = null, object port = null, string serverType = null, string thriftTransportProtocol = null, object serviceDiscoveryMode = null, object zooKeeperNameSpace = null, object useNativeQuery = null, object username = null, Microsoft.Azure.Management.DataFactory.Models.SecretBase password = null, object httpPath = null, object enableSsl = null, object trustedCertPath = null, object useSystemTrustStore = null, object allowHostNameCNMismatch = null, object allowSelfSignedServerCert = null, object encryptedCredential = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object host, string authenticationType, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia, string description, object port, string serverType, string thriftTransportProtocol, object serviceDiscoveryMode, object zooKeeperNameSpace, object useNativeQuery, object username, class Microsoft.Azure.Management.DataFactory.Models.SecretBase password, object httpPath, object enableSsl, object trustedCertPath, object useSystemTrustStore, object allowHostNameCNMismatch, object allowSelfSignedServerCert, object encryptedCredential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.HiveLinkedService.#ctor(System.Object,System.String,System.Collections.Generic.IDictionary{System.String,System.Object},Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference,System.String,System.Object,System.String,System.String,System.Object,System.Object,System.Object,System.Object,Microsoft.Azure.Management.DataFactory.Models.SecretBase,System.Object,System.Object,System.Object,System.Object,System.Object,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (host As Object, authenticationType As String, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional connectVia As IntegrationRuntimeReference = null, Optional description As String = null, Optional port As Object = null, Optional serverType As String = null, Optional thriftTransportProtocol As String = null, Optional serviceDiscoveryMode As Object = null, Optional zooKeeperNameSpace As Object = null, Optional useNativeQuery As Object = null, Optional username As Object = null, Optional password As SecretBase = null, Optional httpPath As Object = null, Optional enableSsl As Object = null, Optional trustedCertPath As Object = null, Optional useSystemTrustStore As Object = null, Optional allowHostNameCNMismatch As Object = null, Optional allowSelfSignedServerCert As Object = null, Optional encryptedCredential As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.HiveLinkedService : obj * string * System.Collections.Generic.IDictionary&lt;string, obj&gt; * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference * string * obj * string * string * obj * obj * obj * obj * Microsoft.Azure.Management.DataFactory.Models.SecretBase * obj * obj * obj * obj * obj * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.HiveLinkedService" Usage="new Microsoft.Azure.Management.DataFactory.Models.HiveLinkedService (host, authenticationType, additionalProperties, connectVia, description, port, serverType, thriftTransportProtocol, serviceDiscoveryMode, zooKeeperNameSpace, useNativeQuery, username, password, httpPath, enableSsl, trustedCertPath, useSystemTrustStore, allowHostNameCNMismatch, allowSelfSignedServerCert, encryptedCredential)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="host" Type="System.Object" />
        <Parameter Name="authenticationType" Type="System.String" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="connectVia" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="port" Type="System.Object" />
        <Parameter Name="serverType" Type="System.String" />
        <Parameter Name="thriftTransportProtocol" Type="System.String" />
        <Parameter Name="serviceDiscoveryMode" Type="System.Object" />
        <Parameter Name="zooKeeperNameSpace" Type="System.Object" />
        <Parameter Name="useNativeQuery" Type="System.Object" />
        <Parameter Name="username" Type="System.Object" />
        <Parameter Name="password" Type="Microsoft.Azure.Management.DataFactory.Models.SecretBase" />
        <Parameter Name="httpPath" Type="System.Object" />
        <Parameter Name="enableSsl" Type="System.Object" />
        <Parameter Name="trustedCertPath" Type="System.Object" />
        <Parameter Name="useSystemTrustStore" Type="System.Object" />
        <Parameter Name="allowHostNameCNMismatch" Type="System.Object" />
        <Parameter Name="allowSelfSignedServerCert" Type="System.Object" />
        <Parameter Name="encryptedCredential" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="host">Hive サーバーの IP アドレスまたはホスト名。複数のホストは ';' で区切ります (serviceDiscoveryMode が有効な場合のみ)。</param>
        <param name="authenticationType">Hive サーバーへのアクセスに使用する認証方法。 使用可能な値が含まれます 'Anonymous'、'Username' が 'UsernameAndPassword'、'WindowsAzureHDInsightService'。</param>
        <param name="additionalProperties">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</param>
        <param name="connectVia">統合のランタイム参照。</param>
        <param name="description">リンクされたサービスの説明。</param>
        <param name="port">Hive サーバーがクライアント接続のリッスンに使用する TCP ポート。</param>
        <param name="serverType">Hive サーバーの種類。 使用可能な値が含まれます: 'HiveServer1'、'HiveServer2'、'HiveThriftServer'</param>
        <param name="thriftTransportProtocol">Thrift レイヤーで使用するトランスポート プロトコル。 使用可能な値が含まれます: 'Binary'、'SASL'、'HTTP'</param>
        <param name="serviceDiscoveryMode">ZooKeeper サービスの使用を指定する場合は true、そうでない場合は false。</param>
        <param name="zooKeeperNameSpace">Hive サーバーの 2 ノードが追加される ZooKeeper 上の名前空間。</param>
        <param name="useNativeQuery">ドライバーがネイティブの HiveQL クエリを使用するか、または HiveQL の同等の形式に変換するかを指定します。</param>
        <param name="username">Hive サーバーへのアクセスに使用するユーザー名。</param>
        <param name="password">ユーザー名 フィールドで指定したユーザー名に対応するパスワード</param>
        <param name="httpPath">Hive サーバーに対応する部分的な URL。</param>
        <param name="enableSsl">SSL を使用して、サーバーへの接続を暗号化するかどうかを指定します。 既定値は false です。</param>
        <param name="trustedCertPath">SSL 経由で接続するときにサーバーを検証するための信頼された CA 証明書を含む .pem ファイルの完全なパス。 このプロパティは、セルフホステッド IR で SSL を使用する場合にのみ設定できます。 既定値は、IR でインストールされる cacerts.pem ファイルです。</param>
        <param name="useSystemTrustStore">システムの信頼ストアと指定した PEM ファイルのどちらの CA 証明書を使用するかを指定します。 既定値は false です。</param>
        <param name="allowHostNameCNMismatch">SSL 経由で接続するときに、CA が発行した SSL 証明書名がサーバーのホスト名と一致する必要があるかどうかを指定します。 既定値は false です。</param>
        <param name="allowSelfSignedServerCert">サーバーからの自己署名証明書を許可するかどうかを指定します。 既定値は false です。</param>
        <param name="encryptedCredential">暗号化された資格情報の認証に使用します。 資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。 型: 文字列 (または式の resultType 文字列)。</param>
        <summary>
            HiveLinkedService クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowHostNameCNMismatch">
      <MemberSignature Language="C#" Value="public object AllowHostNameCNMismatch { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object AllowHostNameCNMismatch" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HiveLinkedService.AllowHostNameCNMismatch" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowHostNameCNMismatch As Object" />
      <MemberSignature Language="F#" Value="member this.AllowHostNameCNMismatch : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HiveLinkedService.AllowHostNameCNMismatch" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.allowHostNameCNMismatch")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、SSL 経由で接続するときに、サーバーのホスト名を一致するように CA から発行される SSL 証明書名を必要とするかどうかを指定します。 既定値は false です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowSelfSignedServerCert">
      <MemberSignature Language="C#" Value="public object AllowSelfSignedServerCert { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object AllowSelfSignedServerCert" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HiveLinkedService.AllowSelfSignedServerCert" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowSelfSignedServerCert As Object" />
      <MemberSignature Language="F#" Value="member this.AllowSelfSignedServerCert : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HiveLinkedService.AllowSelfSignedServerCert" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.allowSelfSignedServerCert")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、サーバーから自己署名証明書を許可するかどうかを指定します。 既定値は false です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationType">
      <MemberSignature Language="C#" Value="public string AuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HiveLinkedService.AuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationType As String" />
      <MemberSignature Language="F#" Value="member this.AuthenticationType : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HiveLinkedService.AuthenticationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.authenticationType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Hive サーバーへのアクセスに使用する認証方法を設定します。 使用可能な値が含まれます 'Anonymous'、'Username' が 'UsernameAndPassword'、'WindowsAzureHDInsightService'。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableSsl">
      <MemberSignature Language="C#" Value="public object EnableSsl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EnableSsl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HiveLinkedService.EnableSsl" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableSsl As Object" />
      <MemberSignature Language="F#" Value="member this.EnableSsl : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HiveLinkedService.EnableSsl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.enableSsl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、SSL を使用して、サーバーへの接続を暗号化するかどうかを指定します。 既定値は false です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptedCredential">
      <MemberSignature Language="C#" Value="public object EncryptedCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EncryptedCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HiveLinkedService.EncryptedCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptedCredential As Object" />
      <MemberSignature Language="F#" Value="member this.EncryptedCredential : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HiveLinkedService.EncryptedCredential" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.encryptedCredential")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または認証に使用される暗号化された資格情報を設定します。
            資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。 型: 文字列 (または式の resultType 文字列)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Host">
      <MemberSignature Language="C#" Value="public object Host { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Host" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HiveLinkedService.Host" />
      <MemberSignature Language="VB.NET" Value="Public Property Host As Object" />
      <MemberSignature Language="F#" Value="member this.Host : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HiveLinkedService.Host" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.host")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または (だけ serviceDiscoveryMode が有効である場合) の複数のホストに ';' での区切られた、Hive サーバーの IP アドレスまたはホスト名を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpPath">
      <MemberSignature Language="C#" Value="public object HttpPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object HttpPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HiveLinkedService.HttpPath" />
      <MemberSignature Language="VB.NET" Value="Public Property HttpPath As Object" />
      <MemberSignature Language="F#" Value="member this.HttpPath : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HiveLinkedService.HttpPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.httpPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Hive サーバーに対応する部分の URL を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecretBase Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecretBase Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HiveLinkedService.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As SecretBase" />
      <MemberSignature Language="F#" Value="member this.Password : Microsoft.Azure.Management.DataFactory.Models.SecretBase with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HiveLinkedService.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.password")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.SecretBase</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはユーザー名 フィールドで指定したユーザー名に対応するパスワードを設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Port">
      <MemberSignature Language="C#" Value="public object Port { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Port" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HiveLinkedService.Port" />
      <MemberSignature Language="VB.NET" Value="Public Property Port As Object" />
      <MemberSignature Language="F#" Value="member this.Port : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HiveLinkedService.Port" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.port")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Hive サーバーがクライアント接続のリッスンに使用される TCP ポートを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerType">
      <MemberSignature Language="C#" Value="public string ServerType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServerType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HiveLinkedService.ServerType" />
      <MemberSignature Language="VB.NET" Value="Public Property ServerType As String" />
      <MemberSignature Language="F#" Value="member this.ServerType : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HiveLinkedService.ServerType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.serverType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Hive サーバーの種類を設定します。 使用可能な値が含まれます: 'HiveServer1'、'HiveServer2'、'HiveThriftServer'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceDiscoveryMode">
      <MemberSignature Language="C#" Value="public object ServiceDiscoveryMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object ServiceDiscoveryMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HiveLinkedService.ServiceDiscoveryMode" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceDiscoveryMode As Object" />
      <MemberSignature Language="F#" Value="member this.ServiceDiscoveryMode : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HiveLinkedService.ServiceDiscoveryMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.serviceDiscoveryMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、サービスを使用して、飼育、false いないを示すために true です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ThriftTransportProtocol">
      <MemberSignature Language="C#" Value="public string ThriftTransportProtocol { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ThriftTransportProtocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HiveLinkedService.ThriftTransportProtocol" />
      <MemberSignature Language="VB.NET" Value="Public Property ThriftTransportProtocol As String" />
      <MemberSignature Language="F#" Value="member this.ThriftTransportProtocol : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HiveLinkedService.ThriftTransportProtocol" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.thriftTransportProtocol")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Thrift レイヤーを使用するトランスポート プロトコルを設定します。
            使用可能な値が含まれます: 'Binary'、'SASL'、'HTTP'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrustedCertPath">
      <MemberSignature Language="C#" Value="public object TrustedCertPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object TrustedCertPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HiveLinkedService.TrustedCertPath" />
      <MemberSignature Language="VB.NET" Value="Public Property TrustedCertPath As Object" />
      <MemberSignature Language="F#" Value="member this.TrustedCertPath : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HiveLinkedService.TrustedCertPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.trustedCertPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または SSL 経由で接続するときに、サーバーを検証するための信頼された CA 証明書を含む .pem ファイルの完全パスを設定します。
            このプロパティは、セルフホステッド IR で SSL を使用する場合にのみ設定できます。 既定値は、IR でインストールされる cacerts.pem ファイルです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseNativeQuery">
      <MemberSignature Language="C#" Value="public object UseNativeQuery { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object UseNativeQuery" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HiveLinkedService.UseNativeQuery" />
      <MemberSignature Language="VB.NET" Value="Public Property UseNativeQuery As Object" />
      <MemberSignature Language="F#" Value="member this.UseNativeQuery : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HiveLinkedService.UseNativeQuery" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.useNativeQuery")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、ドライバーがネイティブの HiveQL クエリを使用または HiveQL 内と同等の形式に変換するかどうかを指定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Username">
      <MemberSignature Language="C#" Value="public object Username { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Username" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HiveLinkedService.Username" />
      <MemberSignature Language="VB.NET" Value="Public Property Username As Object" />
      <MemberSignature Language="F#" Value="member this.Username : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HiveLinkedService.Username" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.username")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Hive サーバーへのアクセスに使用するユーザー名を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseSystemTrustStore">
      <MemberSignature Language="C#" Value="public object UseSystemTrustStore { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object UseSystemTrustStore" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HiveLinkedService.UseSystemTrustStore" />
      <MemberSignature Language="VB.NET" Value="Public Property UseSystemTrustStore As Object" />
      <MemberSignature Language="F#" Value="member this.UseSystemTrustStore : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HiveLinkedService.UseSystemTrustStore" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.useSystemTrustStore")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、システムのトラスト ストアから、または指定した PEM ファイルから CA 証明書を使用するかどうかを指定します。 既定値は false です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.HiveLinkedService.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="hiveLinkedService.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
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
    <Member MemberName="ZooKeeperNameSpace">
      <MemberSignature Language="C#" Value="public object ZooKeeperNameSpace { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object ZooKeeperNameSpace" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HiveLinkedService.ZooKeeperNameSpace" />
      <MemberSignature Language="VB.NET" Value="Public Property ZooKeeperNameSpace As Object" />
      <MemberSignature Language="F#" Value="member this.ZooKeeperNameSpace : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HiveLinkedService.ZooKeeperNameSpace" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.zooKeeperNameSpace")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または飼育 Hive サーバー 2 ノードを追加するには名前空間を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>