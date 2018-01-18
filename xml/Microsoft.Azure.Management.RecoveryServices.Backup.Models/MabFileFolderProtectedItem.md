<Type Name="MabFileFolderProtectedItem" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItem">
  <TypeSignature Language="C#" Value="public class MabFileFolderProtectedItem : Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItem" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MabFileFolderProtectedItem extends Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItem" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItem" />
  <TypeSignature Language="VB.NET" Value="Public Class MabFileFolderProtectedItem&#xA;Inherits ProtectedItem" />
  <TypeSignature Language="F#" Value="type MabFileFolderProtectedItem = class&#xA;    inherit ProtectedItem" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItem</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3b5ee-101">MAB ワークロードに固有のバックアップ アイテムです。</span><span class="sxs-lookup"><span data-stu-id="3b5ee-101">MAB workload-specific backup item.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MabFileFolderProtectedItem ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItem.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3b5ee-102">MabFileFolderProtectedItem クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3b5ee-102">Initializes a new instance of the MabFileFolderProtectedItem class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MabFileFolderProtectedItem (string backupManagementType = null, string workloadType = null, string containerName = null, string sourceResourceId = null, string policyId = null, Nullable&lt;DateTime&gt; lastRecoveryPoint = null, string friendlyName = null, string computerName = null, string lastBackupStatus = null, string protectionState = null, Nullable&lt;bool&gt; isScheduledForDeferredDelete = null, Nullable&lt;long&gt; deferredDeleteSyncTimeInUTC = null, Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItemExtendedInfo extendedInfo = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string backupManagementType, string workloadType, string containerName, string sourceResourceId, string policyId, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastRecoveryPoint, string friendlyName, string computerName, string lastBackupStatus, string protectionState, valuetype System.Nullable`1&lt;bool&gt; isScheduledForDeferredDelete, valuetype System.Nullable`1&lt;int64&gt; deferredDeleteSyncTimeInUTC, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItemExtendedInfo extendedInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItem.#ctor(System.String,System.String,System.String,System.String,System.String,System.Nullable{System.DateTime},System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.Nullable{System.Int64},Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItemExtendedInfo)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional backupManagementType As String = null, Optional workloadType As String = null, Optional containerName As String = null, Optional sourceResourceId As String = null, Optional policyId As String = null, Optional lastRecoveryPoint As Nullable(Of DateTime) = null, Optional friendlyName As String = null, Optional computerName As String = null, Optional lastBackupStatus As String = null, Optional protectionState As String = null, Optional isScheduledForDeferredDelete As Nullable(Of Boolean) = null, Optional deferredDeleteSyncTimeInUTC As Nullable(Of Long) = null, Optional extendedInfo As MabFileFolderProtectedItemExtendedInfo = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItem : string * string * string * string * string * Nullable&lt;DateTime&gt; * string * string * string * string * Nullable&lt;bool&gt; * Nullable&lt;int64&gt; * Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItemExtendedInfo -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItem" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItem (backupManagementType, workloadType, containerName, sourceResourceId, policyId, lastRecoveryPoint, friendlyName, computerName, lastBackupStatus, protectionState, isScheduledForDeferredDelete, deferredDeleteSyncTimeInUTC, extendedInfo)" />
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
        <Parameter Name="friendlyName" Type="System.String" />
        <Parameter Name="computerName" Type="System.String" />
        <Parameter Name="lastBackupStatus" Type="System.String" />
        <Parameter Name="protectionState" Type="System.String" />
        <Parameter Name="isScheduledForDeferredDelete" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="deferredDeleteSyncTimeInUTC" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="extendedInfo" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItemExtendedInfo" />
      </Parameters>
      <Docs>
        <param name="backupManagementType"><span data-ttu-id="3b5ee-103">バックアップ managemenent バックアップ項目の種類です。</span><span class="sxs-lookup"><span data-stu-id="3b5ee-103">Type of backup managemenent for the backed up item.</span></span> <span data-ttu-id="3b5ee-104">使用可能な値が含まれます: '無効'、'AzureIaasVM'、'MAB'、'DPM'、'AzureBackupServer'、'仮想'</span><span class="sxs-lookup"><span data-stu-id="3b5ee-104">Possible values include: 'Invalid', 'AzureIaasVM', 'MAB', 'DPM', 'AzureBackupServer', 'AzureSql'</span></span></param>
        <param name="workloadType"><span data-ttu-id="3b5ee-105">この項目を表すワークロードの種類です。</span><span class="sxs-lookup"><span data-stu-id="3b5ee-105">Type of workload this item represents.</span></span>
            <span data-ttu-id="3b5ee-106">使用可能な値が含まれます: '無効'、'VM'、'ファイル フォルダー'、'AzureSqlDb'、'SQLDB'、'交換'、'Sharepoint'、'VMwareVM'、'SystemState'、'Client'、'GenericDataSource'</span><span class="sxs-lookup"><span data-stu-id="3b5ee-106">Possible values include: 'Invalid', 'VM', 'FileFolder', 'AzureSqlDb', 'SQLDB', 'Exchange', 'Sharepoint', 'VMwareVM', 'SystemState', 'Client', 'GenericDataSource'</span></span></param>
        <param name="containerName"><span data-ttu-id="3b5ee-107">コンテナーの一意の名前</span><span class="sxs-lookup"><span data-stu-id="3b5ee-107">Unique name of container</span></span></param>
        <param name="sourceResourceId"><span data-ttu-id="3b5ee-108">バックアップするリソースの ARM ID です。</span><span class="sxs-lookup"><span data-stu-id="3b5ee-108">ARM ID of the resource to be backed up.</span></span></param>
        <param name="policyId"><span data-ttu-id="3b5ee-109">この項目をバックアップするバックアップ ポリシーの ID です。</span><span class="sxs-lookup"><span data-stu-id="3b5ee-109">ID of the backup policy with which this item is backed up.</span></span></param>
        <param name="lastRecoveryPoint"><span data-ttu-id="3b5ee-110">このバックアップ アイテムの最後 (最新) のバックアップ コピーが作成されたときのタイムスタンプ。</span><span class="sxs-lookup"><span data-stu-id="3b5ee-110">Timestamp when the last (latest) backup copy was created for this backup item.</span></span></param>
        <param name="friendlyName"><span data-ttu-id="3b5ee-111">このバックアップ アイテムの表示名。</span><span class="sxs-lookup"><span data-stu-id="3b5ee-111">Friendly name of this backup item.</span></span></param>
        <param name="computerName"><span data-ttu-id="3b5ee-112">バックアップは、この項目に関連付けられているコンピューターの名前です。</span><span class="sxs-lookup"><span data-stu-id="3b5ee-112">Name of the computer associated with this backup item.</span></span></param>
        <param name="lastBackupStatus"><span data-ttu-id="3b5ee-113">最後のバックアップ操作の状態です。</span><span class="sxs-lookup"><span data-stu-id="3b5ee-113">Status of last backup operation.</span></span></param>
        <param name="protectionState"><span data-ttu-id="3b5ee-114">保護された、ProtectionStopped、IRPending または ProtectionError</span><span class="sxs-lookup"><span data-stu-id="3b5ee-114">Protected, ProtectionStopped, IRPending or ProtectionError</span></span></param>
        <param name="isScheduledForDeferredDelete"><span data-ttu-id="3b5ee-115">遅延および削除の項目がスケジュールされているかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="3b5ee-115">Specifies if the item is scheduled for deferred deletion.</span></span></param>
        <param name="deferredDeleteSyncTimeInUTC"><span data-ttu-id="3b5ee-116">遅延および削除の同期時間です。</span><span class="sxs-lookup"><span data-stu-id="3b5ee-116">Sync time for deferred deletion.</span></span></param>
        <param name="extendedInfo"><span data-ttu-id="3b5ee-117">このバックアップ項目の追加情報です。</span><span class="sxs-lookup"><span data-stu-id="3b5ee-117">Additional information with this backup item.</span></span></param>
        <summary>
            <span data-ttu-id="3b5ee-118">MabFileFolderProtectedItem クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3b5ee-118">Initializes a new instance of the MabFileFolderProtectedItem class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComputerName">
      <MemberSignature Language="C#" Value="public string ComputerName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ComputerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItem.ComputerName" />
      <MemberSignature Language="VB.NET" Value="Public Property ComputerName As String" />
      <MemberSignature Language="F#" Value="member this.ComputerName : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItem.ComputerName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="computerName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3b5ee-119">取得またはバックアップは、この項目に関連付けられているコンピューターの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="3b5ee-119">Gets or sets name of the computer associated with this backup item.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeferredDeleteSyncTimeInUTC">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; DeferredDeleteSyncTimeInUTC { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; DeferredDeleteSyncTimeInUTC" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItem.DeferredDeleteSyncTimeInUTC" />
      <MemberSignature Language="VB.NET" Value="Public Property DeferredDeleteSyncTimeInUTC As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.DeferredDeleteSyncTimeInUTC : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItem.DeferredDeleteSyncTimeInUTC" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="deferredDeleteSyncTimeInUTC")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3b5ee-120">取得または遅延削除の同期の時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="3b5ee-120">Gets or sets sync time for deferred deletion.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExtendedInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItemExtendedInfo ExtendedInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItemExtendedInfo ExtendedInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItem.ExtendedInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property ExtendedInfo As MabFileFolderProtectedItemExtendedInfo" />
      <MemberSignature Language="F#" Value="member this.ExtendedInfo : Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItemExtendedInfo with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItem.ExtendedInfo" />
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
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItemExtendedInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3b5ee-121">取得またはでは、このバックアップ項目の追加情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="3b5ee-121">Gets or sets additional information with this backup item.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FriendlyName">
      <MemberSignature Language="C#" Value="public string FriendlyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FriendlyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItem.FriendlyName" />
      <MemberSignature Language="VB.NET" Value="Public Property FriendlyName As String" />
      <MemberSignature Language="F#" Value="member this.FriendlyName : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItem.FriendlyName" />
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
            <span data-ttu-id="3b5ee-122">取得またはこのバックアップ アイテムの表示名を設定します。</span><span class="sxs-lookup"><span data-stu-id="3b5ee-122">Gets or sets friendly name of this backup item.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsScheduledForDeferredDelete">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsScheduledForDeferredDelete { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsScheduledForDeferredDelete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItem.IsScheduledForDeferredDelete" />
      <MemberSignature Language="VB.NET" Value="Public Property IsScheduledForDeferredDelete As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsScheduledForDeferredDelete : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItem.IsScheduledForDeferredDelete" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isScheduledForDeferredDelete")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3b5ee-123">取得または設定は、遅延および削除の項目がスケジュールされているかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="3b5ee-123">Gets or sets specifies if the item is scheduled for deferred deletion.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastBackupStatus">
      <MemberSignature Language="C#" Value="public string LastBackupStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LastBackupStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItem.LastBackupStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property LastBackupStatus As String" />
      <MemberSignature Language="F#" Value="member this.LastBackupStatus : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItem.LastBackupStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastBackupStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3b5ee-124">取得または最後のバックアップ操作の状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="3b5ee-124">Gets or sets status of last backup operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectionState">
      <MemberSignature Language="C#" Value="public string ProtectionState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProtectionState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItem.ProtectionState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProtectionState As String" />
      <MemberSignature Language="F#" Value="member this.ProtectionState : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItem.ProtectionState" />
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
            <span data-ttu-id="3b5ee-125">取得または設定、保護されている ProtectionStopped、IRPending または ProtectionError</span><span class="sxs-lookup"><span data-stu-id="3b5ee-125">Gets or sets protected, ProtectionStopped, IRPending or ProtectionError</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>