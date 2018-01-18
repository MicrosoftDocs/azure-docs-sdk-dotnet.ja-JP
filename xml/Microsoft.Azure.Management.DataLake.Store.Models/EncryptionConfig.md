<Type Name="EncryptionConfig" FullName="Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfig">
  <TypeSignature Language="C#" Value="public class EncryptionConfig" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EncryptionConfig extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfig" />
  <TypeSignature Language="VB.NET" Value="Public Class EncryptionConfig" />
  <TypeSignature Language="F#" Value="type EncryptionConfig = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f4746-101">アカウントの暗号化の構成。</span><span class="sxs-lookup"><span data-stu-id="f4746-101">The encryption configuration for the account.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EncryptionConfig ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfig.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f4746-102">EncryptionConfig クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f4746-102">Initializes a new instance of the EncryptionConfig class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EncryptionConfig (Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfigType type, Microsoft.Azure.Management.DataLake.Store.Models.KeyVaultMetaInfo keyVaultMetaInfo = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfigType type, class Microsoft.Azure.Management.DataLake.Store.Models.KeyVaultMetaInfo keyVaultMetaInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfig.#ctor(Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfigType,Microsoft.Azure.Management.DataLake.Store.Models.KeyVaultMetaInfo)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfig : Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfigType * Microsoft.Azure.Management.DataLake.Store.Models.KeyVaultMetaInfo -&gt; Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfig" Usage="new Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfig (type, keyVaultMetaInfo)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="type" Type="Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfigType" />
        <Parameter Name="keyVaultMetaInfo" Type="Microsoft.Azure.Management.DataLake.Store.Models.KeyVaultMetaInfo" />
      </Parameters>
      <Docs>
        <param name="type"><span data-ttu-id="f4746-103">使用されている暗号化構成の型。</span><span class="sxs-lookup"><span data-stu-id="f4746-103">The type of encryption configuration being used.</span></span>
            <span data-ttu-id="f4746-104">現在サポートされている型はのみ 'UserManaged' および 'ServiceManaged' です。</span><span class="sxs-lookup"><span data-stu-id="f4746-104">Currently the only supported types are 'UserManaged' and 'ServiceManaged'.</span></span> <span data-ttu-id="f4746-105">使用可能な値が含まれます: 'UserManaged'、'ServiceManaged'</span><span class="sxs-lookup"><span data-stu-id="f4746-105">Possible values include: 'UserManaged', 'ServiceManaged'</span></span></param>
        <param name="keyVaultMetaInfo"><span data-ttu-id="f4746-106">Key Vault については、ユーザーに接続するためには、暗号化キーが管理されます。</span><span class="sxs-lookup"><span data-stu-id="f4746-106">The Key Vault information for connecting to user managed encryption keys.</span></span></param>
        <summary>
            <span data-ttu-id="f4746-107">EncryptionConfig クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f4746-107">Initializes a new instance of the EncryptionConfig class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyVaultMetaInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Store.Models.KeyVaultMetaInfo KeyVaultMetaInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Store.Models.KeyVaultMetaInfo KeyVaultMetaInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfig.KeyVaultMetaInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyVaultMetaInfo As KeyVaultMetaInfo" />
      <MemberSignature Language="F#" Value="member this.KeyVaultMetaInfo : Microsoft.Azure.Management.DataLake.Store.Models.KeyVaultMetaInfo with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfig.KeyVaultMetaInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keyVaultMetaInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.KeyVaultMetaInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f4746-108">取得または暗号化キーの管理ユーザーに接続するためキー コンテナーの情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="f4746-108">Gets or sets the Key Vault information for connecting to user managed encryption keys.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfigType Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfigType Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfig.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As EncryptionConfigType" />
      <MemberSignature Language="F#" Value="member this.Type : Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfigType with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfig.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfigType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f4746-109">取得または使用されている暗号化構成の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="f4746-109">Gets or sets the type of encryption configuration being used.</span></span>
            <span data-ttu-id="f4746-110">現在サポートされている型はのみ 'UserManaged' および 'ServiceManaged' です。</span><span class="sxs-lookup"><span data-stu-id="f4746-110">Currently the only supported types are 'UserManaged' and 'ServiceManaged'.</span></span> <span data-ttu-id="f4746-111">使用可能な値が含まれます: 'UserManaged'、'ServiceManaged'</span><span class="sxs-lookup"><span data-stu-id="f4746-111">Possible values include: 'UserManaged', 'ServiceManaged'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfig.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="encryptionConfig.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f4746-112">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="f4746-112">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4746-113">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4746-113">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>