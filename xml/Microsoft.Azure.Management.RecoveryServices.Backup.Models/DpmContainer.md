<Type Name="DpmContainer" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmContainer">
  <TypeSignature Language="C#" Value="public class DpmContainer : Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DpmContainer extends Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmContainer" />
  <TypeSignature Language="VB.NET" Value="Public Class DpmContainer&#xA;Inherits ProtectionContainer" />
  <TypeSignature Language="F#" Value="type DpmContainer = class&#xA;    inherit ProtectionContainer" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("DPMContainer")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="acda9-101">DPM ワークロード固有の保護のコンテナーです。</span><span class="sxs-lookup"><span data-stu-id="acda9-101">DPM workload-specific protection container.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DpmContainer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmContainer.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="acda9-102">DpmContainer クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="acda9-102">Initializes a new instance of the DpmContainer class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DpmContainer (string friendlyName = null, string backupManagementType = null, string registrationStatus = null, string healthStatus = null, string containerType = null, Nullable&lt;bool&gt; canReRegister = null, string containerId = null, Nullable&lt;long&gt; protectedItemCount = null, string dpmAgentVersion = null, System.Collections.Generic.IList&lt;string&gt; dPMServers = null, Nullable&lt;bool&gt; upgradeAvailable = null, string protectionStatus = null, Microsoft.Azure.Management.RecoveryServices.Backup.Models.DPMContainerExtendedInfo extendedInfo = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string friendlyName, string backupManagementType, string registrationStatus, string healthStatus, string containerType, valuetype System.Nullable`1&lt;bool&gt; canReRegister, string containerId, valuetype System.Nullable`1&lt;int64&gt; protectedItemCount, string dpmAgentVersion, class System.Collections.Generic.IList`1&lt;string&gt; dPMServers, valuetype System.Nullable`1&lt;bool&gt; upgradeAvailable, string protectionStatus, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.DPMContainerExtendedInfo extendedInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmContainer.#ctor(System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.String,System.Nullable{System.Int64},System.String,System.Collections.Generic.IList{System.String},System.Nullable{System.Boolean},System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.DPMContainerExtendedInfo)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional friendlyName As String = null, Optional backupManagementType As String = null, Optional registrationStatus As String = null, Optional healthStatus As String = null, Optional containerType As String = null, Optional canReRegister As Nullable(Of Boolean) = null, Optional containerId As String = null, Optional protectedItemCount As Nullable(Of Long) = null, Optional dpmAgentVersion As String = null, Optional dPMServers As IList(Of String) = null, Optional upgradeAvailable As Nullable(Of Boolean) = null, Optional protectionStatus As String = null, Optional extendedInfo As DPMContainerExtendedInfo = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmContainer : string * string * string * string * string * Nullable&lt;bool&gt; * string * Nullable&lt;int64&gt; * string * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;bool&gt; * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.DPMContainerExtendedInfo -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmContainer" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmContainer (friendlyName, backupManagementType, registrationStatus, healthStatus, containerType, canReRegister, containerId, protectedItemCount, dpmAgentVersion, dPMServers, upgradeAvailable, protectionStatus, extendedInfo)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="friendlyName" Type="System.String" />
        <Parameter Name="backupManagementType" Type="System.String" />
        <Parameter Name="registrationStatus" Type="System.String" />
        <Parameter Name="healthStatus" Type="System.String" />
        <Parameter Name="containerType" Type="System.String" />
        <Parameter Name="canReRegister" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="containerId" Type="System.String" />
        <Parameter Name="protectedItemCount" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="dpmAgentVersion" Type="System.String" />
        <Parameter Name="dPMServers" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="upgradeAvailable" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="protectionStatus" Type="System.String" />
        <Parameter Name="extendedInfo" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.DPMContainerExtendedInfo" />
      </Parameters>
      <Docs>
        <param name="friendlyName"><span data-ttu-id="acda9-103">コンテナーのフレンドリ名。</span><span class="sxs-lookup"><span data-stu-id="acda9-103">Friendly name of the container.</span></span></param>
        <param name="backupManagementType"><span data-ttu-id="acda9-104">コンテナーのバックアップ managemenent の型。</span><span class="sxs-lookup"><span data-stu-id="acda9-104">Type of backup managemenent for the container.</span></span> <span data-ttu-id="acda9-105">使用可能な値が含まれます: '無効'、'AzureIaasVM'、'MAB'、'DPM'、'AzureBackupServer'、'仮想'</span><span class="sxs-lookup"><span data-stu-id="acda9-105">Possible values include: 'Invalid', 'AzureIaasVM', 'MAB', 'DPM', 'AzureBackupServer', 'AzureSql'</span></span></param>
        <param name="registrationStatus"><span data-ttu-id="acda9-106">Recovery Services コンテナーのコンテナーの登録の状態です。</span><span class="sxs-lookup"><span data-stu-id="acda9-106">Status of registration of the container with the Recovery Services Vault.</span></span></param>
        <param name="healthStatus"><span data-ttu-id="acda9-107">コンテナーの正常性の状態です。</span><span class="sxs-lookup"><span data-stu-id="acda9-107">Status of health of the container.</span></span></param>
        <param name="containerType"><span data-ttu-id="acda9-108">コンテナーの型。</span><span class="sxs-lookup"><span data-stu-id="acda9-108">Type of the container.</span></span> <span data-ttu-id="acda9-109">このプロパティの値: 1。</span><span class="sxs-lookup"><span data-stu-id="acda9-109">The value of this property for: 1.</span></span> <span data-ttu-id="acda9-110">Azure VM が Microsoft.Compute/virtualMachines 2 を計算します。</span><span class="sxs-lookup"><span data-stu-id="acda9-110">Compute Azure VM is Microsoft.Compute/virtualMachines 2.</span></span> <span data-ttu-id="acda9-111">クラシック Azure 仮想マシンのコンピューティングとは、Microsoft.ClassicCompute/virtualMachines 3 です。</span><span class="sxs-lookup"><span data-stu-id="acda9-111">Classic Compute Azure VM is Microsoft.ClassicCompute/virtualMachines 3.</span></span> <span data-ttu-id="acda9-112">(MAB、DPM など) のように Windows コンピューターとは、Windows 4 です。</span><span class="sxs-lookup"><span data-stu-id="acda9-112">Windows machines (like MAB, DPM etc) is Windows 4.</span></span> <span data-ttu-id="acda9-113">Azure の SQL インスタンスは、AzureSqlContainer です。</span><span class="sxs-lookup"><span data-stu-id="acda9-113">Azure SQL instance is AzureSqlContainer.</span></span> <span data-ttu-id="acda9-114">使用可能な値が含まれます: '無効'、'Unknown'、'IaasVMContainer'、'IaasVMServiceContainer'、'DPMContainer'、'AzureBackupServerContainer'、'MABContainer'、'をクラスター'、'AzureSqlContainer'、'Windows'、'VCenter'</span><span class="sxs-lookup"><span data-stu-id="acda9-114">Possible values include: 'Invalid', 'Unknown', 'IaasVMContainer', 'IaasVMServiceContainer', 'DPMContainer', 'AzureBackupServerContainer', 'MABContainer', 'Cluster', 'AzureSqlContainer', 'Windows', 'VCenter'</span></span></param>
        <param name="canReRegister"><span data-ttu-id="acda9-115">コンテナーが再登録可能なかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="acda9-115">Specifies whether the container is re-registrable.</span></span></param>
        <param name="containerId"><span data-ttu-id="acda9-116">コンテナーの ID。</span><span class="sxs-lookup"><span data-stu-id="acda9-116">ID of container.</span></span></param>
        <param name="protectedItemCount"><span data-ttu-id="acda9-117">BackupEngine で保護された項目の数</span><span class="sxs-lookup"><span data-stu-id="acda9-117">Number of protected items in the BackupEngine</span></span></param>
        <param name="dpmAgentVersion"><span data-ttu-id="acda9-118">バックアップ エンジン エージェントのバージョン</span><span class="sxs-lookup"><span data-stu-id="acda9-118">Backup engine Agent version</span></span></param>
        <param name="dPMServers"><span data-ttu-id="acda9-119">コンテナーを保護する BackupEngines の一覧</span><span class="sxs-lookup"><span data-stu-id="acda9-119">List of BackupEngines protecting the container</span></span></param>
        <param name="upgradeAvailable"><span data-ttu-id="acda9-120">場合は、アップグレードの確認に使用できます</span><span class="sxs-lookup"><span data-stu-id="acda9-120">To check if upgrade available</span></span></param>
        <param name="protectionStatus"><span data-ttu-id="acda9-121">コンテナーの状態を保護します。</span><span class="sxs-lookup"><span data-stu-id="acda9-121">Protection status of the container.</span></span></param>
        <param name="extendedInfo"><span data-ttu-id="acda9-122">コンテナーの情報を拡張します。</span><span class="sxs-lookup"><span data-stu-id="acda9-122">Extended Info of the container.</span></span></param>
        <summary>
            <span data-ttu-id="acda9-123">DpmContainer クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="acda9-123">Initializes a new instance of the DpmContainer class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanReRegister">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; CanReRegister { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; CanReRegister" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmContainer.CanReRegister" />
      <MemberSignature Language="VB.NET" Value="Public Property CanReRegister As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.CanReRegister : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmContainer.CanReRegister" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="canReRegister")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="acda9-124">取得または設定は、コンテナーが再登録可能なかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="acda9-124">Gets or sets specifies whether the container is re-registrable.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerId">
      <MemberSignature Language="C#" Value="public string ContainerId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContainerId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmContainer.ContainerId" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerId As String" />
      <MemberSignature Language="F#" Value="member this.ContainerId : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmContainer.ContainerId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="containerId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="acda9-125">取得またはコンテナーの ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="acda9-125">Gets or sets ID of container.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DpmAgentVersion">
      <MemberSignature Language="C#" Value="public string DpmAgentVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DpmAgentVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmContainer.DpmAgentVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property DpmAgentVersion As String" />
      <MemberSignature Language="F#" Value="member this.DpmAgentVersion : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmContainer.DpmAgentVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dpmAgentVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="acda9-126">取得または設定のバックアップ エンジン エージェントのバージョン</span><span class="sxs-lookup"><span data-stu-id="acda9-126">Gets or sets backup engine Agent version</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DPMServers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; DPMServers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; DPMServers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmContainer.DPMServers" />
      <MemberSignature Language="VB.NET" Value="Public Property DPMServers As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.DPMServers : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmContainer.DPMServers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="DPMServers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="acda9-127">取得またはコンテナーを保護する BackupEngines の一覧の設定</span><span class="sxs-lookup"><span data-stu-id="acda9-127">Gets or sets list of BackupEngines protecting the container</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExtendedInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.Models.DPMContainerExtendedInfo ExtendedInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.Models.DPMContainerExtendedInfo ExtendedInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmContainer.ExtendedInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property ExtendedInfo As DPMContainerExtendedInfo" />
      <MemberSignature Language="F#" Value="member this.ExtendedInfo : Microsoft.Azure.Management.RecoveryServices.Backup.Models.DPMContainerExtendedInfo with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmContainer.ExtendedInfo" />
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
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.DPMContainerExtendedInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="acda9-128">取得またはコンテナーの拡張情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="acda9-128">Gets or sets extended Info of the container.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectedItemCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; ProtectedItemCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; ProtectedItemCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmContainer.ProtectedItemCount" />
      <MemberSignature Language="VB.NET" Value="Public Property ProtectedItemCount As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.ProtectedItemCount : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmContainer.ProtectedItemCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="protectedItemCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="acda9-129">取得または設定の保護された項目の数、BackupEngine</span><span class="sxs-lookup"><span data-stu-id="acda9-129">Gets or sets number of protected items in the BackupEngine</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectionStatus">
      <MemberSignature Language="C#" Value="public string ProtectionStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProtectionStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmContainer.ProtectionStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property ProtectionStatus As String" />
      <MemberSignature Language="F#" Value="member this.ProtectionStatus : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmContainer.ProtectionStatus" />
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
            <span data-ttu-id="acda9-130">取得またはコンテナーの保護の状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="acda9-130">Gets or sets protection status of the container.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeAvailable">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; UpgradeAvailable { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; UpgradeAvailable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmContainer.UpgradeAvailable" />
      <MemberSignature Language="VB.NET" Value="Public Property UpgradeAvailable As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.UpgradeAvailable : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmContainer.UpgradeAvailable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="UpgradeAvailable")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="acda9-131">取得または設定するかどうか確認は、使用可能なアップグレードします。</span><span class="sxs-lookup"><span data-stu-id="acda9-131">Gets or sets to check if upgrade available</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>