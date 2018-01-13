<Type Name="EncryptionSettings" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.EncryptionSettings">
  <TypeSignature Language="C#" Value="public class EncryptionSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EncryptionSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.EncryptionSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class EncryptionSettings" />
  <TypeSignature Language="F#" Value="type EncryptionSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ディスクまたはスナップショットの暗号化の設定
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EncryptionSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.EncryptionSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            EncryptionSettings クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EncryptionSettings (Nullable&lt;bool&gt; enabled = null, Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndSecretReference diskEncryptionKey = null, Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndKeyReference keyEncryptionKey = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; enabled, class Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndSecretReference diskEncryptionKey, class Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndKeyReference keyEncryptionKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.EncryptionSettings.#ctor(System.Nullable{System.Boolean},Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndSecretReference,Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndKeyReference)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional enabled As Nullable(Of Boolean) = null, Optional diskEncryptionKey As KeyVaultAndSecretReference = null, Optional keyEncryptionKey As KeyVaultAndKeyReference = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.EncryptionSettings : Nullable&lt;bool&gt; * Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndSecretReference * Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndKeyReference -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.EncryptionSettings" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.EncryptionSettings (enabled, diskEncryptionKey, keyEncryptionKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="enabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="diskEncryptionKey" Type="Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndSecretReference" />
        <Parameter Name="keyEncryptionKey" Type="Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndKeyReference" />
      </Parameters>
      <Docs>
        <param name="enabled">True し、暗号化を有効にするには、DiskEncryptionKey と省略可能な KeyEncryptionKey を提供するには、このフラグを設定します。 このフラグを false に設定し、暗号化を無効にするには、DiskEncryptionKey と KeyEncryptionKey を削除します。 EncryptionSettings が null の場合、要求オブジェクトの場合は、既存の設定は変更されません。</param>
        <param name="diskEncryptionKey">ディスクの暗号化キーの Key Vault シークレットの Url と資格情報コンテナーの id</param>
        <param name="keyEncryptionKey">キーの暗号化キーの Key Vault のキーの Url と資格情報コンテナーの id</param>
        <summary>
            EncryptionSettings クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiskEncryptionKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndSecretReference DiskEncryptionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndSecretReference DiskEncryptionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.EncryptionSettings.DiskEncryptionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property DiskEncryptionKey As KeyVaultAndSecretReference" />
      <MemberSignature Language="F#" Value="member this.DiskEncryptionKey : Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndSecretReference with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.EncryptionSettings.DiskEncryptionKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="diskEncryptionKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndSecretReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            キー Vault シークレットの Url と、ディスクの暗号化キーの id を資格情報コンテナーを取得または設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Enabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Enabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.EncryptionSettings.Enabled" />
      <MemberSignature Language="VB.NET" Value="Public Property Enabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Enabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.EncryptionSettings.Enabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="enabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、true し、暗号化を有効にするには、DiskEncryptionKey と省略可能な KeyEncryptionKey を提供するには、このフラグを設定します。 このフラグを false に設定し、暗号化を無効にするには、DiskEncryptionKey と KeyEncryptionKey を削除します。 EncryptionSettings が null の場合、要求オブジェクトの場合は、既存の設定は変更されません。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyEncryptionKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndKeyReference KeyEncryptionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndKeyReference KeyEncryptionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.EncryptionSettings.KeyEncryptionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyEncryptionKey As KeyVaultAndKeyReference" />
      <MemberSignature Language="F#" Value="member this.KeyEncryptionKey : Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndKeyReference with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.EncryptionSettings.KeyEncryptionKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keyEncryptionKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndKeyReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            キーの資格情報コンテナー キーの Url とキーの暗号化キーの id を資格情報コンテナーを取得または設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.EncryptionSettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="encryptionSettings.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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