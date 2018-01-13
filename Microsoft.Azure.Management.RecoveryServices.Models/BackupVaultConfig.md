<Type Name="BackupVaultConfig" FullName="Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig">
  <TypeSignature Language="C#" Value="public class BackupVaultConfig : Microsoft.Azure.Management.RecoveryServices.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BackupVaultConfig extends Microsoft.Azure.Management.RecoveryServices.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig" />
  <TypeSignature Language="VB.NET" Value="Public Class BackupVaultConfig&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type BackupVaultConfig = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
    <AssemblyVersion>4.2.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.RecoveryServices.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            バックアップ コンテナーの構成に関する詳細。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupVaultConfig ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            BackupVaultConfig クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupVaultConfig (string id = null, string name = null, string type = null, string eTag = null, string storageType = null, string storageTypeState = null, string enhancedSecurityState = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string eTag, string storageType, string storageTypeState, string enhancedSecurityState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional eTag As String = null, Optional storageType As String = null, Optional storageTypeState As String = null, Optional enhancedSecurityState As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig : string * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig" Usage="new Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig (id, name, type, eTag, storageType, storageTypeState, enhancedSecurityState)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="eTag" Type="System.String" />
        <Parameter Name="storageType" Type="System.String" />
        <Parameter Name="storageTypeState" Type="System.String" />
        <Parameter Name="enhancedSecurityState" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">リソース Id は、リソースへの完全なパスを表します。</param>
        <param name="name">リソースに関連付けられているリソースの名前です。</param>
        <param name="type">リソースの種類は Namespace/ResourceType/ResourceType/... 形式の完全なパスを表します</param>
        <param name="eTag">省略可能な ETag です。</param>
        <param name="storageType">記憶域の種類。 使用可能な値が含まれます: '無効'、'GeoRedundant'、'LocallyRedundant'</param>
        <param name="storageTypeState">ロックまたはロック解除します。 リソースに対して、コンピューターを登録すると、storageTypeState は常にロックされています。 使用可能な値が含まれます: '無効'、'ロック'、'ロックされていない'</param>
        <param name="enhancedSecurityState">有効または無効にします。 使用可能な値が含まれます: '無効'、'Enabled'、'Disabled'</param>
        <summary>
            BackupVaultConfig クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnhancedSecurityState">
      <MemberSignature Language="C#" Value="public string EnhancedSecurityState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EnhancedSecurityState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig.EnhancedSecurityState" />
      <MemberSignature Language="VB.NET" Value="Public Property EnhancedSecurityState As String" />
      <MemberSignature Language="F#" Value="member this.EnhancedSecurityState : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig.EnhancedSecurityState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enhancedSecurityState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、有効または無効に設定します。 使用可能な値が含まれます: '無効'、'Enabled'、'Disabled'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageType">
      <MemberSignature Language="C#" Value="public string StorageType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig.StorageType" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageType As String" />
      <MemberSignature Language="F#" Value="member this.StorageType : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig.StorageType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または記憶域の種類を設定します。 使用可能な値が含まれます: '無効'、'GeoRedundant'、'LocallyRedundant'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageTypeState">
      <MemberSignature Language="C#" Value="public string StorageTypeState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageTypeState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig.StorageTypeState" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageTypeState As String" />
      <MemberSignature Language="F#" Value="member this.StorageTypeState : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig.StorageTypeState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageTypeState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはロックまたはロック解除を設定します。 リソースに対して、コンピューターを登録すると、storageTypeState は常にロックされています。 使用可能な値が含まれます: '無効'、'ロック'、'ロックされていない'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>