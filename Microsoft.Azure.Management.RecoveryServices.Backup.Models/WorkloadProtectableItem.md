<Type Name="WorkloadProtectableItem" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItem">
  <TypeSignature Language="C#" Value="public class WorkloadProtectableItem" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WorkloadProtectableItem extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItem" />
  <TypeSignature Language="VB.NET" Value="Public Class WorkloadProtectableItem" />
  <TypeSignature Language="F#" Value="type WorkloadProtectableItem = class" />
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
            バックアップ項目の基本クラス。 ワークロードに固有のバックアップ アイテムは、このクラスから派生します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WorkloadProtectableItem ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItem.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            WorkloadProtectableItem クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WorkloadProtectableItem (string backupManagementType = null, string friendlyName = null, string protectionState = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string backupManagementType, string friendlyName, string protectionState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItem.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional backupManagementType As String = null, Optional friendlyName As String = null, Optional protectionState As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItem : string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItem" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItem (backupManagementType, friendlyName, protectionState)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="backupManagementType" Type="System.String" />
        <Parameter Name="friendlyName" Type="System.String" />
        <Parameter Name="protectionState" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="backupManagementType">項目をバックアップするバックアップ managemenent の型。</param>
        <param name="friendlyName">バックアップ項目の表示名。</param>
        <param name="protectionState">項目のバックアップの状態です。 使用可能な値が含まれます: '無効'、'NotProtected'、'を保護する'、'Protected'</param>
        <summary>
            WorkloadProtectableItem クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupManagementType">
      <MemberSignature Language="C#" Value="public string BackupManagementType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BackupManagementType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItem.BackupManagementType" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupManagementType As String" />
      <MemberSignature Language="F#" Value="member this.BackupManagementType : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItem.BackupManagementType" />
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
            取得または項目をバックアップするバックアップ managemenent の種類を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FriendlyName">
      <MemberSignature Language="C#" Value="public string FriendlyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FriendlyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItem.FriendlyName" />
      <MemberSignature Language="VB.NET" Value="Public Property FriendlyName As String" />
      <MemberSignature Language="F#" Value="member this.FriendlyName : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItem.FriendlyName" />
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
            取得またはバックアップ アイテムの表示名を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectionState">
      <MemberSignature Language="C#" Value="public string ProtectionState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProtectionState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItem.ProtectionState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProtectionState As String" />
      <MemberSignature Language="F#" Value="member this.ProtectionState : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItem.ProtectionState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="protectionState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または項目のバックアップの状態を設定します。 使用可能な値が含まれます: '無効'、'NotProtected'、'を保護する'、'Protected'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>