<Type Name="UpdateEncryptionConfig" FullName="Microsoft.Azure.Management.DataLake.Store.Models.UpdateEncryptionConfig">
  <TypeSignature Language="C#" Value="public class UpdateEncryptionConfig" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit UpdateEncryptionConfig extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.Models.UpdateEncryptionConfig" />
  <TypeSignature Language="VB.NET" Value="Public Class UpdateEncryptionConfig" />
  <TypeSignature Language="F#" Value="type UpdateEncryptionConfig = class" />
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
            <span data-ttu-id="11bb1-101">ユーザーを更新するために使用する暗号化の構成は、Key Vault のキーを管理します。</span><span class="sxs-lookup"><span data-stu-id="11bb1-101">The encryption configuration used to update a user managed Key Vault key.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UpdateEncryptionConfig ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.UpdateEncryptionConfig.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="11bb1-102">UpdateEncryptionConfig クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="11bb1-102">Initializes a new instance of the UpdateEncryptionConfig class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UpdateEncryptionConfig (Microsoft.Azure.Management.DataLake.Store.Models.UpdateKeyVaultMetaInfo keyVaultMetaInfo = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.DataLake.Store.Models.UpdateKeyVaultMetaInfo keyVaultMetaInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.UpdateEncryptionConfig.#ctor(Microsoft.Azure.Management.DataLake.Store.Models.UpdateKeyVaultMetaInfo)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional keyVaultMetaInfo As UpdateKeyVaultMetaInfo = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Store.Models.UpdateEncryptionConfig : Microsoft.Azure.Management.DataLake.Store.Models.UpdateKeyVaultMetaInfo -&gt; Microsoft.Azure.Management.DataLake.Store.Models.UpdateEncryptionConfig" Usage="new Microsoft.Azure.Management.DataLake.Store.Models.UpdateEncryptionConfig keyVaultMetaInfo" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="keyVaultMetaInfo" Type="Microsoft.Azure.Management.DataLake.Store.Models.UpdateKeyVaultMetaInfo" />
      </Parameters>
      <Docs>
        <param name="keyVaultMetaInfo"><span data-ttu-id="11bb1-103">ユーザーで使用する更新された Key Vault のキーは、キー ローテーションを管理します。</span><span class="sxs-lookup"><span data-stu-id="11bb1-103">The updated Key Vault key to use in user managed key rotation.</span></span></param>
        <summary>
            <span data-ttu-id="11bb1-104">UpdateEncryptionConfig クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="11bb1-104">Initializes a new instance of the UpdateEncryptionConfig class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyVaultMetaInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Store.Models.UpdateKeyVaultMetaInfo KeyVaultMetaInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Store.Models.UpdateKeyVaultMetaInfo KeyVaultMetaInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.UpdateEncryptionConfig.KeyVaultMetaInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyVaultMetaInfo As UpdateKeyVaultMetaInfo" />
      <MemberSignature Language="F#" Value="member this.KeyVaultMetaInfo : Microsoft.Azure.Management.DataLake.Store.Models.UpdateKeyVaultMetaInfo with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.Models.UpdateEncryptionConfig.KeyVaultMetaInfo" />
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
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.UpdateKeyVaultMetaInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="11bb1-105">取得またはユーザーに管理されるキーのローテーションで使用する更新された Key Vault のキーを設定します。</span><span class="sxs-lookup"><span data-stu-id="11bb1-105">Gets or sets the updated Key Vault key to use in user managed key rotation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>