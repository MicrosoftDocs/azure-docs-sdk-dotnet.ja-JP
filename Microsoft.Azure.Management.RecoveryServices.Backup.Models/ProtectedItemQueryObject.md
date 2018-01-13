<Type Name="ProtectedItemQueryObject" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemQueryObject">
  <TypeSignature Language="C#" Value="public class ProtectedItemQueryObject" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ProtectedItemQueryObject extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemQueryObject" />
  <TypeSignature Language="VB.NET" Value="Public Class ProtectedItemQueryObject" />
  <TypeSignature Language="F#" Value="type ProtectedItemQueryObject = class" />
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
            <span data-ttu-id="6be57-101">バックアップ項目の一覧をフィルターします。</span><span class="sxs-lookup"><span data-stu-id="6be57-101">Filters to list backup items.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ProtectedItemQueryObject ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemQueryObject.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6be57-102">ProtectedItemQueryObject クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6be57-102">Initializes a new instance of the ProtectedItemQueryObject class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ProtectedItemQueryObject (string healthState = null, string backupManagementType = null, string itemType = null, string policyName = null, string containerName = null, string backupEngineName = null, string friendlyName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string healthState, string backupManagementType, string itemType, string policyName, string containerName, string backupEngineName, string friendlyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemQueryObject.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional healthState As String = null, Optional backupManagementType As String = null, Optional itemType As String = null, Optional policyName As String = null, Optional containerName As String = null, Optional backupEngineName As String = null, Optional friendlyName As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemQueryObject : string * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemQueryObject" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemQueryObject (healthState, backupManagementType, itemType, policyName, containerName, backupEngineName, friendlyName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="healthState" Type="System.String" />
        <Parameter Name="backupManagementType" Type="System.String" />
        <Parameter Name="itemType" Type="System.String" />
        <Parameter Name="policyName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="backupEngineName" Type="System.String" />
        <Parameter Name="friendlyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="healthState"><span data-ttu-id="6be57-103">バックアップ項目の正常性状態。</span><span class="sxs-lookup"><span data-stu-id="6be57-103">Health State for the backed up item.</span></span>
            <span data-ttu-id="6be57-104">使用可能な値が含まれます: '渡さ'、'ActionRequired'、'ActionSuggested'、'無効'</span><span class="sxs-lookup"><span data-stu-id="6be57-104">Possible values include: 'Passed', 'ActionRequired', 'ActionSuggested', 'Invalid'</span></span></param>
        <param name="backupManagementType"><span data-ttu-id="6be57-105">バックアップ項目のバックアップの管理の種類。</span><span class="sxs-lookup"><span data-stu-id="6be57-105">Backup management type for the backed up item.</span></span> <span data-ttu-id="6be57-106">使用可能な値が含まれます: '無効'、'AzureIaasVM'、'MAB'、'DPM'、'AzureBackupServer'、'仮想'</span><span class="sxs-lookup"><span data-stu-id="6be57-106">Possible values include: 'Invalid', 'AzureIaasVM', 'MAB', 'DPM', 'AzureBackupServer', 'AzureSql'</span></span></param>
        <param name="itemType"><span data-ttu-id="6be57-107">この項目を表すワークロードの種類です。</span><span class="sxs-lookup"><span data-stu-id="6be57-107">Type of workload this item represents.</span></span>
            <span data-ttu-id="6be57-108">使用可能な値が含まれます: '無効'、'VM'、'ファイル フォルダー'、'AzureSqlDb'、'SQLDB'、'交換'、'Sharepoint'、'VMwareVM'、'SystemState'、'Client'、'GenericDataSource'</span><span class="sxs-lookup"><span data-stu-id="6be57-108">Possible values include: 'Invalid', 'VM', 'FileFolder', 'AzureSqlDb', 'SQLDB', 'Exchange', 'Sharepoint', 'VMwareVM', 'SystemState', 'Client', 'GenericDataSource'</span></span></param>
        <param name="policyName"><span data-ttu-id="6be57-109">バックアップ項目に関連付けられているバックアップ ポリシーの名前です。</span><span class="sxs-lookup"><span data-stu-id="6be57-109">Backup policy name associated with the backup item.</span></span></param>
        <param name="containerName"><span data-ttu-id="6be57-110">コンテナーの名前です。</span><span class="sxs-lookup"><span data-stu-id="6be57-110">Name of the container.</span></span></param>
        <param name="backupEngineName"><span data-ttu-id="6be57-111">バックアップ エンジン名</span><span class="sxs-lookup"><span data-stu-id="6be57-111">Backup Engine name</span></span></param>
        <param name="friendlyName"><span data-ttu-id="6be57-112">保護されているアイテムの表示名</span><span class="sxs-lookup"><span data-stu-id="6be57-112">Friendly name of protected item</span></span></param>
        <summary>
            <span data-ttu-id="6be57-113">ProtectedItemQueryObject クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6be57-113">Initializes a new instance of the ProtectedItemQueryObject class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupEngineName">
      <MemberSignature Language="C#" Value="public string BackupEngineName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BackupEngineName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemQueryObject.BackupEngineName" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupEngineName As String" />
      <MemberSignature Language="F#" Value="member this.BackupEngineName : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemQueryObject.BackupEngineName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="backupEngineName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6be57-114">取得または設定のバックアップ エンジン名</span><span class="sxs-lookup"><span data-stu-id="6be57-114">Gets or sets backup Engine name</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupManagementType">
      <MemberSignature Language="C#" Value="public string BackupManagementType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BackupManagementType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemQueryObject.BackupManagementType" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupManagementType As String" />
      <MemberSignature Language="F#" Value="member this.BackupManagementType : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemQueryObject.BackupManagementType" />
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
            <span data-ttu-id="6be57-115">取得またはバックアップ管理項目の種類をバックアップを設定します。</span><span class="sxs-lookup"><span data-stu-id="6be57-115">Gets or sets backup management type for the backed up item.</span></span>
            <span data-ttu-id="6be57-116">使用可能な値が含まれます: '無効'、'AzureIaasVM'、'MAB'、'DPM'、'AzureBackupServer'、'仮想'</span><span class="sxs-lookup"><span data-stu-id="6be57-116">Possible values include: 'Invalid', 'AzureIaasVM', 'MAB', 'DPM', 'AzureBackupServer', 'AzureSql'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerName">
      <MemberSignature Language="C#" Value="public string ContainerName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContainerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemQueryObject.ContainerName" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerName As String" />
      <MemberSignature Language="F#" Value="member this.ContainerName : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemQueryObject.ContainerName" />
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
            <span data-ttu-id="6be57-117">取得またはコンテナーの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="6be57-117">Gets or sets name of the container.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FriendlyName">
      <MemberSignature Language="C#" Value="public string FriendlyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FriendlyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemQueryObject.FriendlyName" />
      <MemberSignature Language="VB.NET" Value="Public Property FriendlyName As String" />
      <MemberSignature Language="F#" Value="member this.FriendlyName : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemQueryObject.FriendlyName" />
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
            <span data-ttu-id="6be57-118">取得または設定の保護された項目の表示名</span><span class="sxs-lookup"><span data-stu-id="6be57-118">Gets or sets friendly name of protected item</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthState">
      <MemberSignature Language="C#" Value="public string HealthState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HealthState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemQueryObject.HealthState" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthState As String" />
      <MemberSignature Language="F#" Value="member this.HealthState : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemQueryObject.HealthState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="healthState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6be57-119">取得または作成したバックアップ項目のヘルス状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="6be57-119">Gets or sets health State for the backed up item.</span></span> <span data-ttu-id="6be57-120">使用可能な値が含まれます: '渡さ'、'ActionRequired'、'ActionSuggested'、'無効'</span><span class="sxs-lookup"><span data-stu-id="6be57-120">Possible values include: 'Passed', 'ActionRequired', 'ActionSuggested', 'Invalid'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ItemType">
      <MemberSignature Language="C#" Value="public string ItemType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ItemType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemQueryObject.ItemType" />
      <MemberSignature Language="VB.NET" Value="Public Property ItemType As String" />
      <MemberSignature Language="F#" Value="member this.ItemType : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemQueryObject.ItemType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="itemType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6be57-121">取得または設定の種類のワークロードは、この項目を表します。</span><span class="sxs-lookup"><span data-stu-id="6be57-121">Gets or sets type of workload this item represents.</span></span> <span data-ttu-id="6be57-122">使用可能な値が含まれます: '無効'、'VM'、'ファイル フォルダー'、'AzureSqlDb'、'SQLDB'、'交換'、'Sharepoint'、'VMwareVM'、'SystemState'、'Client'、'GenericDataSource'</span><span class="sxs-lookup"><span data-stu-id="6be57-122">Possible values include: 'Invalid', 'VM', 'FileFolder', 'AzureSqlDb', 'SQLDB', 'Exchange', 'Sharepoint', 'VMwareVM', 'SystemState', 'Client', 'GenericDataSource'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PolicyName">
      <MemberSignature Language="C#" Value="public string PolicyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PolicyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemQueryObject.PolicyName" />
      <MemberSignature Language="VB.NET" Value="Public Property PolicyName As String" />
      <MemberSignature Language="F#" Value="member this.PolicyName : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemQueryObject.PolicyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="policyName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6be57-123">取得またはバックアップの項目に関連付けられているバックアップ ポリシー名を設定します。</span><span class="sxs-lookup"><span data-stu-id="6be57-123">Gets or sets backup policy name associated with the backup item.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>