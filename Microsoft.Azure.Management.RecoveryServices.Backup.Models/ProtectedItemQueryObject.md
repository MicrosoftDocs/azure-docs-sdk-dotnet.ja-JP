<Type Name="ProtectedItemQueryObject" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemQueryObject">
  <TypeSignature Language="C#" Value="public class ProtectedItemQueryObject" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ProtectedItemQueryObject extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemQueryObject" />
  <TypeSignature Language="VB.NET" Value="Public Class ProtectedItemQueryObject" />
  <TypeSignature Language="F#" Value="type ProtectedItemQueryObject = class" />
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
            バックアップ項目の一覧をフィルターします。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ProtectedItemQueryObject ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemQueryObject.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ProtectedItemQueryObject クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ProtectedItemQueryObject (string healthState = null, string backupManagementType = null, string itemType = null, string policyName = null, string containerName = null, string backupEngineName = null, string friendlyName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string healthState, string backupManagementType, string itemType, string policyName, string containerName, string backupEngineName, string friendlyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemQueryObject.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional healthState As String = null, Optional backupManagementType As String = null, Optional itemType As String = null, Optional policyName As String = null, Optional containerName As String = null, Optional backupEngineName As String = null, Optional friendlyName As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemQueryObject : string * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemQueryObject" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemQueryObject (healthState, backupManagementType, itemType, policyName, containerName, backupEngineName, friendlyName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="healthState" Type="System.String" />
        <Parameter Name="backupManagementType" Type="System.String" />
        <Parameter Name="itemType" Type="System.String" />
        <Parameter Name="policyName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="backupEngineName" Type="System.String" />
        <Parameter Name="friendlyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="healthState">バックアップ項目の正常性状態。
            使用可能な値が含まれます: '渡さ'、'ActionRequired'、'ActionSuggested'、'無効'</param>
        <param name="backupManagementType">バックアップ項目のバックアップの管理の種類。 使用可能な値が含まれます: '無効'、'AzureIaasVM'、'MAB'、'DPM'、'AzureBackupServer'、'仮想'</param>
        <param name="itemType">この項目を表すワークロードの種類です。
            使用可能な値が含まれます: '無効'、'VM'、'ファイル フォルダー'、'AzureSqlDb'、'SQLDB'、'交換'、'Sharepoint'、'VMwareVM'、'SystemState'、'Client'、'GenericDataSource'</param>
        <param name="policyName">バックアップ項目に関連付けられているバックアップ ポリシーの名前です。</param>
        <param name="containerName">コンテナーの名前です。</param>
        <param name="backupEngineName">バックアップ エンジン名</param>
        <param name="friendlyName">保護されているアイテムの表示名</param>
        <summary>
            ProtectedItemQueryObject クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupEngineName">
      <MemberSignature Language="C#" Value="public string BackupEngineName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BackupEngineName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemQueryObject.BackupEngineName" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupEngineName As String" />
      <MemberSignature Language="F#" Value="member this.BackupEngineName : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemQueryObject.BackupEngineName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="backupEngineName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定のバックアップ エンジン名
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupManagementType">
      <MemberSignature Language="C#" Value="public string BackupManagementType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BackupManagementType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemQueryObject.BackupManagementType" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupManagementType As String" />
      <MemberSignature Language="F#" Value="member this.BackupManagementType : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemQueryObject.BackupManagementType" />
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
            取得またはバックアップ管理項目の種類をバックアップを設定します。
            使用可能な値が含まれます: '無効'、'AzureIaasVM'、'MAB'、'DPM'、'AzureBackupServer'、'仮想'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerName">
      <MemberSignature Language="C#" Value="public string ContainerName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContainerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemQueryObject.ContainerName" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerName As String" />
      <MemberSignature Language="F#" Value="member this.ContainerName : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemQueryObject.ContainerName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="containerName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはコンテナーの名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FriendlyName">
      <MemberSignature Language="C#" Value="public string FriendlyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FriendlyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemQueryObject.FriendlyName" />
      <MemberSignature Language="VB.NET" Value="Public Property FriendlyName As String" />
      <MemberSignature Language="F#" Value="member this.FriendlyName : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemQueryObject.FriendlyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="friendlyName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の保護された項目の表示名
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthState">
      <MemberSignature Language="C#" Value="public string HealthState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HealthState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemQueryObject.HealthState" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthState As String" />
      <MemberSignature Language="F#" Value="member this.HealthState : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemQueryObject.HealthState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="healthState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または作成したバックアップ項目のヘルス状態を設定します。 使用可能な値が含まれます: '渡さ'、'ActionRequired'、'ActionSuggested'、'無効'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ItemType">
      <MemberSignature Language="C#" Value="public string ItemType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ItemType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemQueryObject.ItemType" />
      <MemberSignature Language="VB.NET" Value="Public Property ItemType As String" />
      <MemberSignature Language="F#" Value="member this.ItemType : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemQueryObject.ItemType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="itemType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の種類のワークロードは、この項目を表します。 使用可能な値が含まれます: '無効'、'VM'、'ファイル フォルダー'、'AzureSqlDb'、'SQLDB'、'交換'、'Sharepoint'、'VMwareVM'、'SystemState'、'Client'、'GenericDataSource'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PolicyName">
      <MemberSignature Language="C#" Value="public string PolicyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PolicyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemQueryObject.PolicyName" />
      <MemberSignature Language="VB.NET" Value="Public Property PolicyName As String" />
      <MemberSignature Language="F#" Value="member this.PolicyName : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemQueryObject.PolicyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="policyName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはバックアップの項目に関連付けられているバックアップ ポリシー名を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>