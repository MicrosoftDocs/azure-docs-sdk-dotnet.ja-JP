<Type Name="AppServiceCertificateResource" FullName="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource">
  <TypeSignature Language="C#" Value="public class AppServiceCertificateResource : Microsoft.Azure.Management.WebSites.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AppServiceCertificateResource extends Microsoft.Azure.Management.WebSites.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource" />
  <TypeSignature Language="VB.NET" Value="Public Class AppServiceCertificateResource&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type AppServiceCertificateResource = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Key Vault のコンテナーを Azure で購入した証明書の ARM リソースです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AppServiceCertificateResource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            AppServiceCertificateResource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AppServiceCertificateResource (string location, string id = null, string name = null, string kind = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string keyVaultId = null, string keyVaultSecretName = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.KeyVaultSecretStatus&gt; provisioningState = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string kind, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string keyVaultId, string keyVaultSecretName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.KeyVaultSecretStatus&gt; provisioningState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource.#ctor(System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.String,System.Nullable{Microsoft.Azure.Management.WebSites.Models.KeyVaultSecretStatus})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (location As String, Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional keyVaultId As String = null, Optional keyVaultSecretName As String = null, Optional provisioningState As Nullable(Of KeyVaultSecretStatus) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource : string * string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * string * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.KeyVaultSecretStatus&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource" Usage="new Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource (location, id, name, kind, type, tags, keyVaultId, keyVaultSecretName, provisioningState)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="keyVaultId" Type="System.String" />
        <Parameter Name="keyVaultSecretName" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.KeyVaultSecretStatus&gt;" />
      </Parameters>
      <Docs>
        <param name="location">リソースの場所。</param>
        <param name="id">リソース id です。</param>
        <param name="name">リソースの名前です。</param>
        <param name="kind">リソースの種類。</param>
        <param name="type">リソースの種類。</param>
        <param name="tags">リソース タグ。</param>
        <param name="keyVaultId">Key Vault リソース id。</param>
        <param name="keyVaultSecretName">Key Vault シークレットの名前です。</param>
        <param name="provisioningState">Key Vault シークレットの状態です。
            使用可能な値が含まれます: '初期化'、'WaitingOnCertificateOrder'、'成功'、'CertificateOrderFailed'、'OperationNotPermittedOnKeyVault'、'AzureServiceUnauthorizedToAccessKeyVault'、'KeyVaultDoesNotExist'、'KeyVaultSecretDoesNotExist'、'された'、'ExternalPrivateKey'、'Unknown'</param>
        <summary>
            AppServiceCertificateResource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyVaultId">
      <MemberSignature Language="C#" Value="public string KeyVaultId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyVaultId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource.KeyVaultId" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyVaultId As String" />
      <MemberSignature Language="F#" Value="member this.KeyVaultId : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource.KeyVaultId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.keyVaultId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定キーの資格情報コンテナーのリソース id。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyVaultSecretName">
      <MemberSignature Language="C#" Value="public string KeyVaultSecretName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyVaultSecretName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource.KeyVaultSecretName" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyVaultSecretName As String" />
      <MemberSignature Language="F#" Value="member this.KeyVaultSecretName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource.KeyVaultSecretName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.keyVaultSecretName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはキーの資格情報コンテナーのシークレット名を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.KeyVaultSecretStatus&gt; ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.KeyVaultSecretStatus&gt; ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As Nullable(Of KeyVaultSecretStatus)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.KeyVaultSecretStatus&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.KeyVaultSecretStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            秘密キー コンテナーの状態を取得します。 使用可能な値が含まれます: '初期化'、'WaitingOnCertificateOrder'、'成功'、'CertificateOrderFailed'、'OperationNotPermittedOnKeyVault'、'AzureServiceUnauthorizedToAccessKeyVault'、'KeyVaultDoesNotExist'、'KeyVaultSecretDoesNotExist'、'された'、'ExternalPrivateKey'、'Unknown'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="appServiceCertificateResource.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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