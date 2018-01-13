<Type Name="SparkLinkedService" FullName="Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService">
  <TypeSignature Language="C#" Value="public class SparkLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SparkLinkedService extends Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class SparkLinkedService&#xA;Inherits LinkedService" />
  <TypeSignature Language="F#" Value="type SparkLinkedService = class&#xA;    inherit LinkedService" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("Spark")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Spark サーバーにリンクされたサービスを指定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SparkLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            SparkLinkedService クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SparkLinkedService (object host, object port, string authenticationType, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia = null, string description = null, string serverType = null, string thriftTransportProtocol = null, object username = null, Microsoft.Azure.Management.DataFactory.Models.SecretBase password = null, object httpPath = null, object enableSsl = null, object trustedCertPath = null, object useSystemTrustStore = null, object allowHostNameCNMismatch = null, object allowSelfSignedServerCert = null, object encryptedCredential = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object host, object port, string authenticationType, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia, string description, string serverType, string thriftTransportProtocol, object username, class Microsoft.Azure.Management.DataFactory.Models.SecretBase password, object httpPath, object enableSsl, object trustedCertPath, object useSystemTrustStore, object allowHostNameCNMismatch, object allowSelfSignedServerCert, object encryptedCredential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.#ctor(System.Object,System.Object,System.String,System.Collections.Generic.IDictionary{System.String,System.Object},Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference,System.String,System.String,System.String,System.Object,Microsoft.Azure.Management.DataFactory.Models.SecretBase,System.Object,System.Object,System.Object,System.Object,System.Object,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (host As Object, port As Object, authenticationType As String, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional connectVia As IntegrationRuntimeReference = null, Optional description As String = null, Optional serverType As String = null, Optional thriftTransportProtocol As String = null, Optional username As Object = null, Optional password As SecretBase = null, Optional httpPath As Object = null, Optional enableSsl As Object = null, Optional trustedCertPath As Object = null, Optional useSystemTrustStore As Object = null, Optional allowHostNameCNMismatch As Object = null, Optional allowSelfSignedServerCert As Object = null, Optional encryptedCredential As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService : obj * obj * string * System.Collections.Generic.IDictionary&lt;string, obj&gt; * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference * string * string * string * obj * Microsoft.Azure.Management.DataFactory.Models.SecretBase * obj * obj * obj * obj * obj * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService" Usage="new Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService (host, port, authenticationType, additionalProperties, connectVia, description, serverType, thriftTransportProtocol, username, password, httpPath, enableSsl, trustedCertPath, useSystemTrustStore, allowHostNameCNMismatch, allowSelfSignedServerCert, encryptedCredential)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="host" Type="System.Object" />
        <Parameter Name="port" Type="System.Object" />
        <Parameter Name="authenticationType" Type="System.String" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="connectVia" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="serverType" Type="System.String" />
        <Parameter Name="thriftTransportProtocol" Type="System.String" />
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
        <param name="host">Spark サーバーの IP アドレスまたはホスト名</param>
        <param name="port">Spark サーバーがクライアント接続のリッスンに使用する TCP ポート。</param>
        <param name="authenticationType">Spark サーバーへのアクセスに使用する認証方法。 使用可能な値が含まれます 'Anonymous'、'Username' が 'UsernameAndPassword'、'WindowsAzureHDInsightService'。</param>
        <param name="additionalProperties">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</param>
        <param name="connectVia">統合のランタイム参照。</param>
        <param name="description">リンクされたサービスの説明。</param>
        <param name="serverType">Spark サーバーの種類。 使用可能な値が含まれます: 'SharkServer'、'SharkServer2'、'SparkThriftServer'</param>
        <param name="thriftTransportProtocol">Thrift レイヤーで使用するトランスポート プロトコル。 使用可能な値が含まれます: 'Binary'、'SASL'、'HTTP'</param>
        <param name="username">Spark サーバーへのアクセスに使用するユーザー名。</param>
        <param name="password">ユーザー名 フィールドで指定したユーザー名に対応するパスワード</param>
        <param name="httpPath">Spark サーバーに対応する部分的な URL。</param>
        <param name="enableSsl">SSL を使用して、サーバーへの接続を暗号化するかどうかを指定します。 既定値は false です。</param>
        <param name="trustedCertPath">SSL 経由で接続するときにサーバーを検証するための信頼された CA 証明書を含む .pem ファイルの完全なパス。 このプロパティは、セルフホステッド IR で SSL を使用する場合にのみ設定できます。 既定値は、IR でインストールされる cacerts.pem ファイルです。</param>
        <param name="useSystemTrustStore">システムの信頼ストアと指定した PEM ファイルのどちらの CA 証明書を使用するかを指定します。 既定値は false です。</param>
        <param name="allowHostNameCNMismatch">SSL 経由で接続するときに、CA が発行した SSL 証明書名がサーバーのホスト名と一致する必要があるかどうかを指定します。 既定値は false です。</param>
        <param name="allowSelfSignedServerCert">サーバーからの自己署名証明書を許可するかどうかを指定します。 既定値は false です。</param>
        <param name="encryptedCredential">暗号化された資格情報の認証に使用します。 資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。 型: 文字列 (または式の resultType 文字列)。</param>
        <summary>
            SparkLinkedService クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowHostNameCNMismatch">
      <MemberSignature Language="C#" Value="public object AllowHostNameCNMismatch { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object AllowHostNameCNMismatch" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.AllowHostNameCNMismatch" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowHostNameCNMismatch As Object" />
      <MemberSignature Language="F#" Value="member this.AllowHostNameCNMismatch : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.AllowHostNameCNMismatch" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.AllowSelfSignedServerCert" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowSelfSignedServerCert As Object" />
      <MemberSignature Language="F#" Value="member this.AllowSelfSignedServerCert : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.AllowSelfSignedServerCert" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.AuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationType As String" />
      <MemberSignature Language="F#" Value="member this.AuthenticationType : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.AuthenticationType" />
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
            取得または Spark サーバーへのアクセスに使用する認証方法を設定します。 使用可能な値が含まれます 'Anonymous'、'Username' が 'UsernameAndPassword'、'WindowsAzureHDInsightService'。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableSsl">
      <MemberSignature Language="C#" Value="public object EnableSsl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EnableSsl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.EnableSsl" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableSsl As Object" />
      <MemberSignature Language="F#" Value="member this.EnableSsl : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.EnableSsl" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.EncryptedCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptedCredential As Object" />
      <MemberSignature Language="F#" Value="member this.EncryptedCredential : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.EncryptedCredential" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.Host" />
      <MemberSignature Language="VB.NET" Value="Public Property Host As Object" />
      <MemberSignature Language="F#" Value="member this.Host : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.Host" />
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
            取得または設定、Spark サーバーの IP アドレスまたはホスト名
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpPath">
      <MemberSignature Language="C#" Value="public object HttpPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object HttpPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.HttpPath" />
      <MemberSignature Language="VB.NET" Value="Public Property HttpPath As Object" />
      <MemberSignature Language="F#" Value="member this.HttpPath : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.HttpPath" />
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
            取得または Spark サーバーに対応する部分的な URL を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecretBase Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecretBase Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As SecretBase" />
      <MemberSignature Language="F#" Value="member this.Password : Microsoft.Azure.Management.DataFactory.Models.SecretBase with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.Password" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.Port" />
      <MemberSignature Language="VB.NET" Value="Public Property Port As Object" />
      <MemberSignature Language="F#" Value="member this.Port : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.Port" />
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
            取得または Spark サーバーがクライアント接続のリッスンに使用される TCP ポートを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerType">
      <MemberSignature Language="C#" Value="public string ServerType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServerType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.ServerType" />
      <MemberSignature Language="VB.NET" Value="Public Property ServerType As String" />
      <MemberSignature Language="F#" Value="member this.ServerType : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.ServerType" />
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
            取得または Spark サーバーの種類を設定します。 使用可能な値が含まれます: 'SharkServer'、'SharkServer2'、'SparkThriftServer'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ThriftTransportProtocol">
      <MemberSignature Language="C#" Value="public string ThriftTransportProtocol { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ThriftTransportProtocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.ThriftTransportProtocol" />
      <MemberSignature Language="VB.NET" Value="Public Property ThriftTransportProtocol As String" />
      <MemberSignature Language="F#" Value="member this.ThriftTransportProtocol : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.ThriftTransportProtocol" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.TrustedCertPath" />
      <MemberSignature Language="VB.NET" Value="Public Property TrustedCertPath As Object" />
      <MemberSignature Language="F#" Value="member this.TrustedCertPath : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.TrustedCertPath" />
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
    <Member MemberName="Username">
      <MemberSignature Language="C#" Value="public object Username { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Username" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.Username" />
      <MemberSignature Language="VB.NET" Value="Public Property Username As Object" />
      <MemberSignature Language="F#" Value="member this.Username : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.Username" />
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
            取得または Spark サーバーへのアクセスに使用するユーザー名を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseSystemTrustStore">
      <MemberSignature Language="C#" Value="public object UseSystemTrustStore { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object UseSystemTrustStore" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.UseSystemTrustStore" />
      <MemberSignature Language="VB.NET" Value="Public Property UseSystemTrustStore As Object" />
      <MemberSignature Language="F#" Value="member this.UseSystemTrustStore : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.UseSystemTrustStore" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="sparkLinkedService.Validate " />
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
  </Members>
</Type>