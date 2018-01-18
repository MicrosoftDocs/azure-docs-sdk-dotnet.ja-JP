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
            <span data-ttu-id="20dbc-101">ディスクまたはスナップショットの暗号化の設定</span><span class="sxs-lookup"><span data-stu-id="20dbc-101">Encryption settings for disk or snapshot</span></span>
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
            <span data-ttu-id="20dbc-102">EncryptionSettings クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="20dbc-102">Initializes a new instance of the EncryptionSettings class.</span></span>
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
        <param name="enabled"><span data-ttu-id="20dbc-103">True し、暗号化を有効にするには、DiskEncryptionKey と省略可能な KeyEncryptionKey を提供するには、このフラグを設定します。</span><span class="sxs-lookup"><span data-stu-id="20dbc-103">Set this flag to true and provide DiskEncryptionKey and optional KeyEncryptionKey to enable encryption.</span></span> <span data-ttu-id="20dbc-104">このフラグを false に設定し、暗号化を無効にするには、DiskEncryptionKey と KeyEncryptionKey を削除します。</span><span class="sxs-lookup"><span data-stu-id="20dbc-104">Set this flag to false and remove DiskEncryptionKey and KeyEncryptionKey to disable encryption.</span></span> <span data-ttu-id="20dbc-105">EncryptionSettings が null の場合、要求オブジェクトの場合は、既存の設定は変更されません。</span><span class="sxs-lookup"><span data-stu-id="20dbc-105">If EncryptionSettings is null in the request object, the existing settings remain unchanged.</span></span></param>
        <param name="diskEncryptionKey"><span data-ttu-id="20dbc-106">ディスクの暗号化キーの Key Vault シークレットの Url と資格情報コンテナーの id</span><span class="sxs-lookup"><span data-stu-id="20dbc-106">Key Vault Secret Url and vault id of the disk encryption key</span></span></param>
        <param name="keyEncryptionKey"><span data-ttu-id="20dbc-107">キーの暗号化キーの Key Vault のキーの Url と資格情報コンテナーの id</span><span class="sxs-lookup"><span data-stu-id="20dbc-107">Key Vault Key Url and vault id of the key encryption key</span></span></param>
        <summary>
            <span data-ttu-id="20dbc-108">EncryptionSettings クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="20dbc-108">Initializes a new instance of the EncryptionSettings class.</span></span>
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
            <span data-ttu-id="20dbc-109">キー Vault シークレットの Url と、ディスクの暗号化キーの id を資格情報コンテナーを取得または設定</span><span class="sxs-lookup"><span data-stu-id="20dbc-109">Gets or sets key Vault Secret Url and vault id of the disk encryption key</span></span>
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
            <span data-ttu-id="20dbc-110">取得または設定は、true し、暗号化を有効にするには、DiskEncryptionKey と省略可能な KeyEncryptionKey を提供するには、このフラグを設定します。</span><span class="sxs-lookup"><span data-stu-id="20dbc-110">Gets or sets set this flag to true and provide DiskEncryptionKey and optional KeyEncryptionKey to enable encryption.</span></span> <span data-ttu-id="20dbc-111">このフラグを false に設定し、暗号化を無効にするには、DiskEncryptionKey と KeyEncryptionKey を削除します。</span><span class="sxs-lookup"><span data-stu-id="20dbc-111">Set this flag to false and remove DiskEncryptionKey and KeyEncryptionKey to disable encryption.</span></span> <span data-ttu-id="20dbc-112">EncryptionSettings が null の場合、要求オブジェクトの場合は、既存の設定は変更されません。</span><span class="sxs-lookup"><span data-stu-id="20dbc-112">If EncryptionSettings is null in the request object, the existing settings remain unchanged.</span></span>
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
            <span data-ttu-id="20dbc-113">キーの資格情報コンテナー キーの Url とキーの暗号化キーの id を資格情報コンテナーを取得または設定</span><span class="sxs-lookup"><span data-stu-id="20dbc-113">Gets or sets key Vault Key Url and vault id of the key encryption key</span></span>
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
            <span data-ttu-id="20dbc-114">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="20dbc-114">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="20dbc-115">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="20dbc-115">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>