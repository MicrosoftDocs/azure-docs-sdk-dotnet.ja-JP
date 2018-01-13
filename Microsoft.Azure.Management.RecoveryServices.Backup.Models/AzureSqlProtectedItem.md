<Type Name="AzureSqlProtectedItem" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItem">
  <TypeSignature Language="C#" Value="public class AzureSqlProtectedItem : Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItem" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureSqlProtectedItem extends Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItem" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItem" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureSqlProtectedItem&#xA;Inherits ProtectedItem" />
  <TypeSignature Language="F#" Value="type AzureSqlProtectedItem = class&#xA;    inherit ProtectedItem" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItem</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Microsoft.Sql/servers/databases")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="d7b08-101">Azure SQL ワークロード固有バックアップ アイテムです。</span><span class="sxs-lookup"><span data-stu-id="d7b08-101">Azure SQL workload-specific backup item.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureSqlProtectedItem ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItem.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d7b08-102">AzureSqlProtectedItem クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d7b08-102">Initializes a new instance of the AzureSqlProtectedItem class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureSqlProtectedItem (string backupManagementType = null, string workloadType = null, string containerName = null, string sourceResourceId = null, string policyId = null, Nullable&lt;DateTime&gt; lastRecoveryPoint = null, string protectedItemDataId = null, string protectionState = null, Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItemExtendedInfo extendedInfo = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string backupManagementType, string workloadType, string containerName, string sourceResourceId, string policyId, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastRecoveryPoint, string protectedItemDataId, string protectionState, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItemExtendedInfo extendedInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItem.#ctor(System.String,System.String,System.String,System.String,System.String,System.Nullable{System.DateTime},System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItemExtendedInfo)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional backupManagementType As String = null, Optional workloadType As String = null, Optional containerName As String = null, Optional sourceResourceId As String = null, Optional policyId As String = null, Optional lastRecoveryPoint As Nullable(Of DateTime) = null, Optional protectedItemDataId As String = null, Optional protectionState As String = null, Optional extendedInfo As AzureSqlProtectedItemExtendedInfo = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItem : string * string * string * string * string * Nullable&lt;DateTime&gt; * string * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItemExtendedInfo -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItem" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItem (backupManagementType, workloadType, containerName, sourceResourceId, policyId, lastRecoveryPoint, protectedItemDataId, protectionState, extendedInfo)" />
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
        <Parameter Name="protectedItemDataId" Type="System.String" />
        <Parameter Name="protectionState" Type="System.String" />
        <Parameter Name="extendedInfo" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItemExtendedInfo" />
      </Parameters>
      <Docs>
        <param name="backupManagementType"><span data-ttu-id="d7b08-103">バックアップ managemenent バックアップ項目の種類です。</span><span class="sxs-lookup"><span data-stu-id="d7b08-103">Type of backup managemenent for the backed up item.</span></span> <span data-ttu-id="d7b08-104">使用可能な値が含まれます: '無効'、'AzureIaasVM'、'MAB'、'DPM'、'AzureBackupServer'、'仮想'</span><span class="sxs-lookup"><span data-stu-id="d7b08-104">Possible values include: 'Invalid', 'AzureIaasVM', 'MAB', 'DPM', 'AzureBackupServer', 'AzureSql'</span></span></param>
        <param name="workloadType"><span data-ttu-id="d7b08-105">この項目を表すワークロードの種類です。</span><span class="sxs-lookup"><span data-stu-id="d7b08-105">Type of workload this item represents.</span></span>
            <span data-ttu-id="d7b08-106">使用可能な値が含まれます: '無効'、'VM'、'ファイル フォルダー'、'AzureSqlDb'、'SQLDB'、'交換'、'Sharepoint'、'VMwareVM'、'SystemState'、'Client'、'GenericDataSource'</span><span class="sxs-lookup"><span data-stu-id="d7b08-106">Possible values include: 'Invalid', 'VM', 'FileFolder', 'AzureSqlDb', 'SQLDB', 'Exchange', 'Sharepoint', 'VMwareVM', 'SystemState', 'Client', 'GenericDataSource'</span></span></param>
        <param name="containerName"><span data-ttu-id="d7b08-107">コンテナーの一意の名前</span><span class="sxs-lookup"><span data-stu-id="d7b08-107">Unique name of container</span></span></param>
        <param name="sourceResourceId"><span data-ttu-id="d7b08-108">バックアップするリソースの ARM ID です。</span><span class="sxs-lookup"><span data-stu-id="d7b08-108">ARM ID of the resource to be backed up.</span></span></param>
        <param name="policyId"><span data-ttu-id="d7b08-109">この項目をバックアップするバックアップ ポリシーの ID です。</span><span class="sxs-lookup"><span data-stu-id="d7b08-109">ID of the backup policy with which this item is backed up.</span></span></param>
        <param name="lastRecoveryPoint"><span data-ttu-id="d7b08-110">このバックアップ アイテムの最後 (最新) のバックアップ コピーが作成されたときのタイムスタンプ。</span><span class="sxs-lookup"><span data-stu-id="d7b08-110">Timestamp when the last (latest) backup copy was created for this backup item.</span></span></param>
        <param name="protectedItemDataId"><span data-ttu-id="d7b08-111">バックアップ項目の内部 ID。</span><span class="sxs-lookup"><span data-stu-id="d7b08-111">Internal ID of a backup item.</span></span>
            <span data-ttu-id="d7b08-112">回復サービスにお問い合わせに Azure SQL のバックアップ エンジンが使用されます。</span><span class="sxs-lookup"><span data-stu-id="d7b08-112">Used by Azure SQL Backup engine to contact Recovery Services.</span></span></param>
        <param name="protectionState"><span data-ttu-id="d7b08-113">バックアップ項目の状態をバックアップします。</span><span class="sxs-lookup"><span data-stu-id="d7b08-113">Backup state of the backed up item.</span></span>
            <span data-ttu-id="d7b08-114">使用可能な値が含まれます: '無効'、'IRPending'、'Protected'、'ProtectionError'、'ProtectionStopped'、'ProtectionPaused'</span><span class="sxs-lookup"><span data-stu-id="d7b08-114">Possible values include: 'Invalid', 'IRPending', 'Protected', 'ProtectionError', 'ProtectionStopped', 'ProtectionPaused'</span></span></param>
        <param name="extendedInfo"><span data-ttu-id="d7b08-115">このバックアップ項目の追加情報です。</span><span class="sxs-lookup"><span data-stu-id="d7b08-115">Additional information for this backup item.</span></span></param>
        <summary>
            <span data-ttu-id="d7b08-116">AzureSqlProtectedItem クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d7b08-116">Initializes a new instance of the AzureSqlProtectedItem class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExtendedInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItemExtendedInfo ExtendedInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItemExtendedInfo ExtendedInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItem.ExtendedInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property ExtendedInfo As AzureSqlProtectedItemExtendedInfo" />
      <MemberSignature Language="F#" Value="member this.ExtendedInfo : Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItemExtendedInfo with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItem.ExtendedInfo" />
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
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItemExtendedInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d7b08-117">取得またはこのバックアップ項目の追加情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="d7b08-117">Gets or sets additional information for this backup item.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectedItemDataId">
      <MemberSignature Language="C#" Value="public string ProtectedItemDataId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProtectedItemDataId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItem.ProtectedItemDataId" />
      <MemberSignature Language="VB.NET" Value="Public Property ProtectedItemDataId As String" />
      <MemberSignature Language="F#" Value="member this.ProtectedItemDataId : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItem.ProtectedItemDataId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="protectedItemDataId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d7b08-118">取得またはバックアップ項目の内部 ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="d7b08-118">Gets or sets internal ID of a backup item.</span></span> <span data-ttu-id="d7b08-119">回復サービスにお問い合わせに Azure SQL のバックアップ エンジンが使用されます。</span><span class="sxs-lookup"><span data-stu-id="d7b08-119">Used by Azure SQL Backup engine to contact Recovery Services.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectionState">
      <MemberSignature Language="C#" Value="public string ProtectionState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProtectionState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItem.ProtectionState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProtectionState As String" />
      <MemberSignature Language="F#" Value="member this.ProtectionState : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItem.ProtectionState" />
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
            <span data-ttu-id="d7b08-120">取得または作成したバックアップ項目のバックアップの状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="d7b08-120">Gets or sets backup state of the backed up item.</span></span> <span data-ttu-id="d7b08-121">使用可能な値が含まれます: '無効'、'IRPending'、'Protected'、'ProtectionError'、'ProtectionStopped'、'ProtectionPaused'</span><span class="sxs-lookup"><span data-stu-id="d7b08-121">Possible values include: 'Invalid', 'IRPending', 'Protected', 'ProtectionError', 'ProtectionStopped', 'ProtectionPaused'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>