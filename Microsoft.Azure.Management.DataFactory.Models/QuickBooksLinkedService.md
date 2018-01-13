<Type Name="QuickBooksLinkedService" FullName="Microsoft.Azure.Management.DataFactory.Models.QuickBooksLinkedService">
  <TypeSignature Language="C#" Value="public class QuickBooksLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit QuickBooksLinkedService extends Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.QuickBooksLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class QuickBooksLinkedService&#xA;Inherits LinkedService" />
  <TypeSignature Language="F#" Value="type QuickBooksLinkedService = class&#xA;    inherit LinkedService" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("QuickBooks")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            QuickBooks サーバーにリンクされたサービスを指定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public QuickBooksLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.QuickBooksLinkedService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            QuickBooksLinkedService クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public QuickBooksLinkedService (object endpoint, object companyId, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia = null, string description = null, Microsoft.Azure.Management.DataFactory.Models.SecretBase accessToken = null, Microsoft.Azure.Management.DataFactory.Models.SecretBase accessTokenSecret = null, object useEncryptedEndpoints = null, object encryptedCredential = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object endpoint, object companyId, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia, string description, class Microsoft.Azure.Management.DataFactory.Models.SecretBase accessToken, class Microsoft.Azure.Management.DataFactory.Models.SecretBase accessTokenSecret, object useEncryptedEndpoints, object encryptedCredential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.QuickBooksLinkedService.#ctor(System.Object,System.Object,System.Collections.Generic.IDictionary{System.String,System.Object},Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference,System.String,Microsoft.Azure.Management.DataFactory.Models.SecretBase,Microsoft.Azure.Management.DataFactory.Models.SecretBase,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (endpoint As Object, companyId As Object, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional connectVia As IntegrationRuntimeReference = null, Optional description As String = null, Optional accessToken As SecretBase = null, Optional accessTokenSecret As SecretBase = null, Optional useEncryptedEndpoints As Object = null, Optional encryptedCredential As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.QuickBooksLinkedService : obj * obj * System.Collections.Generic.IDictionary&lt;string, obj&gt; * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference * string * Microsoft.Azure.Management.DataFactory.Models.SecretBase * Microsoft.Azure.Management.DataFactory.Models.SecretBase * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.QuickBooksLinkedService" Usage="new Microsoft.Azure.Management.DataFactory.Models.QuickBooksLinkedService (endpoint, companyId, additionalProperties, connectVia, description, accessToken, accessTokenSecret, useEncryptedEndpoints, encryptedCredential)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="endpoint" Type="System.Object" />
        <Parameter Name="companyId" Type="System.Object" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="connectVia" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="accessToken" Type="Microsoft.Azure.Management.DataFactory.Models.SecretBase" />
        <Parameter Name="accessTokenSecret" Type="Microsoft.Azure.Management.DataFactory.Models.SecretBase" />
        <Parameter Name="useEncryptedEndpoints" Type="System.Object" />
        <Parameter Name="encryptedCredential" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="endpoint">QuickBooks サーバーのエンドポイント。 (つまり quickbooks.api.intuit.com)</param>
        <param name="companyId">承認する QuickBooks の会社の会社 ID。</param>
        <param name="additionalProperties">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</param>
        <param name="connectVia">統合のランタイム参照。</param>
        <param name="description">リンクされたサービスの説明。</param>
        <param name="accessToken">OAuth 1.0 認証のアクセス トークン。</param>
        <param name="accessTokenSecret">OAuth 1.0 認証のアクセス トークン シークレット。</param>
        <param name="useEncryptedEndpoints">データ ソースのエンドポイントが HTTPS を使用して暗号化されるかどうかを指定します。 既定値は true です。</param>
        <param name="encryptedCredential">暗号化された資格情報の認証に使用します。 資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。 型: 文字列 (または式の resultType 文字列)。</param>
        <summary>
            QuickBooksLinkedService クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessToken">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecretBase AccessToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecretBase AccessToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.QuickBooksLinkedService.AccessToken" />
      <MemberSignature Language="VB.NET" Value="Public Property AccessToken As SecretBase" />
      <MemberSignature Language="F#" Value="member this.AccessToken : Microsoft.Azure.Management.DataFactory.Models.SecretBase with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.QuickBooksLinkedService.AccessToken" />
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
            取得または OAuth 1.0 認証アクセス トークンを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessTokenSecret">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecretBase AccessTokenSecret { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecretBase AccessTokenSecret" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.QuickBooksLinkedService.AccessTokenSecret" />
      <MemberSignature Language="VB.NET" Value="Public Property AccessTokenSecret As SecretBase" />
      <MemberSignature Language="F#" Value="member this.AccessTokenSecret : Microsoft.Azure.Management.DataFactory.Models.SecretBase with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.QuickBooksLinkedService.AccessTokenSecret" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.accessTokenSecret")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.SecretBase</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または OAuth 1.0 認証アクセス トークン シークレットを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompanyId">
      <MemberSignature Language="C#" Value="public object CompanyId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object CompanyId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.QuickBooksLinkedService.CompanyId" />
      <MemberSignature Language="VB.NET" Value="Public Property CompanyId As Object" />
      <MemberSignature Language="F#" Value="member this.CompanyId : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.QuickBooksLinkedService.CompanyId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.companyId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または承認するために QuickBooks 会社の企業 ID を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptedCredential">
      <MemberSignature Language="C#" Value="public object EncryptedCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EncryptedCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.QuickBooksLinkedService.EncryptedCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptedCredential As Object" />
      <MemberSignature Language="F#" Value="member this.EncryptedCredential : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.QuickBooksLinkedService.EncryptedCredential" />
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
    <Member MemberName="Endpoint">
      <MemberSignature Language="C#" Value="public object Endpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Endpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.QuickBooksLinkedService.Endpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property Endpoint As Object" />
      <MemberSignature Language="F#" Value="member this.Endpoint : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.QuickBooksLinkedService.Endpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.endpoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または QuickBooks サーバーのエンドポイントを設定します。 (つまり quickbooks.api.intuit.com)
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseEncryptedEndpoints">
      <MemberSignature Language="C#" Value="public object UseEncryptedEndpoints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object UseEncryptedEndpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.QuickBooksLinkedService.UseEncryptedEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public Property UseEncryptedEndpoints As Object" />
      <MemberSignature Language="F#" Value="member this.UseEncryptedEndpoints : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.QuickBooksLinkedService.UseEncryptedEndpoints" />
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
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.QuickBooksLinkedService.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="quickBooksLinkedService.Validate " />
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