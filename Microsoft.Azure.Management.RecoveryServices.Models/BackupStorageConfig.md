<Type Name="BackupStorageConfig" FullName="Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig">
  <TypeSignature Language="C#" Value="public class BackupStorageConfig : Microsoft.Azure.Management.RecoveryServices.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BackupStorageConfig extends Microsoft.Azure.Management.RecoveryServices.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig" />
  <TypeSignature Language="VB.NET" Value="Public Class BackupStorageConfig&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type BackupStorageConfig = class&#xA;    inherit Resource" />
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
            バックアップ記憶域の構成。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupStorageConfig ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            BackupStorageConfig クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupStorageConfig (string id = null, string name = null, string type = null, string eTag = null, string storageModelType = null, string storageType = null, string storageTypeState = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string eTag, string storageModelType, string storageType, string storageTypeState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional eTag As String = null, Optional storageModelType As String = null, Optional storageType As String = null, Optional storageTypeState As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig : string * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig" Usage="new Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig (id, name, type, eTag, storageModelType, storageType, storageTypeState)" />
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
        <Parameter Name="storageModelType" Type="System.String" />
        <Parameter Name="storageType" Type="System.String" />
        <Parameter Name="storageTypeState" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">リソース Id は、リソースへの完全なパスを表します。</param>
        <param name="name">リソースに関連付けられているリソースの名前です。</param>
        <param name="type">リソースの種類は Namespace/ResourceType/ResourceType/... 形式の完全なパスを表します</param>
        <param name="eTag">省略可能な ETag です。</param>
        <param name="storageModelType">ストレージ モデルの種類。 使用可能な値が含まれます: '無効'、'GeoRedundant'、'LocallyRedundant'</param>
        <param name="storageType">記憶域の種類。 使用可能な値が含まれます: '無効'、'GeoRedundant'、'LocallyRedundant'</param>
        <param name="storageTypeState">ロックまたはロック解除します。 リソースに対して、コンピューターを登録すると、storageTypeState は常にロックされています。 使用可能な値が含まれます: '無効'、'ロック'、'ロックされていない'</param>
        <summary>
            BackupStorageConfig クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageModelType">
      <MemberSignature Language="C#" Value="public string StorageModelType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageModelType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig.StorageModelType" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageModelType As String" />
      <MemberSignature Language="F#" Value="member this.StorageModelType : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig.StorageModelType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageModelType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはストレージ モデルの種類を設定します。 使用可能な値が含まれます: '無効'、'GeoRedundant'、'LocallyRedundant'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageType">
      <MemberSignature Language="C#" Value="public string StorageType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig.StorageType" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageType As String" />
      <MemberSignature Language="F#" Value="member this.StorageType : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig.StorageType" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig.StorageTypeState" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageTypeState As String" />
      <MemberSignature Language="F#" Value="member this.StorageTypeState : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig.StorageTypeState" />
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