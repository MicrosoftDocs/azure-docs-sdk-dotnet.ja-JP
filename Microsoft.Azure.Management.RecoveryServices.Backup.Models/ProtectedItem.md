<Type Name="ProtectedItem" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItem">
  <TypeSignature Language="C#" Value="public class ProtectedItem" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ProtectedItem extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItem" />
  <TypeSignature Language="VB.NET" Value="Public Class ProtectedItem" />
  <TypeSignature Language="F#" Value="type ProtectedItem = class" />
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
            バックアップ アイテムの基本クラス。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ProtectedItem ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItem.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ProtectedItem クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ProtectedItem (string backupManagementType = null, string workloadType = null, string containerName = null, string sourceResourceId = null, string policyId = null, Nullable&lt;DateTime&gt; lastRecoveryPoint = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string backupManagementType, string workloadType, string containerName, string sourceResourceId, string policyId, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastRecoveryPoint) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItem.#ctor(System.String,System.String,System.String,System.String,System.String,System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional backupManagementType As String = null, Optional workloadType As String = null, Optional containerName As String = null, Optional sourceResourceId As String = null, Optional policyId As String = null, Optional lastRecoveryPoint As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItem : string * string * string * string * string * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItem" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItem (backupManagementType, workloadType, containerName, sourceResourceId, policyId, lastRecoveryPoint)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="backupManagementType" Type="System.String" />
        <Parameter Name="workloadType" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="sourceResourceId" Type="System.String" />
        <Parameter Name="policyId" Type="System.String" />
        <Parameter Name="lastRecoveryPoint" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="backupManagementType">バックアップ managemenent バックアップ項目の種類です。 使用可能な値が含まれます: '無効'、'AzureIaasVM'、'MAB'、'DPM'、'AzureBackupServer'、'仮想'</param>
        <param name="workloadType">この項目を表すワークロードの種類です。
            使用可能な値が含まれます: '無効'、'VM'、'ファイル フォルダー'、'AzureSqlDb'、'SQLDB'、'交換'、'Sharepoint'、'VMwareVM'、'SystemState'、'Client'、'GenericDataSource'</param>
        <param name="containerName">コンテナーの一意の名前</param>
        <param name="sourceResourceId">バックアップするリソースの ARM ID です。</param>
        <param name="policyId">この項目をバックアップするバックアップ ポリシーの ID です。</param>
        <param name="lastRecoveryPoint">このバックアップ アイテムの最後 (最新) のバックアップ コピーが作成されたときのタイムスタンプ。</param>
        <summary>
            ProtectedItem クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupManagementType">
      <MemberSignature Language="C#" Value="public string BackupManagementType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BackupManagementType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItem.BackupManagementType" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupManagementType As String" />
      <MemberSignature Language="F#" Value="member this.BackupManagementType : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItem.BackupManagementType" />
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
            取得またはバックアップ managemenent バックアップ項目の種類を設定します。
            使用可能な値が含まれます: '無効'、'AzureIaasVM'、'MAB'、'DPM'、'AzureBackupServer'、'仮想'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerName">
      <MemberSignature Language="C#" Value="public string ContainerName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContainerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItem.ContainerName" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerName As String" />
      <MemberSignature Language="F#" Value="member this.ContainerName : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItem.ContainerName" />
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
            取得またはコンテナーの一意の名前を設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastRecoveryPoint">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastRecoveryPoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastRecoveryPoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItem.LastRecoveryPoint" />
      <MemberSignature Language="VB.NET" Value="Public Property LastRecoveryPoint As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastRecoveryPoint : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItem.LastRecoveryPoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastRecoveryPoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはこのバックアップ アイテムの最後 (最新) のバックアップ コピーが作成されたときに、タイムスタンプを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PolicyId">
      <MemberSignature Language="C#" Value="public string PolicyId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PolicyId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItem.PolicyId" />
      <MemberSignature Language="VB.NET" Value="Public Property PolicyId As String" />
      <MemberSignature Language="F#" Value="member this.PolicyId : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItem.PolicyId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="policyId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはこの項目をバックアップするバックアップ ポリシーの ID を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceResourceId">
      <MemberSignature Language="C#" Value="public string SourceResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItem.SourceResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceResourceId As String" />
      <MemberSignature Language="F#" Value="member this.SourceResourceId : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItem.SourceResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourceResourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定をバックアップするリソースの ARM ID。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WorkloadType">
      <MemberSignature Language="C#" Value="public string WorkloadType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WorkloadType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItem.WorkloadType" />
      <MemberSignature Language="VB.NET" Value="Public Property WorkloadType As String" />
      <MemberSignature Language="F#" Value="member this.WorkloadType : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItem.WorkloadType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="workloadType")</AttributeName>
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
  </Members>
</Type>