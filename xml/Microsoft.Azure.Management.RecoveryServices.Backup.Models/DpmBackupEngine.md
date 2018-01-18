<Type Name="DpmBackupEngine" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmBackupEngine">
  <TypeSignature Language="C#" Value="public class DpmBackupEngine : Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DpmBackupEngine extends Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmBackupEngine" />
  <TypeSignature Language="VB.NET" Value="Public Class DpmBackupEngine&#xA;Inherits BackupEngineBase" />
  <TypeSignature Language="F#" Value="type DpmBackupEngine = class&#xA;    inherit BackupEngineBase" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7e0a6-101">データ保護マネージャー (DPM) 特定バックアップ エンジンです。</span><span class="sxs-lookup"><span data-stu-id="7e0a6-101">Data Protection Manager (DPM) specific backup engine.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DpmBackupEngine ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmBackupEngine.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7e0a6-102">DpmBackupEngine クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7e0a6-102">Initializes a new instance of the DpmBackupEngine class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DpmBackupEngine (string friendlyName = null, string backupManagementType = null, string registrationStatus = null, string backupEngineState = null, string healthStatus = null, Nullable&lt;bool&gt; canReRegister = null, string backupEngineId = null, string dpmVersion = null, string azureBackupAgentVersion = null, Nullable&lt;bool&gt; isAzureBackupAgentUpgradeAvailable = null, Nullable&lt;bool&gt; isDPMUpgradeAvailable = null, Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo extendedInfo = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string friendlyName, string backupManagementType, string registrationStatus, string backupEngineState, string healthStatus, valuetype System.Nullable`1&lt;bool&gt; canReRegister, string backupEngineId, string dpmVersion, string azureBackupAgentVersion, valuetype System.Nullable`1&lt;bool&gt; isAzureBackupAgentUpgradeAvailable, valuetype System.Nullable`1&lt;bool&gt; isDPMUpgradeAvailable, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo extendedInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmBackupEngine.#ctor(System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.String,System.String,System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional friendlyName As String = null, Optional backupManagementType As String = null, Optional registrationStatus As String = null, Optional backupEngineState As String = null, Optional healthStatus As String = null, Optional canReRegister As Nullable(Of Boolean) = null, Optional backupEngineId As String = null, Optional dpmVersion As String = null, Optional azureBackupAgentVersion As String = null, Optional isAzureBackupAgentUpgradeAvailable As Nullable(Of Boolean) = null, Optional isDPMUpgradeAvailable As Nullable(Of Boolean) = null, Optional extendedInfo As BackupEngineExtendedInfo = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmBackupEngine : string * string * string * string * string * Nullable&lt;bool&gt; * string * string * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmBackupEngine" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmBackupEngine (friendlyName, backupManagementType, registrationStatus, backupEngineState, healthStatus, canReRegister, backupEngineId, dpmVersion, azureBackupAgentVersion, isAzureBackupAgentUpgradeAvailable, isDPMUpgradeAvailable, extendedInfo)" />
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
        <param name="friendlyName"><span data-ttu-id="7e0a6-103">バックアップ エンジンのフレンドリ名。</span><span class="sxs-lookup"><span data-stu-id="7e0a6-103">Friendly name of the backup engine.</span></span></param>
        <param name="backupManagementType"><span data-ttu-id="7e0a6-104">バックアップ用の管理のバックアップ エンジンの種類。</span><span class="sxs-lookup"><span data-stu-id="7e0a6-104">Type of backup management for the backup engine.</span></span> <span data-ttu-id="7e0a6-105">使用可能な値が含まれます: '無効'、'AzureIaasVM'、'MAB'、'DPM'、'AzureBackupServer'、'仮想'</span><span class="sxs-lookup"><span data-stu-id="7e0a6-105">Possible values include: 'Invalid', 'AzureIaasVM', 'MAB', 'DPM', 'AzureBackupServer', 'AzureSql'</span></span></param>
        <param name="registrationStatus"><span data-ttu-id="7e0a6-106">Recovery Services コンテナーでのバックアップ エンジンの登録状態です。</span><span class="sxs-lookup"><span data-stu-id="7e0a6-106">Registration status of the backup engine with the Recovery Services Vault.</span></span></param>
        <param name="backupEngineState"><span data-ttu-id="7e0a6-107">Recovery Services コンテナーでのバックアップ エンジンの状態です。</span><span class="sxs-lookup"><span data-stu-id="7e0a6-107">Status of the backup engine with the Recovery Services Vault.</span></span> <span data-ttu-id="7e0a6-108">{アクティブ/削除/DeleteFailed} を =</span><span class="sxs-lookup"><span data-stu-id="7e0a6-108">= {Active/Deleting/DeleteFailed}</span></span></param>
        <param name="healthStatus"><span data-ttu-id="7e0a6-109">バックアップ エンジンのバックアップの状態。</span><span class="sxs-lookup"><span data-stu-id="7e0a6-109">Backup status of the backup engine.</span></span></param>
        <param name="canReRegister"><span data-ttu-id="7e0a6-110">既に登録されているバックアップ エンジンを登録する場合を示すフラグします。</span><span class="sxs-lookup"><span data-stu-id="7e0a6-110">Flag indicating if the backup engine be registered, once already registered.</span></span></param>
        <param name="backupEngineId"><span data-ttu-id="7e0a6-111">バックアップ エンジンの ID です。</span><span class="sxs-lookup"><span data-stu-id="7e0a6-111">ID of the backup engine.</span></span></param>
        <param name="dpmVersion"><span data-ttu-id="7e0a6-112">バックアップ エンジンのバージョン</span><span class="sxs-lookup"><span data-stu-id="7e0a6-112">Backup engine version</span></span></param>
        <param name="azureBackupAgentVersion"><span data-ttu-id="7e0a6-113">Backup エージェントのバージョン</span><span class="sxs-lookup"><span data-stu-id="7e0a6-113">Backup agent version</span></span></param>
        <param name="isAzureBackupAgentUpgradeAvailable"><span data-ttu-id="7e0a6-114">場合は backup エージェントが使用可能なアップグレードを確認するには</span><span class="sxs-lookup"><span data-stu-id="7e0a6-114">To check if backup agent upgrade available</span></span></param>
        <param name="isDPMUpgradeAvailable"><span data-ttu-id="7e0a6-115">場合のバックアップ エンジンが使用可能なアップグレードを確認するには</span><span class="sxs-lookup"><span data-stu-id="7e0a6-115">To check if backup engine upgrade available</span></span></param>
        <param name="extendedInfo"><span data-ttu-id="7e0a6-116">Backupengine の拡張情報</span><span class="sxs-lookup"><span data-stu-id="7e0a6-116">Extended info of the backupengine</span></span></param>
        <summary>
            <span data-ttu-id="7e0a6-117">DpmBackupEngine クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7e0a6-117">Initializes a new instance of the DpmBackupEngine class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>