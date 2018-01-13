<Type Name="BackupResourceConfig" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceConfig">
  <TypeSignature Language="C#" Value="public class BackupResourceConfig" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BackupResourceConfig extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceConfig" />
  <TypeSignature Language="VB.NET" Value="Public Class BackupResourceConfig" />
  <TypeSignature Language="F#" Value="type BackupResourceConfig = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ストレージ リソースの詳細。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupResourceConfig ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceConfig.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            BackupResourceConfig クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupResourceConfig (string storageType = null, string storageTypeState = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string storageType, string storageTypeState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceConfig.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional storageType As String = null, Optional storageTypeState As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceConfig : string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceConfig" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceConfig (storageType, storageTypeState)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageType" Type="System.String" />
        <Parameter Name="storageTypeState" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="storageType">記憶域の種類。 使用可能な値が含まれます: '無効'、'GeoRedundant'、'LocallyRedundant'</param>
        <param name="storageTypeState">ロックまたはロック解除します。 リソースに対して、コンピューターを登録すると、storageTypeState は常にロックされています。 使用可能な値が含まれます: '無効'、'ロック'、'ロックされていない'</param>
        <summary>
            BackupResourceConfig クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageType">
      <MemberSignature Language="C#" Value="public string StorageType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceConfig.StorageType" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageType As String" />
      <MemberSignature Language="F#" Value="member this.StorageType : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceConfig.StorageType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageType")</AttributeName>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceConfig.StorageTypeState" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageTypeState As String" />
      <MemberSignature Language="F#" Value="member this.StorageTypeState : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceConfig.StorageTypeState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageTypeState")</AttributeName>
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