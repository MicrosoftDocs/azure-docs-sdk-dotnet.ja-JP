<Type Name="IRecoveryServicesBackupClient" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient">
  <TypeSignature Language="C#" Value="public interface IRecoveryServicesBackupClient : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IRecoveryServicesBackupClient implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient" />
  <TypeSignature Language="VB.NET" Value="Public Interface IRecoveryServicesBackupClient&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type IRecoveryServicesBackupClient = interface&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="75722-101">Azure RecoveryServices バックアップ サービスの API 2.0 の仕様を開く</span><span class="sxs-lookup"><span data-stu-id="75722-101">Open API 2.0 Specs for Azure RecoveryServices Backup service</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AcceptLanguage">
      <MemberSignature Language="C#" Value="public string AcceptLanguage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AcceptLanguage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.AcceptLanguage" />
      <MemberSignature Language="VB.NET" Value="Public Property AcceptLanguage As String" />
      <MemberSignature Language="F#" Value="member this.AcceptLanguage : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.AcceptLanguage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="75722-102">取得または応答の優先言語を設定します。</span><span class="sxs-lookup"><span data-stu-id="75722-102">Gets or sets the preferred language for the response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupEngines">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations BackupEngines { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations BackupEngines" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.BackupEngines" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupEngines As IBackupEnginesOperations" />
      <MemberSignature Language="F#" Value="member this.BackupEngines : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.BackupEngines" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="75722-103">IBackupEnginesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="75722-103">Gets the IBackupEnginesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupJobs">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IBackupJobsOperations BackupJobs { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupJobsOperations BackupJobs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.BackupJobs" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupJobs As IBackupJobsOperations" />
      <MemberSignature Language="F#" Value="member this.BackupJobs : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupJobsOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.BackupJobs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IBackupJobsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="75722-104">IBackupJobsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="75722-104">Gets the IBackupJobsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupOperationResults">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationResultsOperations BackupOperationResults { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationResultsOperations BackupOperationResults" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.BackupOperationResults" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupOperationResults As IBackupOperationResultsOperations" />
      <MemberSignature Language="F#" Value="member this.BackupOperationResults : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationResultsOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.BackupOperationResults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationResultsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="75722-105">IBackupOperationResultsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="75722-105">Gets the IBackupOperationResultsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupOperationStatuses">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationStatusesOperations BackupOperationStatuses { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationStatusesOperations BackupOperationStatuses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.BackupOperationStatuses" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupOperationStatuses As IBackupOperationStatusesOperations" />
      <MemberSignature Language="F#" Value="member this.BackupOperationStatuses : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationStatusesOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.BackupOperationStatuses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationStatusesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="75722-106">IBackupOperationStatusesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="75722-106">Gets the IBackupOperationStatusesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupPolicies">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IBackupPoliciesOperations BackupPolicies { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupPoliciesOperations BackupPolicies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.BackupPolicies" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupPolicies As IBackupPoliciesOperations" />
      <MemberSignature Language="F#" Value="member this.BackupPolicies : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupPoliciesOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.BackupPolicies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IBackupPoliciesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="75722-107">IBackupPoliciesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="75722-107">Gets the IBackupPoliciesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupProtectableItems">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectableItemsOperations BackupProtectableItems { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectableItemsOperations BackupProtectableItems" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.BackupProtectableItems" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupProtectableItems As IBackupProtectableItemsOperations" />
      <MemberSignature Language="F#" Value="member this.BackupProtectableItems : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectableItemsOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.BackupProtectableItems" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectableItemsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="75722-108">IBackupProtectableItemsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="75722-108">Gets the IBackupProtectableItemsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupProtectedItems">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectedItemsOperations BackupProtectedItems { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectedItemsOperations BackupProtectedItems" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.BackupProtectedItems" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupProtectedItems As IBackupProtectedItemsOperations" />
      <MemberSignature Language="F#" Value="member this.BackupProtectedItems : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectedItemsOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.BackupProtectedItems" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectedItemsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="75722-109">IBackupProtectedItemsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="75722-109">Gets the IBackupProtectedItemsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupProtectionContainers">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectionContainersOperations BackupProtectionContainers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectionContainersOperations BackupProtectionContainers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.BackupProtectionContainers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupProtectionContainers As IBackupProtectionContainersOperations" />
      <MemberSignature Language="F#" Value="member this.BackupProtectionContainers : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectionContainersOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.BackupProtectionContainers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectionContainersOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="75722-110">IBackupProtectionContainersOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="75722-110">Gets the IBackupProtectionContainersOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupResourceStorageConfigs">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceStorageConfigsOperations BackupResourceStorageConfigs { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceStorageConfigsOperations BackupResourceStorageConfigs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.BackupResourceStorageConfigs" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupResourceStorageConfigs As IBackupResourceStorageConfigsOperations" />
      <MemberSignature Language="F#" Value="member this.BackupResourceStorageConfigs : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceStorageConfigsOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.BackupResourceStorageConfigs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceStorageConfigsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="75722-111">IBackupResourceStorageConfigsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="75722-111">Gets the IBackupResourceStorageConfigsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupResourceVaultConfigs">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceVaultConfigsOperations BackupResourceVaultConfigs { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceVaultConfigsOperations BackupResourceVaultConfigs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.BackupResourceVaultConfigs" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupResourceVaultConfigs As IBackupResourceVaultConfigsOperations" />
      <MemberSignature Language="F#" Value="member this.BackupResourceVaultConfigs : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceVaultConfigsOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.BackupResourceVaultConfigs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceVaultConfigsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="75722-112">IBackupResourceVaultConfigsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="75722-112">Gets the IBackupResourceVaultConfigsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Backups">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IBackupsOperations Backups { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupsOperations Backups" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.Backups" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Backups As IBackupsOperations" />
      <MemberSignature Language="F#" Value="member this.Backups : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupsOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.Backups" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IBackupsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="75722-113">IBackupsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="75722-113">Gets the IBackupsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupUsageSummaries">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IBackupUsageSummariesOperations BackupUsageSummaries { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupUsageSummariesOperations BackupUsageSummaries" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.BackupUsageSummaries" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupUsageSummaries As IBackupUsageSummariesOperations" />
      <MemberSignature Language="F#" Value="member this.BackupUsageSummaries : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupUsageSummariesOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.BackupUsageSummaries" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IBackupUsageSummariesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="75722-114">IBackupUsageSummariesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="75722-114">Gets the IBackupUsageSummariesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.BaseUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="75722-115">サービスのベース URI。</span><span class="sxs-lookup"><span data-stu-id="75722-115">The base URI of the service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.ServiceClientCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.ServiceClientCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As ServiceClientCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Rest.ServiceClientCredentials" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.ServiceClientCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="75722-116">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="75722-116">Credentials needed for the client to connect to Azure.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeserializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings DeserializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings DeserializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.DeserializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeserializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.DeserializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.DeserializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="75722-117">取得または json に逆シリアル化の設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="75722-117">Gets or sets json deserialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportJobsOperationResults">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IExportJobsOperationResultsOperations ExportJobsOperationResults { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IExportJobsOperationResultsOperations ExportJobsOperationResults" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.ExportJobsOperationResults" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExportJobsOperationResults As IExportJobsOperationResultsOperations" />
      <MemberSignature Language="F#" Value="member this.ExportJobsOperationResults : Microsoft.Azure.Management.RecoveryServices.Backup.IExportJobsOperationResultsOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.ExportJobsOperationResults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IExportJobsOperationResultsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="75722-118">IExportJobsOperationResultsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="75722-118">Gets the IExportJobsOperationResultsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; GenerateClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; GenerateClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.GenerateClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property GenerateClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.GenerateClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.GenerateClientRequestId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="75722-119">設定すると、一意の x ms-クライアントの要求 id 値を true に生成され、各要求に含まれます。</span><span class="sxs-lookup"><span data-stu-id="75722-119">When set to true a unique x-ms-client-request-id value is generated and included in each request.</span></span> <span data-ttu-id="75722-120">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="75722-120">Default is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ItemLevelRecoveryConnections">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations ItemLevelRecoveryConnections { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations ItemLevelRecoveryConnections" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.ItemLevelRecoveryConnections" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ItemLevelRecoveryConnections As IItemLevelRecoveryConnectionsOperations" />
      <MemberSignature Language="F#" Value="member this.ItemLevelRecoveryConnections : Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.ItemLevelRecoveryConnections" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="75722-121">IItemLevelRecoveryConnectionsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="75722-121">Gets the IItemLevelRecoveryConnectionsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobCancellations">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IJobCancellationsOperations JobCancellations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IJobCancellationsOperations JobCancellations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.JobCancellations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property JobCancellations As IJobCancellationsOperations" />
      <MemberSignature Language="F#" Value="member this.JobCancellations : Microsoft.Azure.Management.RecoveryServices.Backup.IJobCancellationsOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.JobCancellations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IJobCancellationsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="75722-122">IJobCancellationsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="75722-122">Gets the IJobCancellationsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobDetails">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IJobDetailsOperations JobDetails { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IJobDetailsOperations JobDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.JobDetails" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property JobDetails As IJobDetailsOperations" />
      <MemberSignature Language="F#" Value="member this.JobDetails : Microsoft.Azure.Management.RecoveryServices.Backup.IJobDetailsOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.JobDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IJobDetailsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="75722-123">IJobDetailsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="75722-123">Gets the IJobDetailsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobOperationResults">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IJobOperationResultsOperations JobOperationResults { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IJobOperationResultsOperations JobOperationResults" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.JobOperationResults" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property JobOperationResults As IJobOperationResultsOperations" />
      <MemberSignature Language="F#" Value="member this.JobOperationResults : Microsoft.Azure.Management.RecoveryServices.Backup.IJobOperationResultsOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.JobOperationResults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IJobOperationResultsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="75722-124">IJobOperationResultsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="75722-124">Gets the IJobOperationResultsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Jobs">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IJobsOperations Jobs { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IJobsOperations Jobs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.Jobs" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Jobs As IJobsOperations" />
      <MemberSignature Language="F#" Value="member this.Jobs : Microsoft.Azure.Management.RecoveryServices.Backup.IJobsOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.Jobs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IJobsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="75722-125">IJobsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="75722-125">Gets the IJobsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="75722-126">取得または長時間実行される操作の秒単位の再試行タイムアウトを設定します。</span><span class="sxs-lookup"><span data-stu-id="75722-126">Gets or sets the retry timeout in seconds for Long Running Operations.</span></span> <span data-ttu-id="75722-127">既定値は 30 です。</span><span class="sxs-lookup"><span data-stu-id="75722-127">Default value is 30.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Operations">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IOperations Operations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IOperations Operations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.Operations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Operations As IOperations" />
      <MemberSignature Language="F#" Value="member this.Operations : Microsoft.Azure.Management.RecoveryServices.Backup.IOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.Operations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="75722-128">IOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="75722-128">Gets the IOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectedItemOperationResults">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationResultsOperations ProtectedItemOperationResults { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationResultsOperations ProtectedItemOperationResults" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.ProtectedItemOperationResults" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProtectedItemOperationResults As IProtectedItemOperationResultsOperations" />
      <MemberSignature Language="F#" Value="member this.ProtectedItemOperationResults : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationResultsOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.ProtectedItemOperationResults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationResultsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="75722-129">IProtectedItemOperationResultsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="75722-129">Gets the IProtectedItemOperationResultsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectedItemOperationStatuses">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationStatusesOperations ProtectedItemOperationStatuses { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationStatusesOperations ProtectedItemOperationStatuses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.ProtectedItemOperationStatuses" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProtectedItemOperationStatuses As IProtectedItemOperationStatusesOperations" />
      <MemberSignature Language="F#" Value="member this.ProtectedItemOperationStatuses : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationStatusesOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.ProtectedItemOperationStatuses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationStatusesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="75722-130">IProtectedItemOperationStatusesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="75722-130">Gets the IProtectedItemOperationStatusesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectedItems">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations ProtectedItems { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations ProtectedItems" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.ProtectedItems" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProtectedItems As IProtectedItemsOperations" />
      <MemberSignature Language="F#" Value="member this.ProtectedItems : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.ProtectedItems" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="75722-131">IProtectedItemsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="75722-131">Gets the IProtectedItemsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectionContainerOperationResults">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainerOperationResultsOperations ProtectionContainerOperationResults { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainerOperationResultsOperations ProtectionContainerOperationResults" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.ProtectionContainerOperationResults" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProtectionContainerOperationResults As IProtectionContainerOperationResultsOperations" />
      <MemberSignature Language="F#" Value="member this.ProtectionContainerOperationResults : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainerOperationResultsOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.ProtectionContainerOperationResults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainerOperationResultsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="75722-132">IProtectionContainerOperationResultsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="75722-132">Gets the IProtectionContainerOperationResultsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectionContainerRefreshOperationResults">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainerRefreshOperationResultsOperations ProtectionContainerRefreshOperationResults { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainerRefreshOperationResultsOperations ProtectionContainerRefreshOperationResults" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.ProtectionContainerRefreshOperationResults" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProtectionContainerRefreshOperationResults As IProtectionContainerRefreshOperationResultsOperations" />
      <MemberSignature Language="F#" Value="member this.ProtectionContainerRefreshOperationResults : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainerRefreshOperationResultsOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.ProtectionContainerRefreshOperationResults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainerRefreshOperationResultsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="75722-133">IProtectionContainerRefreshOperationResultsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="75722-133">Gets the IProtectionContainerRefreshOperationResultsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectionContainers">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainersOperations ProtectionContainers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainersOperations ProtectionContainers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.ProtectionContainers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProtectionContainers As IProtectionContainersOperations" />
      <MemberSignature Language="F#" Value="member this.ProtectionContainers : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainersOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.ProtectionContainers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainersOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="75722-134">IProtectionContainersOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="75722-134">Gets the IProtectionContainersOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectionPolicies">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations ProtectionPolicies { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations ProtectionPolicies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.ProtectionPolicies" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProtectionPolicies As IProtectionPoliciesOperations" />
      <MemberSignature Language="F#" Value="member this.ProtectionPolicies : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.ProtectionPolicies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="75722-135">IProtectionPoliciesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="75722-135">Gets the IProtectionPoliciesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectionPolicyOperationResults">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPolicyOperationResultsOperations ProtectionPolicyOperationResults { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPolicyOperationResultsOperations ProtectionPolicyOperationResults" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.ProtectionPolicyOperationResults" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProtectionPolicyOperationResults As IProtectionPolicyOperationResultsOperations" />
      <MemberSignature Language="F#" Value="member this.ProtectionPolicyOperationResults : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPolicyOperationResultsOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.ProtectionPolicyOperationResults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPolicyOperationResultsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="75722-136">IProtectionPolicyOperationResultsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="75722-136">Gets the IProtectionPolicyOperationResultsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectionPolicyOperationStatuses">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPolicyOperationStatusesOperations ProtectionPolicyOperationStatuses { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPolicyOperationStatusesOperations ProtectionPolicyOperationStatuses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.ProtectionPolicyOperationStatuses" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProtectionPolicyOperationStatuses As IProtectionPolicyOperationStatusesOperations" />
      <MemberSignature Language="F#" Value="member this.ProtectionPolicyOperationStatuses : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPolicyOperationStatusesOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.ProtectionPolicyOperationStatuses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPolicyOperationStatusesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="75722-137">IProtectionPolicyOperationStatusesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="75722-137">Gets the IProtectionPolicyOperationStatusesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoveryPoints">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations RecoveryPoints { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations RecoveryPoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.RecoveryPoints" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RecoveryPoints As IRecoveryPointsOperations" />
      <MemberSignature Language="F#" Value="member this.RecoveryPoints : Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.RecoveryPoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="75722-138">IRecoveryPointsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="75722-138">Gets the IRecoveryPointsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Restores">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.IRestoresOperations Restores { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.IRestoresOperations Restores" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.Restores" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Restores As IRestoresOperations" />
      <MemberSignature Language="F#" Value="member this.Restores : Microsoft.Azure.Management.RecoveryServices.Backup.IRestoresOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.Restores" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.IRestoresOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="75722-139">IRestoresOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="75722-139">Gets the IRestoresOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecurityPINs">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.ISecurityPINsOperations SecurityPINs { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.ISecurityPINsOperations SecurityPINs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.SecurityPINs" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SecurityPINs As ISecurityPINsOperations" />
      <MemberSignature Language="F#" Value="member this.SecurityPINs : Microsoft.Azure.Management.RecoveryServices.Backup.ISecurityPINsOperations" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.SecurityPINs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.ISecurityPINsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="75722-140">ISecurityPINsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="75722-140">Gets the ISecurityPINsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings SerializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings SerializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.SerializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.SerializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.SerializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="75722-141">取得または json のシリアル化設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="75722-141">Gets or sets json serialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryServicesBackupClient.SubscriptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="75722-142">サブスクリプション id</span><span class="sxs-lookup"><span data-stu-id="75722-142">The subscription Id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>