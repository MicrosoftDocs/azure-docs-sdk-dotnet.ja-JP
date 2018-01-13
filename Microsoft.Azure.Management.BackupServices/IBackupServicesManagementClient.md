<Type Name="IBackupServicesManagementClient" FullName="Microsoft.Azure.Management.BackupServices.IBackupServicesManagementClient">
  <TypeSignature Language="C#" Value="public interface IBackupServicesManagementClient : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IBackupServicesManagementClient implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.IBackupServicesManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public Interface IBackupServicesManagementClient&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type IBackupServicesManagementClient = interface&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApiVersion">
      <MemberSignature Language="C#" Value="public string ApiVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApiVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.IBackupServicesManagementClient.ApiVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApiVersion As String" />
      <MemberSignature Language="F#" Value="member this.ApiVersion : string" Usage="Microsoft.Azure.Management.BackupServices.IBackupServicesManagementClient.ApiVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            API のバージョンを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackUp">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BackupServices.IBackUpOperations BackUp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BackupServices.IBackUpOperations BackUp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.IBackupServicesManagementClient.BackUp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackUp As IBackUpOperations" />
      <MemberSignature Language="F#" Value="member this.BackUp : Microsoft.Azure.Management.BackupServices.IBackUpOperations" Usage="Microsoft.Azure.Management.BackupServices.IBackupServicesManagementClient.BackUp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.IBackUpOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Backup の拡張機能のバックアップ操作の定義。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.IBackupServicesManagementClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri" Usage="Microsoft.Azure.Management.BackupServices.IBackupServicesManagementClient.BaseUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            すべてのクラウド サービス要求のベースとして使用する URI を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Container">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BackupServices.IContainerOperations Container { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BackupServices.IContainerOperations Container" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.IBackupServicesManagementClient.Container" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Container As IContainerOperations" />
      <MemberSignature Language="F#" Value="member this.Container : Microsoft.Azure.Management.BackupServices.IContainerOperations" Usage="Microsoft.Azure.Management.BackupServices.IBackupServicesManagementClient.Container" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.IContainerOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Backup の拡張機能のコンテナーの操作の定義。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SubscriptionCloudCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.SubscriptionCloudCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.IBackupServicesManagementClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As SubscriptionCloudCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Azure.SubscriptionCloudCredentials" Usage="Microsoft.Azure.Management.BackupServices.IBackupServicesManagementClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SubscriptionCloudCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Microsoft Azure サブスクリプションを一意に識別するサブスクリプション資格情報を取得します。 サブスクリプション ID では、すべてのサービス呼び出しの URI の一部を形成します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CSMProtectionPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations CSMProtectionPolicy { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations CSMProtectionPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.IBackupServicesManagementClient.CSMProtectionPolicy" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CSMProtectionPolicy As ICSMProtectionPolicyOperations" />
      <MemberSignature Language="F#" Value="member this.CSMProtectionPolicy : Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations" Usage="Microsoft.Azure.Management.BackupServices.IBackupServicesManagementClient.CSMProtectionPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Backup の拡張機能の保護ポリシーの操作の定義。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataSource">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BackupServices.IDataSourceOperations DataSource { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BackupServices.IDataSourceOperations DataSource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.IBackupServicesManagementClient.DataSource" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DataSource As IDataSourceOperations" />
      <MemberSignature Language="F#" Value="member this.DataSource : Microsoft.Azure.Management.BackupServices.IDataSourceOperations" Usage="Microsoft.Azure.Management.BackupServices.IBackupServicesManagementClient.DataSource" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.IDataSourceOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Backup の拡張機能の操作をデータ ソースの定義。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Job">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BackupServices.IJobOperations Job { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BackupServices.IJobOperations Job" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.IBackupServicesManagementClient.Job" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Job As IJobOperations" />
      <MemberSignature Language="F#" Value="member this.Job : Microsoft.Azure.Management.BackupServices.IJobOperations" Usage="Microsoft.Azure.Management.BackupServices.IBackupServicesManagementClient.Job" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.IJobOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure バックアップ用拡張子に対してジョブ操作の定義。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationInitialTimeout">
      <MemberSignature Language="C#" Value="public int LongRunningOperationInitialTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 LongRunningOperationInitialTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.IBackupServicesManagementClient.LongRunningOperationInitialTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationInitialTimeout As Integer" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationInitialTimeout : int with get, set" Usage="Microsoft.Azure.Management.BackupServices.IBackupServicesManagementClient.LongRunningOperationInitialTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または長時間実行される操作の初期タイムアウトを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public int LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.IBackupServicesManagementClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Integer" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : int with get, set" Usage="Microsoft.Azure.Management.BackupServices.IBackupServicesManagementClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または長時間実行される操作の再試行タイムアウトを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationStatus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BackupServices.IOperationStatus OperationStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BackupServices.IOperationStatus OperationStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.IBackupServicesManagementClient.OperationStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OperationStatus As IOperationStatus" />
      <MemberSignature Language="F#" Value="member this.OperationStatus : Microsoft.Azure.Management.BackupServices.IOperationStatus" Usage="Microsoft.Azure.Management.BackupServices.IBackupServicesManagementClient.OperationStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.IOperationStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Backup の拡張機能のワークフロー操作の定義。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectableObject">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BackupServices.IProtectableObjectOperations ProtectableObject { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BackupServices.IProtectableObjectOperations ProtectableObject" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.IBackupServicesManagementClient.ProtectableObject" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProtectableObject As IProtectableObjectOperations" />
      <MemberSignature Language="F#" Value="member this.ProtectableObject : Microsoft.Azure.Management.BackupServices.IProtectableObjectOperations" Usage="Microsoft.Azure.Management.BackupServices.IBackupServicesManagementClient.ProtectableObject" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.IProtectableObjectOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Backup の拡張機能の保護可能な ObjectOperation 操作の定義。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoveryPoint">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BackupServices.IRecoveryPointOperations RecoveryPoint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BackupServices.IRecoveryPointOperations RecoveryPoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.IBackupServicesManagementClient.RecoveryPoint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RecoveryPoint As IRecoveryPointOperations" />
      <MemberSignature Language="F#" Value="member this.RecoveryPoint : Microsoft.Azure.Management.BackupServices.IRecoveryPointOperations" Usage="Microsoft.Azure.Management.BackupServices.IBackupServicesManagementClient.RecoveryPoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.IRecoveryPointOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Backup の拡張機能の回復ポイントの操作の定義。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Restore">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BackupServices.IRestoreOperations Restore { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BackupServices.IRestoreOperations Restore" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.IBackupServicesManagementClient.Restore" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Restore As IRestoreOperations" />
      <MemberSignature Language="F#" Value="member this.Restore : Microsoft.Azure.Management.BackupServices.IRestoreOperations" Usage="Microsoft.Azure.Management.BackupServices.IBackupServicesManagementClient.Restore" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.IRestoreOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Backup の拡張機能の復元操作の定義。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>