<Type Name="AzureIaaSVMProtectedItem" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItem">
  <TypeSignature Language="C#" Value="public class AzureIaaSVMProtectedItem : Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItem" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureIaaSVMProtectedItem extends Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItem" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItem" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureIaaSVMProtectedItem&#xA;Inherits ProtectedItem" />
  <TypeSignature Language="F#" Value="type AzureIaaSVMProtectedItem = class&#xA;    inherit ProtectedItem" />
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
            <span data-ttu-id="ea470-101">IaaS VM のワークロードに固有のバックアップの項目。</span><span class="sxs-lookup"><span data-stu-id="ea470-101">IaaS VM workload-specific backup item.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureIaaSVMProtectedItem ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItem.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ea470-102">AzureIaaSVMProtectedItem クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ea470-102">Initializes a new instance of the AzureIaaSVMProtectedItem class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureIaaSVMProtectedItem (string backupManagementType = null, string workloadType = null, string containerName = null, string sourceResourceId = null, string policyId = null, Nullable&lt;DateTime&gt; lastRecoveryPoint = null, string friendlyName = null, string virtualMachineId = null, string protectionStatus = null, string protectionState = null, string healthStatus = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMHealthDetails&gt; healthDetails = null, string lastBackupStatus = null, Nullable&lt;DateTime&gt; lastBackupTime = null, string protectedItemDataId = null, Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItemExtendedInfo extendedInfo = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string backupManagementType, string workloadType, string containerName, string sourceResourceId, string policyId, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastRecoveryPoint, string friendlyName, string virtualMachineId, string protectionStatus, string protectionState, string healthStatus, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMHealthDetails&gt; healthDetails, string lastBackupStatus, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastBackupTime, string protectedItemDataId, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItemExtendedInfo extendedInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItem.#ctor(System.String,System.String,System.String,System.String,System.String,System.Nullable{System.DateTime},System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMHealthDetails},System.String,System.Nullable{System.DateTime},System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItemExtendedInfo)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional backupManagementType As String = null, Optional workloadType As String = null, Optional containerName As String = null, Optional sourceResourceId As String = null, Optional policyId As String = null, Optional lastRecoveryPoint As Nullable(Of DateTime) = null, Optional friendlyName As String = null, Optional virtualMachineId As String = null, Optional protectionStatus As String = null, Optional protectionState As String = null, Optional healthStatus As String = null, Optional healthDetails As IList(Of AzureIaaSVMHealthDetails) = null, Optional lastBackupStatus As String = null, Optional lastBackupTime As Nullable(Of DateTime) = null, Optional protectedItemDataId As String = null, Optional extendedInfo As AzureIaaSVMProtectedItemExtendedInfo = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItem : string * string * string * string * string * Nullable&lt;DateTime&gt; * string * string * string * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMHealthDetails&gt; * string * Nullable&lt;DateTime&gt; * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItemExtendedInfo -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItem" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItem (backupManagementType, workloadType, containerName, sourceResourceId, policyId, lastRecoveryPoint, friendlyName, virtualMachineId, protectionStatus, protectionState, healthStatus, healthDetails, lastBackupStatus, lastBackupTime, protectedItemDataId, extendedInfo)" />
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
        <Parameter Name="virtualMachineId" Type="System.String" />
        <Parameter Name="protectionStatus" Type="System.String" />
        <Parameter Name="protectionState" Type="System.String" />
        <Parameter Name="healthStatus" Type="System.String" />
        <Parameter Name="healthDetails" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMHealthDetails&gt;" />
        <Parameter Name="lastBackupStatus" Type="System.String" />
        <Parameter Name="lastBackupTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="protectedItemDataId" Type="System.String" />
        <Parameter Name="extendedInfo" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItemExtendedInfo" />
      </Parameters>
      <Docs>
        <param name="backupManagementType"><span data-ttu-id="ea470-103">バックアップ managemenent バックアップ項目の種類です。</span><span class="sxs-lookup"><span data-stu-id="ea470-103">Type of backup managemenent for the backed up item.</span></span> <span data-ttu-id="ea470-104">使用可能な値が含まれます: '無効'、'AzureIaasVM'、'MAB'、'DPM'、'AzureBackupServer'、'仮想'</span><span class="sxs-lookup"><span data-stu-id="ea470-104">Possible values include: 'Invalid', 'AzureIaasVM', 'MAB', 'DPM', 'AzureBackupServer', 'AzureSql'</span></span></param>
        <param name="workloadType"><span data-ttu-id="ea470-105">この項目を表すワークロードの種類です。</span><span class="sxs-lookup"><span data-stu-id="ea470-105">Type of workload this item represents.</span></span>
            <span data-ttu-id="ea470-106">使用可能な値が含まれます: '無効'、'VM'、'ファイル フォルダー'、'AzureSqlDb'、'SQLDB'、'交換'、'Sharepoint'、'VMwareVM'、'SystemState'、'Client'、'GenericDataSource'</span><span class="sxs-lookup"><span data-stu-id="ea470-106">Possible values include: 'Invalid', 'VM', 'FileFolder', 'AzureSqlDb', 'SQLDB', 'Exchange', 'Sharepoint', 'VMwareVM', 'SystemState', 'Client', 'GenericDataSource'</span></span></param>
        <param name="containerName"><span data-ttu-id="ea470-107">コンテナーの一意の名前</span><span class="sxs-lookup"><span data-stu-id="ea470-107">Unique name of container</span></span></param>
        <param name="sourceResourceId"><span data-ttu-id="ea470-108">バックアップするリソースの ARM ID です。</span><span class="sxs-lookup"><span data-stu-id="ea470-108">ARM ID of the resource to be backed up.</span></span></param>
        <param name="policyId"><span data-ttu-id="ea470-109">この項目をバックアップするバックアップ ポリシーの ID です。</span><span class="sxs-lookup"><span data-stu-id="ea470-109">ID of the backup policy with which this item is backed up.</span></span></param>
        <param name="lastRecoveryPoint"><span data-ttu-id="ea470-110">このバックアップ アイテムの最後 (最新) のバックアップ コピーが作成されたときのタイムスタンプ。</span><span class="sxs-lookup"><span data-stu-id="ea470-110">Timestamp when the last (latest) backup copy was created for this backup item.</span></span></param>
        <param name="friendlyName"><span data-ttu-id="ea470-111">このバックアップ項目によって表される VM のフレンドリ名。</span><span class="sxs-lookup"><span data-stu-id="ea470-111">Friendly name of the VM represented by this backup item.</span></span></param>
        <param name="virtualMachineId"><span data-ttu-id="ea470-112">このアイテムで表されるバーチャル マシンの完全修飾の ARM ID です。</span><span class="sxs-lookup"><span data-stu-id="ea470-112">Fully qualified ARM ID of the virtual machine represented by this item.</span></span></param>
        <param name="protectionStatus"><span data-ttu-id="ea470-113">このバックアップ項目のバックアップの状態。</span><span class="sxs-lookup"><span data-stu-id="ea470-113">Backup status of this backup item.</span></span></param>
        <param name="protectionState"><span data-ttu-id="ea470-114">バックアップは、この項目の状態をバックアップします。</span><span class="sxs-lookup"><span data-stu-id="ea470-114">Backup state of this backup item.</span></span>
            <span data-ttu-id="ea470-115">使用可能な値が含まれます: '無効'、'IRPending'、'Protected'、'ProtectionError'、'ProtectionStopped'、'ProtectionPaused'</span><span class="sxs-lookup"><span data-stu-id="ea470-115">Possible values include: 'Invalid', 'IRPending', 'Protected', 'ProtectionError', 'ProtectionStopped', 'ProtectionPaused'</span></span></param>
        <param name="healthStatus"><span data-ttu-id="ea470-116">保護されている項目のヘルス状態です。</span><span class="sxs-lookup"><span data-stu-id="ea470-116">Health status of protected item.</span></span>
            <span data-ttu-id="ea470-117">使用可能な値が含まれます: '渡さ'、'ActionRequired'、'ActionSuggested'、'無効'</span><span class="sxs-lookup"><span data-stu-id="ea470-117">Possible values include: 'Passed', 'ActionRequired', 'ActionSuggested', 'Invalid'</span></span></param>
        <param name="healthDetails"><span data-ttu-id="ea470-118">このバックアップ項目の正常性の詳細。</span><span class="sxs-lookup"><span data-stu-id="ea470-118">Health details on this backup item.</span></span></param>
        <param name="lastBackupStatus"><span data-ttu-id="ea470-119">最新のバックアップ操作の状態。</span><span class="sxs-lookup"><span data-stu-id="ea470-119">Last backup operation status.</span></span>
            <span data-ttu-id="ea470-120">使用可能な値: 正常、異常です。</span><span class="sxs-lookup"><span data-stu-id="ea470-120">Possible values: Healthy, Unhealthy.</span></span></param>
        <param name="lastBackupTime"><span data-ttu-id="ea470-121">このバックアップ項目の最後のバックアップ操作のタイムスタンプです。</span><span class="sxs-lookup"><span data-stu-id="ea470-121">Timestamp of the last backup operation on this backup item.</span></span></param>
        <param name="protectedItemDataId"><span data-ttu-id="ea470-122">保護されたアイテムのデータ ID。</span><span class="sxs-lookup"><span data-stu-id="ea470-122">Data ID of the protected item.</span></span></param>
        <param name="extendedInfo"><span data-ttu-id="ea470-123">このバックアップ項目の追加情報です。</span><span class="sxs-lookup"><span data-stu-id="ea470-123">Additional information for this backup item.</span></span></param>
        <summary>
            <span data-ttu-id="ea470-124">AzureIaaSVMProtectedItem クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ea470-124">Initializes a new instance of the AzureIaaSVMProtectedItem class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExtendedInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItemExtendedInfo ExtendedInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItemExtendedInfo ExtendedInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItem.ExtendedInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property ExtendedInfo As AzureIaaSVMProtectedItemExtendedInfo" />
      <MemberSignature Language="F#" Value="member this.ExtendedInfo : Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItemExtendedInfo with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItem.ExtendedInfo" />
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
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItemExtendedInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea470-125">取得またはこのバックアップ項目の追加情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="ea470-125">Gets or sets additional information for this backup item.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FriendlyName">
      <MemberSignature Language="C#" Value="public string FriendlyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FriendlyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItem.FriendlyName" />
      <MemberSignature Language="VB.NET" Value="Public Property FriendlyName As String" />
      <MemberSignature Language="F#" Value="member this.FriendlyName : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItem.FriendlyName" />
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
            <span data-ttu-id="ea470-126">取得またはこのバックアップ項目によって表される VM のフレンドリ名を設定します。</span><span class="sxs-lookup"><span data-stu-id="ea470-126">Gets or sets friendly name of the VM represented by this backup item.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthDetails">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMHealthDetails&gt; HealthDetails { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMHealthDetails&gt; HealthDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItem.HealthDetails" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthDetails As IList(Of AzureIaaSVMHealthDetails)" />
      <MemberSignature Language="F#" Value="member this.HealthDetails : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMHealthDetails&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItem.HealthDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="healthDetails")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMHealthDetails&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea470-127">取得またはこのバックアップ項目の正常性の詳細を設定します。</span><span class="sxs-lookup"><span data-stu-id="ea470-127">Gets or sets health details on this backup item.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStatus">
      <MemberSignature Language="C#" Value="public string HealthStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HealthStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItem.HealthStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStatus As String" />
      <MemberSignature Language="F#" Value="member this.HealthStatus : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItem.HealthStatus" />
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
            <span data-ttu-id="ea470-128">取得または保護された項目のヘルス状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="ea470-128">Gets or sets health status of protected item.</span></span> <span data-ttu-id="ea470-129">使用可能な値が含まれます: '渡さ'、'ActionRequired'、'ActionSuggested'、'無効'</span><span class="sxs-lookup"><span data-stu-id="ea470-129">Possible values include: 'Passed', 'ActionRequired', 'ActionSuggested', 'Invalid'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastBackupStatus">
      <MemberSignature Language="C#" Value="public string LastBackupStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LastBackupStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItem.LastBackupStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property LastBackupStatus As String" />
      <MemberSignature Language="F#" Value="member this.LastBackupStatus : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItem.LastBackupStatus" />
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
            <span data-ttu-id="ea470-130">取得または最新のバックアップ操作の状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="ea470-130">Gets or sets last backup operation status.</span></span> <span data-ttu-id="ea470-131">使用可能な値: 正常、異常です。</span><span class="sxs-lookup"><span data-stu-id="ea470-131">Possible values: Healthy, Unhealthy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastBackupTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastBackupTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastBackupTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItem.LastBackupTime" />
      <MemberSignature Language="VB.NET" Value="Public Property LastBackupTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastBackupTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItem.LastBackupTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastBackupTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea470-132">取得またはこのバックアップ項目の最後のバックアップ操作のタイムスタンプを設定します。</span><span class="sxs-lookup"><span data-stu-id="ea470-132">Gets or sets timestamp of the last backup operation on this backup item.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectedItemDataId">
      <MemberSignature Language="C#" Value="public string ProtectedItemDataId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProtectedItemDataId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItem.ProtectedItemDataId" />
      <MemberSignature Language="VB.NET" Value="Public Property ProtectedItemDataId As String" />
      <MemberSignature Language="F#" Value="member this.ProtectedItemDataId : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItem.ProtectedItemDataId" />
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
            <span data-ttu-id="ea470-133">取得または保護されたアイテムのデータ ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="ea470-133">Gets or sets data ID of the protected item.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectionState">
      <MemberSignature Language="C#" Value="public string ProtectionState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProtectionState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItem.ProtectionState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProtectionState As String" />
      <MemberSignature Language="F#" Value="member this.ProtectionState : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItem.ProtectionState" />
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
            <span data-ttu-id="ea470-134">取得またはこのバックアップ項目のバックアップの状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="ea470-134">Gets or sets backup state of this backup item.</span></span> <span data-ttu-id="ea470-135">使用可能な値が含まれます: '無効'、'IRPending'、'Protected'、'ProtectionError'、'ProtectionStopped'、'ProtectionPaused'</span><span class="sxs-lookup"><span data-stu-id="ea470-135">Possible values include: 'Invalid', 'IRPending', 'Protected', 'ProtectionError', 'ProtectionStopped', 'ProtectionPaused'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectionStatus">
      <MemberSignature Language="C#" Value="public string ProtectionStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProtectionStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItem.ProtectionStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property ProtectionStatus As String" />
      <MemberSignature Language="F#" Value="member this.ProtectionStatus : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItem.ProtectionStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="protectionStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea470-136">取得またはこのバックアップ項目のバックアップの状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="ea470-136">Gets or sets backup status of this backup item.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineId">
      <MemberSignature Language="C#" Value="public string VirtualMachineId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VirtualMachineId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItem.VirtualMachineId" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualMachineId As String" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineId : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItem.VirtualMachineId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="virtualMachineId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea470-137">取得またはこの項目で表現される、仮想マシンの完全修飾の ARM ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="ea470-137">Gets or sets fully qualified ARM ID of the virtual machine represented by this item.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>