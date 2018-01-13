<Type Name="AzureMLLinkedService" FullName="Microsoft.Azure.Management.DataFactory.Models.AzureMLLinkedService">
  <TypeSignature Language="C#" Value="public class AzureMLLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureMLLinkedService extends Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.AzureMLLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureMLLinkedService&#xA;Inherits LinkedService" />
  <TypeSignature Language="F#" Value="type AzureMLLinkedService = class&#xA;    inherit LinkedService" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
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
      <AttributeName>Newtonsoft.Json.JsonObject("AzureML")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Azure ML Web サービスにリンクされたサービスを指定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureMLLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureMLLinkedService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            AzureMLLinkedService クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureMLLinkedService (object mlEndpoint, Microsoft.Azure.Management.DataFactory.Models.SecureString apiKey, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia = null, string description = null, object updateResourceEndpoint = null, object servicePrincipalId = null, Microsoft.Azure.Management.DataFactory.Models.SecureString servicePrincipalKey = null, object tenant = null, object encryptedCredential = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object mlEndpoint, class Microsoft.Azure.Management.DataFactory.Models.SecureString apiKey, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia, string description, object updateResourceEndpoint, object servicePrincipalId, class Microsoft.Azure.Management.DataFactory.Models.SecureString servicePrincipalKey, object tenant, object encryptedCredential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureMLLinkedService.#ctor(System.Object,Microsoft.Azure.Management.DataFactory.Models.SecureString,System.Collections.Generic.IDictionary{System.String,System.Object},Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference,System.String,System.Object,System.Object,Microsoft.Azure.Management.DataFactory.Models.SecureString,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (mlEndpoint As Object, apiKey As SecureString, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional connectVia As IntegrationRuntimeReference = null, Optional description As String = null, Optional updateResourceEndpoint As Object = null, Optional servicePrincipalId As Object = null, Optional servicePrincipalKey As SecureString = null, Optional tenant As Object = null, Optional encryptedCredential As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.AzureMLLinkedService : obj * Microsoft.Azure.Management.DataFactory.Models.SecureString * System.Collections.Generic.IDictionary&lt;string, obj&gt; * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference * string * obj * obj * Microsoft.Azure.Management.DataFactory.Models.SecureString * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.AzureMLLinkedService" Usage="new Microsoft.Azure.Management.DataFactory.Models.AzureMLLinkedService (mlEndpoint, apiKey, additionalProperties, connectVia, description, updateResourceEndpoint, servicePrincipalId, servicePrincipalKey, tenant, encryptedCredential)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="mlEndpoint" Type="System.Object" />
        <Parameter Name="apiKey" Type="Microsoft.Azure.Management.DataFactory.Models.SecureString" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="connectVia" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="updateResourceEndpoint" Type="System.Object" />
        <Parameter Name="servicePrincipalId" Type="System.Object" />
        <Parameter Name="servicePrincipalKey" Type="Microsoft.Azure.Management.DataFactory.Models.SecureString" />
        <Parameter Name="tenant" Type="System.Object" />
        <Parameter Name="encryptedCredential" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="mlEndpoint">Azure ML Web サービス エンドポイントのバッチ実行 REST の URL です。 型: 文字列 (または式の resultType 文字列)。</param>
        <param name="apiKey">Azure ML モデル エンドポイントにアクセスするために API キー。</param>
        <param name="additionalProperties">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</param>
        <param name="connectVia">統合のランタイム参照。</param>
        <param name="description">リンクされたサービスの説明。</param>
        <param name="updateResourceEndpoint">Azure ML Web サービス エンドポイントの更新リソース REST の URL。 型: 文字列 (または式の resultType 文字列)。</param>
        <param name="servicePrincipalId">Azure ML web サービスの ARM ベース updateResourceEndpoint に対する認証に使用されるサービス プリンシパルの ID。 型: 文字列 (または式の resultType 文字列)。</param>
        <param name="servicePrincipalKey">Azure ML web サービスの ARM ベース updateResourceEndpoint に対する認証に使用されるサービス プリンシパルのキー。</param>
        <param name="tenant">名前またはサービス プリンシパルが属しているテナントの ID。 型: 文字列 (または式の resultType 文字列)。</param>
        <param name="encryptedCredential">暗号化された資格情報の認証に使用します。 資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。 型: 文字列 (または式の resultType 文字列)。</param>
        <summary>
            AzureMLLinkedService クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecureString ApiKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecureString ApiKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureMLLinkedService.ApiKey" />
      <MemberSignature Language="VB.NET" Value="Public Property ApiKey As SecureString" />
      <MemberSignature Language="F#" Value="member this.ApiKey : Microsoft.Azure.Management.DataFactory.Models.SecureString with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureMLLinkedService.ApiKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.apiKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.SecureString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure ML モデル エンドポイントにアクセスするために API キーを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptedCredential">
      <MemberSignature Language="C#" Value="public object EncryptedCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EncryptedCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureMLLinkedService.EncryptedCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptedCredential As Object" />
      <MemberSignature Language="F#" Value="member this.EncryptedCredential : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureMLLinkedService.EncryptedCredential" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
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
    <Member MemberName="MlEndpoint">
      <MemberSignature Language="C#" Value="public object MlEndpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object MlEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureMLLinkedService.MlEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property MlEndpoint As Object" />
      <MemberSignature Language="F#" Value="member this.MlEndpoint : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureMLLinkedService.MlEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.mlEndpoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure ML Web サービス エンドポイントのバッチ実行 REST の URL を設定します。 型: 文字列 (または式の resultType 文字列)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePrincipalId">
      <MemberSignature Language="C#" Value="public object ServicePrincipalId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object ServicePrincipalId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureMLLinkedService.ServicePrincipalId" />
      <MemberSignature Language="VB.NET" Value="Public Property ServicePrincipalId As Object" />
      <MemberSignature Language="F#" Value="member this.ServicePrincipalId : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureMLLinkedService.ServicePrincipalId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.servicePrincipalId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure ML web サービスの ARM ベース updateResourceEndpoint に対する認証に使用するサービス プリンシパルの ID を設定します。 型: 文字列 (または式の resultType 文字列)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePrincipalKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecureString ServicePrincipalKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecureString ServicePrincipalKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureMLLinkedService.ServicePrincipalKey" />
      <MemberSignature Language="VB.NET" Value="Public Property ServicePrincipalKey As SecureString" />
      <MemberSignature Language="F#" Value="member this.ServicePrincipalKey : Microsoft.Azure.Management.DataFactory.Models.SecureString with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureMLLinkedService.ServicePrincipalKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.servicePrincipalKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.SecureString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure ML web サービスの ARM ベース updateResourceEndpoint に対する認証に使用されるサービス プリンシパルのキーを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tenant">
      <MemberSignature Language="C#" Value="public object Tenant { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Tenant" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureMLLinkedService.Tenant" />
      <MemberSignature Language="VB.NET" Value="Public Property Tenant As Object" />
      <MemberSignature Language="F#" Value="member this.Tenant : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureMLLinkedService.Tenant" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.tenant")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または名またはサービス プリンシパルが属しているテナントの ID を設定します。 型: 文字列 (または式の resultType 文字列)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateResourceEndpoint">
      <MemberSignature Language="C#" Value="public object UpdateResourceEndpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object UpdateResourceEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureMLLinkedService.UpdateResourceEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property UpdateResourceEndpoint As Object" />
      <MemberSignature Language="F#" Value="member this.UpdateResourceEndpoint : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureMLLinkedService.UpdateResourceEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.updateResourceEndpoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure ML Web サービス エンドポイントの更新リソース REST の URL を設定します。 型: 文字列 (または式の resultType 文字列)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureMLLinkedService.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="azureMLLinkedService.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
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