<Type Name="ProtectionPolicyQueryObject" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyQueryObject">
  <TypeSignature Language="C#" Value="public class ProtectionPolicyQueryObject" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ProtectionPolicyQueryObject extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyQueryObject" />
  <TypeSignature Language="VB.NET" Value="Public Class ProtectionPolicyQueryObject" />
  <TypeSignature Language="F#" Value="type ProtectionPolicyQueryObject = class" />
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
            一覧のバックアップ ポリシー API をフィルター処理します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ProtectionPolicyQueryObject ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyQueryObject.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ProtectionPolicyQueryObject クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ProtectionPolicyQueryObject (string backupManagementType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string backupManagementType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyQueryObject.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional backupManagementType As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyQueryObject : string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyQueryObject" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyQueryObject backupManagementType" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="backupManagementType" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="backupManagementType">バックアップ ポリシーのバックアップの管理の種類。 使用可能な値が含まれます: '無効'、'AzureIaasVM'、'MAB'、'DPM'、'AzureBackupServer'、'仮想'</param>
        <summary>
            ProtectionPolicyQueryObject クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupManagementType">
      <MemberSignature Language="C#" Value="public string BackupManagementType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BackupManagementType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyQueryObject.BackupManagementType" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupManagementType As String" />
      <MemberSignature Language="F#" Value="member this.BackupManagementType : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyQueryObject.BackupManagementType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="backupManagementType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはバックアップ ポリシーのバックアップの管理の種類を設定します。 使用可能な値が含まれます: '無効'、'AzureIaasVM'、'MAB'、'DPM'、'AzureBackupServer'、'仮想'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>