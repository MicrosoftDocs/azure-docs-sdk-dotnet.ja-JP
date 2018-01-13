<Type Name="HubspotLinkedService" FullName="Microsoft.Azure.Management.DataFactory.Models.HubspotLinkedService">
  <TypeSignature Language="C#" Value="public class HubspotLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HubspotLinkedService extends Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.HubspotLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class HubspotLinkedService&#xA;Inherits LinkedService" />
  <TypeSignature Language="F#" Value="type HubspotLinkedService = class&#xA;    inherit LinkedService" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("Hubspot")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Hubspot サービスにリンクされたサービスを指定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HubspotLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.HubspotLinkedService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            HubspotLinkedService クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HubspotLinkedService (object clientId, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia = null, string description = null, Microsoft.Azure.Management.DataFactory.Models.SecretBase clientSecret = null, Microsoft.Azure.Management.DataFactory.Models.SecretBase accessToken = null, Microsoft.Azure.Management.DataFactory.Models.SecretBase refreshToken = null, object useEncryptedEndpoints = null, object useHostVerification = null, object usePeerVerification = null, object encryptedCredential = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object clientId, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia, string description, class Microsoft.Azure.Management.DataFactory.Models.SecretBase clientSecret, class Microsoft.Azure.Management.DataFactory.Models.SecretBase accessToken, class Microsoft.Azure.Management.DataFactory.Models.SecretBase refreshToken, object useEncryptedEndpoints, object useHostVerification, object usePeerVerification, object encryptedCredential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.HubspotLinkedService.#ctor(System.Object,System.Collections.Generic.IDictionary{System.String,System.Object},Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference,System.String,Microsoft.Azure.Management.DataFactory.Models.SecretBase,Microsoft.Azure.Management.DataFactory.Models.SecretBase,Microsoft.Azure.Management.DataFactory.Models.SecretBase,System.Object,System.Object,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (clientId As Object, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional connectVia As IntegrationRuntimeReference = null, Optional description As String = null, Optional clientSecret As SecretBase = null, Optional accessToken As SecretBase = null, Optional refreshToken As SecretBase = null, Optional useEncryptedEndpoints As Object = null, Optional useHostVerification As Object = null, Optional usePeerVerification As Object = null, Optional encryptedCredential As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.HubspotLinkedService : obj * System.Collections.Generic.IDictionary&lt;string, obj&gt; * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference * string * Microsoft.Azure.Management.DataFactory.Models.SecretBase * Microsoft.Azure.Management.DataFactory.Models.SecretBase * Microsoft.Azure.Management.DataFactory.Models.SecretBase * obj * obj * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.HubspotLinkedService" Usage="new Microsoft.Azure.Management.DataFactory.Models.HubspotLinkedService (clientId, additionalProperties, connectVia, description, clientSecret, accessToken, refreshToken, useEncryptedEndpoints, useHostVerification, usePeerVerification, encryptedCredential)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clientId" Type="System.Object" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="connectVia" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="clientSecret" Type="Microsoft.Azure.Management.DataFactory.Models.SecretBase" />
        <Parameter Name="accessToken" Type="Microsoft.Azure.Management.DataFactory.Models.SecretBase" />
        <Parameter Name="refreshToken" Type="Microsoft.Azure.Management.DataFactory.Models.SecretBase" />
        <Parameter Name="useEncryptedEndpoints" Type="System.Object" />
        <Parameter Name="useHostVerification" Type="System.Object" />
        <Parameter Name="usePeerVerification" Type="System.Object" />
        <Parameter Name="encryptedCredential" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="clientId">Hubspot アプリケーションに関連付けられているクライアント ID。</param>
        <param name="additionalProperties">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</param>
        <param name="connectVia">統合のランタイム参照。</param>
        <param name="description">リンクされたサービスの説明。</param>
        <param name="clientSecret">Hubspot アプリケーションに関連付けられているクライアント シークレット。</param>
        <param name="accessToken">最初に OAuth 統合を認証するときに取得したアクセス トークン。</param>
        <param name="refreshToken">最初に OAuth 統合を認証するときに取得した更新トークン。</param>
        <param name="useEncryptedEndpoints">データ ソースのエンドポイントが HTTPS を使用して暗号化されるかどうかを指定します。 既定値は true です。</param>
        <param name="useHostVerification">SSL 経由で接続するときに、サーバーの証明書内のホスト名がサーバーのホスト名と一致する必要があるかどうかを指定します。 既定値は true です。</param>
        <param name="usePeerVerification">SSL 経由で接続するときに、サーバーの ID を検証するかどうかを指定します。 既定値は true です。</param>
        <param name="encryptedCredential">暗号化された資格情報の認証に使用します。 資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。 型: 文字列 (または式の resultType 文字列)。</param>
        <summary>
            HubspotLinkedService クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessToken">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecretBase AccessToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecretBase AccessToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HubspotLinkedService.AccessToken" />
      <MemberSignature Language="VB.NET" Value="Public Property AccessToken As SecretBase" />
      <MemberSignature Language="F#" Value="member this.AccessToken : Microsoft.Azure.Management.DataFactory.Models.SecretBase with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HubspotLinkedService.AccessToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.accessToken")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.SecretBase</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または最初に、OAuth の統合を認証するときに取得したアクセス トークンを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientId">
      <MemberSignature Language="C#" Value="public object ClientId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object ClientId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HubspotLinkedService.ClientId" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientId As Object" />
      <MemberSignature Language="F#" Value="member this.ClientId : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HubspotLinkedService.ClientId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.clientId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Hubspot アプリケーションに関連付けられたクライアント ID を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientSecret">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecretBase ClientSecret { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecretBase ClientSecret" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HubspotLinkedService.ClientSecret" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientSecret As SecretBase" />
      <MemberSignature Language="F#" Value="member this.ClientSecret : Microsoft.Azure.Management.DataFactory.Models.SecretBase with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HubspotLinkedService.ClientSecret" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.clientSecret")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.SecretBase</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Hubspot アプリケーションに関連付けられたクライアント シークレットを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptedCredential">
      <MemberSignature Language="C#" Value="public object EncryptedCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EncryptedCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HubspotLinkedService.EncryptedCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptedCredential As Object" />
      <MemberSignature Language="F#" Value="member this.EncryptedCredential : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HubspotLinkedService.EncryptedCredential" />
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
    <Member MemberName="RefreshToken">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecretBase RefreshToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecretBase RefreshToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HubspotLinkedService.RefreshToken" />
      <MemberSignature Language="VB.NET" Value="Public Property RefreshToken As SecretBase" />
      <MemberSignature Language="F#" Value="member this.RefreshToken : Microsoft.Azure.Management.DataFactory.Models.SecretBase with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HubspotLinkedService.RefreshToken" />
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
            取得または最初に、OAuth の統合を認証するときに取得した更新トークンを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseEncryptedEndpoints">
      <MemberSignature Language="C#" Value="public object UseEncryptedEndpoints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object UseEncryptedEndpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HubspotLinkedService.UseEncryptedEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public Property UseEncryptedEndpoints As Object" />
      <MemberSignature Language="F#" Value="member this.UseEncryptedEndpoints : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HubspotLinkedService.UseEncryptedEndpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.useEncryptedEndpoints")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、データ ソースのエンドポイントは HTTPS を使用して暗号化するかどうかを指定します。 既定値は true です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseHostVerification">
      <MemberSignature Language="C#" Value="public object UseHostVerification { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object UseHostVerification" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HubspotLinkedService.UseHostVerification" />
      <MemberSignature Language="VB.NET" Value="Public Property UseHostVerification As Object" />
      <MemberSignature Language="F#" Value="member this.UseHostVerification : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HubspotLinkedService.UseHostVerification" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.useHostVerification")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、SSL 経由で接続するときに、サーバーのホスト名を一致するように、サーバーの証明書内のホスト名を必要とするかどうかを指定します。 既定値は true です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UsePeerVerification">
      <MemberSignature Language="C#" Value="public object UsePeerVerification { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object UsePeerVerification" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HubspotLinkedService.UsePeerVerification" />
      <MemberSignature Language="VB.NET" Value="Public Property UsePeerVerification As Object" />
      <MemberSignature Language="F#" Value="member this.UsePeerVerification : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HubspotLinkedService.UsePeerVerification" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.usePeerVerification")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、SSL 経由で接続するときに、サーバーの id を確認するかどうかを指定します。 既定値は true です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.HubspotLinkedService.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="hubspotLinkedService.Validate " />
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