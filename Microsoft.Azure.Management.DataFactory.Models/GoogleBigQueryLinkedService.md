<Type Name="GoogleBigQueryLinkedService" FullName="Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService">
  <TypeSignature Language="C#" Value="public class GoogleBigQueryLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit GoogleBigQueryLinkedService extends Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class GoogleBigQueryLinkedService&#xA;Inherits LinkedService" />
  <TypeSignature Language="F#" Value="type GoogleBigQueryLinkedService = class&#xA;    inherit LinkedService" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("GoogleBigQuery")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Google BigQuery サービス リンクされたサービスを提供します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GoogleBigQueryLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            GoogleBigQueryLinkedService クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GoogleBigQueryLinkedService (object project, string authenticationType, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia = null, string description = null, object additionalProjects = null, object requestGoogleDriveScope = null, Microsoft.Azure.Management.DataFactory.Models.SecretBase refreshToken = null, object email = null, object keyFilePath = null, object trustedCertPath = null, object useSystemTrustStore = null, object encryptedCredential = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object project, string authenticationType, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia, string description, object additionalProjects, object requestGoogleDriveScope, class Microsoft.Azure.Management.DataFactory.Models.SecretBase refreshToken, object email, object keyFilePath, object trustedCertPath, object useSystemTrustStore, object encryptedCredential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService.#ctor(System.Object,System.String,System.Collections.Generic.IDictionary{System.String,System.Object},Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference,System.String,System.Object,System.Object,Microsoft.Azure.Management.DataFactory.Models.SecretBase,System.Object,System.Object,System.Object,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (project As Object, authenticationType As String, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional connectVia As IntegrationRuntimeReference = null, Optional description As String = null, Optional additionalProjects As Object = null, Optional requestGoogleDriveScope As Object = null, Optional refreshToken As SecretBase = null, Optional email As Object = null, Optional keyFilePath As Object = null, Optional trustedCertPath As Object = null, Optional useSystemTrustStore As Object = null, Optional encryptedCredential As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService : obj * string * System.Collections.Generic.IDictionary&lt;string, obj&gt; * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference * string * obj * obj * Microsoft.Azure.Management.DataFactory.Models.SecretBase * obj * obj * obj * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService" Usage="new Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService (project, authenticationType, additionalProperties, connectVia, description, additionalProjects, requestGoogleDriveScope, refreshToken, email, keyFilePath, trustedCertPath, useSystemTrustStore, encryptedCredential)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="project" Type="System.Object" />
        <Parameter Name="authenticationType" Type="System.String" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="connectVia" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="additionalProjects" Type="System.Object" />
        <Parameter Name="requestGoogleDriveScope" Type="System.Object" />
        <Parameter Name="refreshToken" Type="Microsoft.Azure.Management.DataFactory.Models.SecretBase" />
        <Parameter Name="email" Type="System.Object" />
        <Parameter Name="keyFilePath" Type="System.Object" />
        <Parameter Name="trustedCertPath" Type="System.Object" />
        <Parameter Name="useSystemTrustStore" Type="System.Object" />
        <Parameter Name="encryptedCredential" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="project">クエリ対象の既定の BigQuery プロジェクト。</param>
        <param name="authenticationType">認証に使用される OAuth 2.0 認証メカニズム。 ServiceAuthentication はセルフホステッド IR のみで使用できます。 使用可能な値が含まれます: 'ServiceAuthentication'、'UserAuthentication'</param>
        <param name="additionalProperties">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</param>
        <param name="connectVia">統合のランタイム参照。</param>
        <param name="description">リンクされたサービスの説明。</param>
        <param name="additionalProjects">アクセス対象のパブリック BigQuery プロジェクトのコンマ区切りリスト。</param>
        <param name="requestGoogleDriveScope">Google Drive へのアクセスを要求するかどうか。 Google Drive のアクセスを許可すると、BigQuery データと Google Drive のデータを結合するフェデレーション テーブルのサポートが有効になります。 既定値は false です。</param>
        <param name="refreshToken">UserAuthentication で BigQuery へのアクセスを承認するために Google から取得した更新トークン。</param>
        <param name="email">ServiceAuthentication で使用されるサービス アカウントの電子メール ID。これはセルフホステッド IR のみで使用できます。</param>
        <param name="keyFilePath">サービス アカウントの電子メール アドレスを認証するために使用される .p12 キー ファイルへの完全なパス。これはセルフホステッド IR のみで使用できます。</param>
        <param name="trustedCertPath">SSL 経由で接続するときにサーバーを検証するための信頼された CA 証明書を含む .pem ファイルの完全なパス。 このプロパティは、セルフホステッド IR で SSL を使用する場合にのみ設定できます。 既定値は、IR でインストールされる cacerts.pem ファイルです。</param>
        <param name="useSystemTrustStore">システムの信頼ストアと指定した PEM ファイルのどちらの CA 証明書を使用するかを指定します。 既定値は false です。</param>
        <param name="encryptedCredential">暗号化された資格情報の認証に使用します。 資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。 型: 文字列 (または式の resultType 文字列)。</param>
        <summary>
            GoogleBigQueryLinkedService クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdditionalProjects">
      <MemberSignature Language="C#" Value="public object AdditionalProjects { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object AdditionalProjects" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService.AdditionalProjects" />
      <MemberSignature Language="VB.NET" Value="Public Property AdditionalProjects As Object" />
      <MemberSignature Language="F#" Value="member this.AdditionalProjects : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService.AdditionalProjects" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.additionalProjects")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはパブリックの BigQuery プロジェクトへのアクセスのコンマ区切りの一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationType">
      <MemberSignature Language="C#" Value="public string AuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService.AuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationType As String" />
      <MemberSignature Language="F#" Value="member this.AuthenticationType : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService.AuthenticationType" />
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
            取得または認証に使用する OAuth 2.0 認証メカニズムを設定します。 ServiceAuthentication はセルフホステッド IR のみで使用できます。 使用可能な値が含まれます: 'ServiceAuthentication'、'UserAuthentication'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Email">
      <MemberSignature Language="C#" Value="public object Email { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Email" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService.Email" />
      <MemberSignature Language="VB.NET" Value="Public Property Email As Object" />
      <MemberSignature Language="F#" Value="member this.Email : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService.Email" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.email")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、サービス アカウントの電子メール ID ServiceAuthentication が使用され、自己ホスト型の赤外線でのみ使用できます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptedCredential">
      <MemberSignature Language="C#" Value="public object EncryptedCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EncryptedCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService.EncryptedCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptedCredential As Object" />
      <MemberSignature Language="F#" Value="member this.EncryptedCredential : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService.EncryptedCredential" />
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
    <Member MemberName="KeyFilePath">
      <MemberSignature Language="C#" Value="public object KeyFilePath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object KeyFilePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService.KeyFilePath" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyFilePath As Object" />
      <MemberSignature Language="F#" Value="member this.KeyFilePath : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService.KeyFilePath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.keyFilePath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはサービス アカウントの電子メール アドレスの認証に使用し、自己ホスト型の赤外線でのみ使用できます .p12 キー ファイルへの完全パスを設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Project">
      <MemberSignature Language="C#" Value="public object Project { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Project" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService.Project" />
      <MemberSignature Language="VB.NET" Value="Public Property Project As Object" />
      <MemberSignature Language="F#" Value="member this.Project : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService.Project" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.project")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはに対してクエリを実行する既定の BigQuery プロジェクトを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshToken">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecretBase RefreshToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecretBase RefreshToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService.RefreshToken" />
      <MemberSignature Language="VB.NET" Value="Public Property RefreshToken As SecretBase" />
      <MemberSignature Language="F#" Value="member this.RefreshToken : Microsoft.Azure.Management.DataFactory.Models.SecretBase with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService.RefreshToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.refreshToken")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.SecretBase</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または UserAuthentication の BigQuery へのアクセスを承認するために、Google から取得した更新トークンを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestGoogleDriveScope">
      <MemberSignature Language="C#" Value="public object RequestGoogleDriveScope { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object RequestGoogleDriveScope" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService.RequestGoogleDriveScope" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestGoogleDriveScope As Object" />
      <MemberSignature Language="F#" Value="member this.RequestGoogleDriveScope : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService.RequestGoogleDriveScope" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.requestGoogleDriveScope")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Google ドライブへのアクセスを要求するかどうかを設定します。 Google Drive のアクセスを許可すると、BigQuery データと Google Drive のデータを結合するフェデレーション テーブルのサポートが有効になります。 既定値は false です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrustedCertPath">
      <MemberSignature Language="C#" Value="public object TrustedCertPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object TrustedCertPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService.TrustedCertPath" />
      <MemberSignature Language="VB.NET" Value="Public Property TrustedCertPath As Object" />
      <MemberSignature Language="F#" Value="member this.TrustedCertPath : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService.TrustedCertPath" />
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
    <Member MemberName="UseSystemTrustStore">
      <MemberSignature Language="C#" Value="public object UseSystemTrustStore { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object UseSystemTrustStore" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService.UseSystemTrustStore" />
      <MemberSignature Language="VB.NET" Value="Public Property UseSystemTrustStore As Object" />
      <MemberSignature Language="F#" Value="member this.UseSystemTrustStore : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService.UseSystemTrustStore" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="googleBigQueryLinkedService.Validate " />
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