<Type Name="Encryption" FullName="Microsoft.Azure.Management.Storage.Models.Encryption">
  <TypeSignature Language="C#" Value="public class Encryption" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Encryption extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Models.Encryption" />
  <TypeSignature Language="VB.NET" Value="Public Class Encryption" />
  <TypeSignature Language="F#" Value="type Encryption = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
    <AssemblyVersion>7.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ストレージ アカウントの暗号化設定です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Encryption ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.Encryption.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            暗号化クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Encryption (string keySource, Microsoft.Azure.Management.Storage.Models.EncryptionServices services = null, Microsoft.Azure.Management.Storage.Models.KeyVaultProperties keyVaultProperties = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string keySource, class Microsoft.Azure.Management.Storage.Models.EncryptionServices services, class Microsoft.Azure.Management.Storage.Models.KeyVaultProperties keyVaultProperties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.Encryption.#ctor(System.String,Microsoft.Azure.Management.Storage.Models.EncryptionServices,Microsoft.Azure.Management.Storage.Models.KeyVaultProperties)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Storage.Models.Encryption : string * Microsoft.Azure.Management.Storage.Models.EncryptionServices * Microsoft.Azure.Management.Storage.Models.KeyVaultProperties -&gt; Microsoft.Azure.Management.Storage.Models.Encryption" Usage="new Microsoft.Azure.Management.Storage.Models.Encryption (keySource, services, keyVaultProperties)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="keySource" Type="System.String" />
        <Parameter Name="services" Type="Microsoft.Azure.Management.Storage.Models.EncryptionServices" />
        <Parameter Name="keyVaultProperties" Type="Microsoft.Azure.Management.Storage.Models.KeyVaultProperties" />
      </Parameters>
      <Docs>
        <param name="keySource">暗号化 keySource (プロバイダー)。
            使用可能な値 (小文字): Microsoft.Storage、Microsoft.Keyvault です。 使用可能な値が含まれます: 'Microsoft.Storage'、'Microsoft.Keyvault'</param>
        <param name="services">暗号化をサポートするサービスの一覧です。</param>
        <param name="keyVaultProperties">資格情報コンテナーによって提供されるプロパティです。</param>
        <summary>
            暗号化クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeySource">
      <MemberSignature Language="C#" Value="public string KeySource { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeySource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.Encryption.KeySource" />
      <MemberSignature Language="VB.NET" Value="Public Property KeySource As String" />
      <MemberSignature Language="F#" Value="member this.KeySource : string with get, set" Usage="Microsoft.Azure.Management.Storage.Models.Encryption.KeySource" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keySource")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または暗号化 keySource (プロバイダー) を設定します。 使用可能な値 (小文字): Microsoft.Storage、Microsoft.Keyvault です。
            使用可能な値が含まれます: 'Microsoft.Storage'、'Microsoft.Keyvault'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyVaultProperties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Models.KeyVaultProperties KeyVaultProperties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Models.KeyVaultProperties KeyVaultProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.Encryption.KeyVaultProperties" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyVaultProperties As KeyVaultProperties" />
      <MemberSignature Language="F#" Value="member this.KeyVaultProperties : Microsoft.Azure.Management.Storage.Models.KeyVaultProperties with get, set" Usage="Microsoft.Azure.Management.Storage.Models.Encryption.KeyVaultProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keyvaultproperties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.KeyVaultProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または資格情報コンテナーで提供されるプロパティを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Services">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Models.EncryptionServices Services { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Models.EncryptionServices Services" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.Encryption.Services" />
      <MemberSignature Language="VB.NET" Value="Public Property Services As EncryptionServices" />
      <MemberSignature Language="F#" Value="member this.Services : Microsoft.Azure.Management.Storage.Models.EncryptionServices with get, set" Usage="Microsoft.Azure.Management.Storage.Models.Encryption.Services" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="services")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.EncryptionServices</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または暗号化をサポートするサービスの一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.Encryption.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="encryption.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
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