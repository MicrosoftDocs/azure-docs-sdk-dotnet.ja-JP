<Type Name="UpdateKeyVaultMetaInfo" FullName="Microsoft.Azure.Management.DataLake.Store.Models.UpdateKeyVaultMetaInfo">
  <TypeSignature Language="C#" Value="public class UpdateKeyVaultMetaInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit UpdateKeyVaultMetaInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.Models.UpdateKeyVaultMetaInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class UpdateKeyVaultMetaInfo" />
  <TypeSignature Language="F#" Value="type UpdateKeyVaultMetaInfo = class" />
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
            ユーザーに使用 Key Vault の更新情報は、キー ローテーションを管理します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UpdateKeyVaultMetaInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.UpdateKeyVaultMetaInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            UpdateKeyVaultMetaInfo クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UpdateKeyVaultMetaInfo (string encryptionKeyVersion = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string encryptionKeyVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.UpdateKeyVaultMetaInfo.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional encryptionKeyVersion As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Store.Models.UpdateKeyVaultMetaInfo : string -&gt; Microsoft.Azure.Management.DataLake.Store.Models.UpdateKeyVaultMetaInfo" Usage="new Microsoft.Azure.Management.DataLake.Store.Models.UpdateKeyVaultMetaInfo encryptionKeyVersion" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="encryptionKeyVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="encryptionKeyVersion">ユーザーのバージョンでは、キーの交換によって更新する暗号化キーを管理します。</param>
        <summary>
            UpdateKeyVaultMetaInfo クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionKeyVersion">
      <MemberSignature Language="C#" Value="public string EncryptionKeyVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EncryptionKeyVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.UpdateKeyVaultMetaInfo.EncryptionKeyVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptionKeyVersion As String" />
      <MemberSignature Language="F#" Value="member this.EncryptionKeyVersion : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.Models.UpdateKeyVaultMetaInfo.EncryptionKeyVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="encryptionKeyVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはキーの交換を更新するユーザーの管理されている暗号化キーのバージョンを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>