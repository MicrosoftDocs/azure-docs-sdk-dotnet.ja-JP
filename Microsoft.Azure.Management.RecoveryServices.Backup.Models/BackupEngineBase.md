<Type Name="BackupEngineBase" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase">
  <TypeSignature Language="C#" Value="public class BackupEngineBase" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BackupEngineBase extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase" />
  <TypeSignature Language="VB.NET" Value="Public Class BackupEngineBase" />
  <TypeSignature Language="F#" Value="type BackupEngineBase = class" />
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
            バックアップ エンジンが基本クラスです。 すべてのワークロード特定バックアップ エンジンは、このクラスから派生します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupEngineBase ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            BackupEngineBase クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupEngineBase (string friendlyName = null, string backupManagementType = null, string registrationStatus = null, string backupEngineState = null, string healthStatus = null, Nullable&lt;bool&gt; canReRegister = null, string backupEngineId = null, string dpmVersion = null, string azureBackupAgentVersion = null, Nullable&lt;bool&gt; isAzureBackupAgentUpgradeAvailable = null, Nullable&lt;bool&gt; isDPMUpgradeAvailable = null, Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo extendedInfo = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string friendlyName, string backupManagementType, string registrationStatus, string backupEngineState, string healthStatus, valuetype System.Nullable`1&lt;bool&gt; canReRegister, string backupEngineId, string dpmVersion, string azureBackupAgentVersion, valuetype System.Nullable`1&lt;bool&gt; isAzureBackupAgentUpgradeAvailable, valuetype System.Nullable`1&lt;bool&gt; isDPMUpgradeAvailable, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo extendedInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.#ctor(System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.String,System.String,System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional friendlyName As String = null, Optional backupManagementType As String = null, Optional registrationStatus As String = null, Optional backupEngineState As String = null, Optional healthStatus As String = null, Optional canReRegister As Nullable(Of Boolean) = null, Optional backupEngineId As String = null, Optional dpmVersion As String = null, Optional azureBackupAgentVersion As String = null, Optional isAzureBackupAgentUpgradeAvailable As Nullable(Of Boolean) = null, Optional isDPMUpgradeAvailable As Nullable(Of Boolean) = null, Optional extendedInfo As BackupEngineExtendedInfo = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase : string * string * string * string * string * Nullable&lt;bool&gt; * string * string * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase (friendlyName, backupManagementType, registrationStatus, backupEngineState, healthStatus, canReRegister, backupEngineId, dpmVersion, azureBackupAgentVersion, isAzureBackupAgentUpgradeAvailable, isDPMUpgradeAvailable, extendedInfo)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="friendlyName" Type="System.String" />
        <Parameter Name="backupManagementType" Type="System.String" />
        <Parameter Name="registrationStatus" Type="System.String" />
        <Parameter Name="backupEngineState" Type="System.String" />
        <Parameter Name="healthStatus" Type="System.String" />
        <Parameter Name="canReRegister" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="backupEngineId" Type="System.String" />
        <Parameter Name="dpmVersion" Type="System.String" />
        <Parameter Name="azureBackupAgentVersion" Type="System.String" />
        <Parameter Name="isAzureBackupAgentUpgradeAvailable" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="isDPMUpgradeAvailable" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="extendedInfo" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo" />
      </Parameters>
      <Docs>
        <param name="friendlyName">バックアップ エンジンのフレンドリ名。</param>
        <param name="backupManagementType">バックアップ用の管理のバックアップ エンジンの種類。 使用可能な値が含まれます: '無効'、'AzureIaasVM'、'MAB'、'DPM'、'AzureBackupServer'、'仮想'</param>
        <param name="registrationStatus">Recovery Services コンテナーでのバックアップ エンジンの登録状態です。</param>
        <param name="backupEngineState">Recovery Services コンテナーでのバックアップ エンジンの状態です。 {アクティブ/削除/DeleteFailed} を =</param>
        <param name="healthStatus">バックアップ エンジンのバックアップの状態。</param>
        <param name="canReRegister">既に登録されているバックアップ エンジンを登録する場合を示すフラグします。</param>
        <param name="backupEngineId">バックアップ エンジンの ID です。</param>
        <param name="dpmVersion">バックアップ エンジンのバージョン</param>
        <param name="azureBackupAgentVersion">Backup エージェントのバージョン</param>
        <param name="isAzureBackupAgentUpgradeAvailable">場合は backup エージェントが使用可能なアップグレードを確認するには</param>
        <param name="isDPMUpgradeAvailable">場合のバックアップ エンジンが使用可能なアップグレードを確認するには</param>
        <param name="extendedInfo">Backupengine の拡張情報</param>
        <summary>
            BackupEngineBase クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureBackupAgentVersion">
      <MemberSignature Language="C#" Value="public string AzureBackupAgentVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AzureBackupAgentVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.AzureBackupAgentVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureBackupAgentVersion As String" />
      <MemberSignature Language="F#" Value="member this.AzureBackupAgentVersion : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.AzureBackupAgentVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="azureBackupAgentVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Backup エージェントのバージョン取得または設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupEngineId">
      <MemberSignature Language="C#" Value="public string BackupEngineId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BackupEngineId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.BackupEngineId" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupEngineId As String" />
      <MemberSignature Language="F#" Value="member this.BackupEngineId : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.BackupEngineId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="backupEngineId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはバックアップ エンジンの ID を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupEngineState">
      <MemberSignature Language="C#" Value="public string BackupEngineState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BackupEngineState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.BackupEngineState" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupEngineState As String" />
      <MemberSignature Language="F#" Value="member this.BackupEngineState : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.BackupEngineState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="backupEngineState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Recovery Services コンテナーでのバックアップ エンジンの状態を設定します。 {アクティブ/削除/DeleteFailed} を =
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupManagementType">
      <MemberSignature Language="C#" Value="public string BackupManagementType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BackupManagementType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.BackupManagementType" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupManagementType As String" />
      <MemberSignature Language="F#" Value="member this.BackupManagementType : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.BackupManagementType" />
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
            取得またはバックアップ用の管理のバックアップ エンジンの種類を設定します。
            使用可能な値が含まれます: '無効'、'AzureIaasVM'、'MAB'、'DPM'、'AzureBackupServer'、'仮想'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanReRegister">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; CanReRegister { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; CanReRegister" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.CanReRegister" />
      <MemberSignature Language="VB.NET" Value="Public Property CanReRegister As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.CanReRegister : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.CanReRegister" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="canReRegister")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定を示すフラグ バックアップ エンジンを登録する場合は、既に 1 回登録されています。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DpmVersion">
      <MemberSignature Language="C#" Value="public string DpmVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DpmVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.DpmVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property DpmVersion As String" />
      <MemberSignature Language="F#" Value="member this.DpmVersion : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.DpmVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dpmVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定のバックアップ エンジンのバージョン
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExtendedInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo ExtendedInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo ExtendedInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.ExtendedInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property ExtendedInfo As BackupEngineExtendedInfo" />
      <MemberSignature Language="F#" Value="member this.ExtendedInfo : Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.ExtendedInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="extendedInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、backupengine の拡張情報
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FriendlyName">
      <MemberSignature Language="C#" Value="public string FriendlyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FriendlyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.FriendlyName" />
      <MemberSignature Language="VB.NET" Value="Public Property FriendlyName As String" />
      <MemberSignature Language="F#" Value="member this.FriendlyName : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.FriendlyName" />
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
            取得またはバックアップ エンジンのフレンドリ名を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStatus">
      <MemberSignature Language="C#" Value="public string HealthStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HealthStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.HealthStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStatus As String" />
      <MemberSignature Language="F#" Value="member this.HealthStatus : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.HealthStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="healthStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはバックアップ エンジンのバックアップの状態を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsAzureBackupAgentUpgradeAvailable">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsAzureBackupAgentUpgradeAvailable { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsAzureBackupAgentUpgradeAvailable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.IsAzureBackupAgentUpgradeAvailable" />
      <MemberSignature Language="VB.NET" Value="Public Property IsAzureBackupAgentUpgradeAvailable As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsAzureBackupAgentUpgradeAvailable : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.IsAzureBackupAgentUpgradeAvailable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isAzureBackupAgentUpgradeAvailable")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            場合は backup エージェントが使用可能なアップグレードの確認を取得または設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDPMUpgradeAvailable">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsDPMUpgradeAvailable { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsDPMUpgradeAvailable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.IsDPMUpgradeAvailable" />
      <MemberSignature Language="VB.NET" Value="Public Property IsDPMUpgradeAvailable As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsDPMUpgradeAvailable : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.IsDPMUpgradeAvailable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isDPMUpgradeAvailable")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            場合のバックアップ エンジンが使用可能なアップグレードの確認を取得または設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegistrationStatus">
      <MemberSignature Language="C#" Value="public string RegistrationStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RegistrationStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.RegistrationStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property RegistrationStatus As String" />
      <MemberSignature Language="F#" Value="member this.RegistrationStatus : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.RegistrationStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="registrationStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Recovery Services コンテナーでのバックアップ エンジンの登録状態を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>