<Type Name="LegacyApplianceConfig" FullName="Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig">
  <TypeSignature Language="C#" Value="public class LegacyApplianceConfig" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit LegacyApplianceConfig extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig" />
  <TypeSignature Language="VB.NET" Value="Public Class LegacyApplianceConfig" />
  <TypeSignature Language="F#" Value="type LegacyApplianceConfig = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7adc8-101">このクラスは、インポートする解析済みの構成を表します。</span><span class="sxs-lookup"><span data-stu-id="7adc8-101">This class represents the parsed config to be imported.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LegacyApplianceConfig ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7adc8-102">LegacyApplianceConfig クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7adc8-102">Initializes a new instance of the LegacyApplianceConfig class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessControlRecords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.AccessControlRecord&gt; AccessControlRecords { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.AccessControlRecord&gt; AccessControlRecords" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig.AccessControlRecords" />
      <MemberSignature Language="VB.NET" Value="Public Property AccessControlRecords As IList(Of AccessControlRecord)" />
      <MemberSignature Language="F#" Value="member this.AccessControlRecords : System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.AccessControlRecord&gt; with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig.AccessControlRecords" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.AccessControlRecord&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7adc8-103">必須。</span><span class="sxs-lookup"><span data-stu-id="7adc8-103">Required.</span></span> <span data-ttu-id="7adc8-104">取得またはインポートする構成の xml からアクセス制御レコードの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="7adc8-104">Gets or sets the list of Access Control Records from config xml to be imported.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupPolicies">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationBackupPolicy&gt; BackupPolicies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationBackupPolicy&gt; BackupPolicies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig.BackupPolicies" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupPolicies As IList(Of MigrationBackupPolicy)" />
      <MemberSignature Language="F#" Value="member this.BackupPolicies : System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationBackupPolicy&gt; with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig.BackupPolicies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationBackupPolicy&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7adc8-105">必須。</span><span class="sxs-lookup"><span data-stu-id="7adc8-105">Required.</span></span> <span data-ttu-id="7adc8-106">取得またはインポートする構成の xml からバック ポリシーの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="7adc8-106">Gets or sets list of back policies from config xml to be imported.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BandwidthSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.BandwidthSetting&gt; BandwidthSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.BandwidthSetting&gt; BandwidthSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig.BandwidthSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property BandwidthSettings As IList(Of BandwidthSetting)" />
      <MemberSignature Language="F#" Value="member this.BandwidthSettings : System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.BandwidthSetting&gt; with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig.BandwidthSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.BandwidthSetting&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7adc8-107">必須。</span><span class="sxs-lookup"><span data-stu-id="7adc8-107">Required.</span></span> <span data-ttu-id="7adc8-108">取得または設定 xml からインポートするの帯域幅設定の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="7adc8-108">Gets or sets list of Bandwidth settings from config xml to be imported.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloudConfigurations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainer&gt; CloudConfigurations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainer&gt; CloudConfigurations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig.CloudConfigurations" />
      <MemberSignature Language="VB.NET" Value="Public Property CloudConfigurations As IList(Of MigrationDataContainer)" />
      <MemberSignature Language="F#" Value="member this.CloudConfigurations : System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainer&gt; with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig.CloudConfigurations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainer&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7adc8-109">必須。</span><span class="sxs-lookup"><span data-stu-id="7adc8-109">Required.</span></span> <span data-ttu-id="7adc8-110">取得またはインポートする構成の xml からのボリューム コンテナーの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="7adc8-110">Gets or sets list of volume containers from config xml to be imported.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeviceId">
      <MemberSignature Language="C#" Value="public string DeviceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DeviceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig.DeviceId" />
      <MemberSignature Language="VB.NET" Value="Public Property DeviceId As String" />
      <MemberSignature Language="F#" Value="member this.DeviceId : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig.DeviceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7adc8-111">必須。</span><span class="sxs-lookup"><span data-stu-id="7adc8-111">Required.</span></span> <span data-ttu-id="7adc8-112">取得または移行するボリュームにコンテナーが必要なターゲット デバイス id を設定します。</span><span class="sxs-lookup"><span data-stu-id="7adc8-112">Gets or sets target device id to which volume containers needs to be migrated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InboundChapSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationChapSetting&gt; InboundChapSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationChapSetting&gt; InboundChapSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig.InboundChapSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property InboundChapSettings As IList(Of MigrationChapSetting)" />
      <MemberSignature Language="F#" Value="member this.InboundChapSettings : System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationChapSetting&gt; with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig.InboundChapSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationChapSetting&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7adc8-113">省略可能。</span><span class="sxs-lookup"><span data-stu-id="7adc8-113">Optional.</span></span> <span data-ttu-id="7adc8-114">取得またはインポートする構成 xml からの入力方向の chap 設定の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="7adc8-114">Gets or sets list of inbound chap settings from config xml to be imported.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstanceId">
      <MemberSignature Language="C#" Value="public string InstanceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InstanceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig.InstanceId" />
      <MemberSignature Language="VB.NET" Value="Public Property InstanceId As String" />
      <MemberSignature Language="F#" Value="member this.InstanceId : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig.InstanceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7adc8-115">省略可能。</span><span class="sxs-lookup"><span data-stu-id="7adc8-115">Optional.</span></span> <span data-ttu-id="7adc8-116">取得または設定の構成に関する詳細をインポート中に渡される一意の構成 id</span><span class="sxs-lookup"><span data-stu-id="7adc8-116">Gets or sets the unique config id to be passed while importing the config details</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7adc8-117">必須。</span><span class="sxs-lookup"><span data-stu-id="7adc8-117">Required.</span></span> <span data-ttu-id="7adc8-118">取得または設定の構成の名前</span><span class="sxs-lookup"><span data-stu-id="7adc8-118">Gets or sets the name of the config</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationInProgress">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.Models.OperationInProgress OperationInProgress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Management.StorSimple.Models.OperationInProgress OperationInProgress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig.OperationInProgress" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationInProgress As OperationInProgress" />
      <MemberSignature Language="F#" Value="member this.OperationInProgress : Microsoft.WindowsAzure.Management.StorSimple.Models.OperationInProgress with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig.OperationInProgress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.OperationInProgress</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7adc8-119">省略可能。</span><span class="sxs-lookup"><span data-stu-id="7adc8-119">Optional.</span></span> <span data-ttu-id="7adc8-120">取得または任意の操作が進行中かどうかを示す値を設定</span><span class="sxs-lookup"><span data-stu-id="7adc8-120">Gets or sets a value which indicating whether any operation is in progress</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerialNumber">
      <MemberSignature Language="C#" Value="public int SerialNumber { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 SerialNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig.SerialNumber" />
      <MemberSignature Language="VB.NET" Value="Public Property SerialNumber As Integer" />
      <MemberSignature Language="F#" Value="member this.SerialNumber : int with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig.SerialNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7adc8-121">必須。</span><span class="sxs-lookup"><span data-stu-id="7adc8-121">Required.</span></span> <span data-ttu-id="7adc8-122">取得または構成が小さく構成に分割し、インポートされたときに現在の sub 構成エントリのシリアル番号を設定</span><span class="sxs-lookup"><span data-stu-id="7adc8-122">Gets or sets the serial number of the current sub-config entry when the config is splitted into smaller config and imported</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountCredentials">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.StorageAccountCredential&gt; StorageAccountCredentials { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.StorageAccountCredential&gt; StorageAccountCredentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig.StorageAccountCredentials" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccountCredentials As IList(Of StorageAccountCredential)" />
      <MemberSignature Language="F#" Value="member this.StorageAccountCredentials : System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.StorageAccountCredential&gt; with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig.StorageAccountCredentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.StorageAccountCredential&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7adc8-123">必須。</span><span class="sxs-lookup"><span data-stu-id="7adc8-123">Required.</span></span> <span data-ttu-id="7adc8-124">取得またはインポートする構成の xml からストレージ アカウントの資格情報の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="7adc8-124">Gets or sets the list of storage account credentials from config xml to be imported.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetChapSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationChapSetting&gt; TargetChapSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationChapSetting&gt; TargetChapSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig.TargetChapSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetChapSettings As IList(Of MigrationChapSetting)" />
      <MemberSignature Language="F#" Value="member this.TargetChapSettings : System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationChapSetting&gt; with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig.TargetChapSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationChapSetting&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7adc8-125">省略可能。</span><span class="sxs-lookup"><span data-stu-id="7adc8-125">Optional.</span></span> <span data-ttu-id="7adc8-126">取得または設定をインポートする構成 xml からターゲット chap 設定の一覧</span><span class="sxs-lookup"><span data-stu-id="7adc8-126">Gets or sets the  list of target chap settings from config xml to be imported</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalCount">
      <MemberSignature Language="C#" Value="public int TotalCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 TotalCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig.TotalCount" />
      <MemberSignature Language="VB.NET" Value="Public Property TotalCount As Integer" />
      <MemberSignature Language="F#" Value="member this.TotalCount : int with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig.TotalCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7adc8-127">必須。</span><span class="sxs-lookup"><span data-stu-id="7adc8-127">Required.</span></span> <span data-ttu-id="7adc8-128">取得または設定すると、インポートする sub 構成エントリの合計数より小さい構成に分割とインポートされた構成</span><span class="sxs-lookup"><span data-stu-id="7adc8-128">Gets or sets the total count of sub-config entries to be imported, when the config splitted into smaller configs and imported</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VolumeGroups">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskGroup&gt; VolumeGroups { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskGroup&gt; VolumeGroups" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig.VolumeGroups" />
      <MemberSignature Language="VB.NET" Value="Public Property VolumeGroups As IList(Of VirtualDiskGroup)" />
      <MemberSignature Language="F#" Value="member this.VolumeGroups : System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskGroup&gt; with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig.VolumeGroups" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskGroup&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7adc8-129">必須。</span><span class="sxs-lookup"><span data-stu-id="7adc8-129">Required.</span></span> <span data-ttu-id="7adc8-130">取得または設定 (VirtualDiskGroup)、ボリューム グループの一覧をインポートする構成 xml</span><span class="sxs-lookup"><span data-stu-id="7adc8-130">Gets or sets the list of Volume Groups (VirtualDiskGroup) from config xml to be imported</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Volumes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk&gt; Volumes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk&gt; Volumes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig.Volumes" />
      <MemberSignature Language="VB.NET" Value="Public Property Volumes As IList(Of VirtualDisk)" />
      <MemberSignature Language="F#" Value="member this.Volumes : System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk&gt; with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig.Volumes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7adc8-131">必須。</span><span class="sxs-lookup"><span data-stu-id="7adc8-131">Required.</span></span> <span data-ttu-id="7adc8-132">取得または設定 (仮想ディスク) のボリュームの一覧をインポートする構成 xml</span><span class="sxs-lookup"><span data-stu-id="7adc8-132">Gets or sets the list of volumes (virtual disk) from config xml to be imported</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>