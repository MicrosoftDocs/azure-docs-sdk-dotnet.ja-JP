<Type Name="IRecoveryServicesClient" FullName="Microsoft.Azure.Management.RecoveryServices.IRecoveryServicesClient">
  <TypeSignature Language="C#" Value="public interface IRecoveryServicesClient : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IRecoveryServicesClient implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.IRecoveryServicesClient" />
  <TypeSignature Language="VB.NET" Value="Public Interface IRecoveryServicesClient&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type IRecoveryServicesClient = interface&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
    <AssemblyVersion>4.2.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            回復サービス クライアントの複合 Swagger
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AcceptLanguage">
      <MemberSignature Language="C#" Value="public string AcceptLanguage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AcceptLanguage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.IRecoveryServicesClient.AcceptLanguage" />
      <MemberSignature Language="VB.NET" Value="Public Property AcceptLanguage As String" />
      <MemberSignature Language="F#" Value="member this.AcceptLanguage : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.IRecoveryServicesClient.AcceptLanguage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または応答の優先言語を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupStorageConfigs">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.IBackupStorageConfigsOperations BackupStorageConfigs { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.IBackupStorageConfigsOperations BackupStorageConfigs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.IRecoveryServicesClient.BackupStorageConfigs" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupStorageConfigs As IBackupStorageConfigsOperations" />
      <MemberSignature Language="F#" Value="member this.BackupStorageConfigs : Microsoft.Azure.Management.RecoveryServices.IBackupStorageConfigsOperations" Usage="Microsoft.Azure.Management.RecoveryServices.IRecoveryServicesClient.BackupStorageConfigs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.IBackupStorageConfigsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            IBackupStorageConfigsOperations を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupVaultConfigs">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.IBackupVaultConfigsOperations BackupVaultConfigs { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.IBackupVaultConfigsOperations BackupVaultConfigs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.IRecoveryServicesClient.BackupVaultConfigs" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupVaultConfigs As IBackupVaultConfigsOperations" />
      <MemberSignature Language="F#" Value="member this.BackupVaultConfigs : Microsoft.Azure.Management.RecoveryServices.IBackupVaultConfigsOperations" Usage="Microsoft.Azure.Management.RecoveryServices.IRecoveryServicesClient.BackupVaultConfigs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.IBackupVaultConfigsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            IBackupVaultConfigsOperations を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.IRecoveryServicesClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.IRecoveryServicesClient.BaseUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            サービスのベース URI。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.ServiceClientCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.ServiceClientCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.IRecoveryServicesClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As ServiceClientCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Rest.ServiceClientCredentials" Usage="Microsoft.Azure.Management.RecoveryServices.IRecoveryServicesClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.ServiceClientCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure に接続するクライアントに必要な資格情報です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeserializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings DeserializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings DeserializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.IRecoveryServicesClient.DeserializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeserializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.DeserializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.RecoveryServices.IRecoveryServicesClient.DeserializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または json に逆シリアル化の設定を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; GenerateClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; GenerateClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.IRecoveryServicesClient.GenerateClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property GenerateClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.GenerateClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.IRecoveryServicesClient.GenerateClientRequestId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            設定すると、一意の x ms-クライアントの要求 id 値を true に生成され、各要求に含まれます。 既定値は true です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.IRecoveryServicesClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.IRecoveryServicesClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または長時間実行される操作の秒単位の再試行タイムアウトを設定します。 既定値は 30 です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Operations">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.IOperations Operations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.IOperations Operations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.IRecoveryServicesClient.Operations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Operations As IOperations" />
      <MemberSignature Language="F#" Value="member this.Operations : Microsoft.Azure.Management.RecoveryServices.IOperations" Usage="Microsoft.Azure.Management.RecoveryServices.IRecoveryServicesClient.Operations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.IOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            IOperations を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisteredIdentities">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.IRegisteredIdentitiesOperations RegisteredIdentities { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.IRegisteredIdentitiesOperations RegisteredIdentities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.IRecoveryServicesClient.RegisteredIdentities" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RegisteredIdentities As IRegisteredIdentitiesOperations" />
      <MemberSignature Language="F#" Value="member this.RegisteredIdentities : Microsoft.Azure.Management.RecoveryServices.IRegisteredIdentitiesOperations" Usage="Microsoft.Azure.Management.RecoveryServices.IRecoveryServicesClient.RegisteredIdentities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.IRegisteredIdentitiesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            IRegisteredIdentitiesOperations を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicationUsages">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.IReplicationUsagesOperations ReplicationUsages { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.IReplicationUsagesOperations ReplicationUsages" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.IRecoveryServicesClient.ReplicationUsages" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicationUsages As IReplicationUsagesOperations" />
      <MemberSignature Language="F#" Value="member this.ReplicationUsages : Microsoft.Azure.Management.RecoveryServices.IReplicationUsagesOperations" Usage="Microsoft.Azure.Management.RecoveryServices.IRecoveryServicesClient.ReplicationUsages" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.IReplicationUsagesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            IReplicationUsagesOperations を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings SerializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings SerializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.IRecoveryServicesClient.SerializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.SerializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.RecoveryServices.IRecoveryServicesClient.SerializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または json のシリアル化設定を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.IRecoveryServicesClient.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.IRecoveryServicesClient.SubscriptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            サブスクリプション id
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Usages">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.IUsagesOperations Usages { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.IUsagesOperations Usages" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.IRecoveryServicesClient.Usages" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Usages As IUsagesOperations" />
      <MemberSignature Language="F#" Value="member this.Usages : Microsoft.Azure.Management.RecoveryServices.IUsagesOperations" Usage="Microsoft.Azure.Management.RecoveryServices.IRecoveryServicesClient.Usages" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.IUsagesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            IUsagesOperations を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VaultCertificates">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.IVaultCertificatesOperations VaultCertificates { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.IVaultCertificatesOperations VaultCertificates" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.IRecoveryServicesClient.VaultCertificates" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VaultCertificates As IVaultCertificatesOperations" />
      <MemberSignature Language="F#" Value="member this.VaultCertificates : Microsoft.Azure.Management.RecoveryServices.IVaultCertificatesOperations" Usage="Microsoft.Azure.Management.RecoveryServices.IRecoveryServicesClient.VaultCertificates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.IVaultCertificatesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            IVaultCertificatesOperations を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VaultExtendedInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.IVaultExtendedInfoOperations VaultExtendedInfo { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.IVaultExtendedInfoOperations VaultExtendedInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.IRecoveryServicesClient.VaultExtendedInfo" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VaultExtendedInfo As IVaultExtendedInfoOperations" />
      <MemberSignature Language="F#" Value="member this.VaultExtendedInfo : Microsoft.Azure.Management.RecoveryServices.IVaultExtendedInfoOperations" Usage="Microsoft.Azure.Management.RecoveryServices.IRecoveryServicesClient.VaultExtendedInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.IVaultExtendedInfoOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            IVaultExtendedInfoOperations を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Vaults">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.IVaultsOperations Vaults { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.IVaultsOperations Vaults" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.IRecoveryServicesClient.Vaults" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Vaults As IVaultsOperations" />
      <MemberSignature Language="F#" Value="member this.Vaults : Microsoft.Azure.Management.RecoveryServices.IVaultsOperations" Usage="Microsoft.Azure.Management.RecoveryServices.IRecoveryServicesClient.Vaults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.IVaultsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            IVaultsOperations を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>