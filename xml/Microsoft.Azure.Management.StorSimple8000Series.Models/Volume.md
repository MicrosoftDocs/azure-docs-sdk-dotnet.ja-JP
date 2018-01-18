<Type Name="Volume" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.Volume">
  <TypeSignature Language="C#" Value="public class Volume : Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Volume extends Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.Volume" />
  <TypeSignature Language="VB.NET" Value="Public Class Volume&#xA;Inherits BaseModel" />
  <TypeSignature Language="F#" Value="type Volume = class&#xA;    inherit BaseModel" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="6e4cc-101">ボリューム。</span><span class="sxs-lookup"><span data-stu-id="6e4cc-101">The volume.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Volume ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.Volume.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6e4cc-102">ボリューム クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6e4cc-102">Initializes a new instance of the Volume class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Volume (long sizeInBytes, Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeType volumeType, System.Collections.Generic.IList&lt;string&gt; accessControlRecordIds, Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeStatus volumeStatus, Microsoft.Azure.Management.StorSimple8000Series.Models.MonitoringStatus monitoringStatus, string id = null, string name = null, string type = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind = null, string volumeContainerId = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.OperationStatus&gt; operationStatus = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupStatus&gt; backupStatus = null, System.Collections.Generic.IList&lt;string&gt; backupPolicyIds = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int64 sizeInBytes, valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeType volumeType, class System.Collections.Generic.IList`1&lt;string&gt; accessControlRecordIds, valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeStatus volumeStatus, valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.MonitoringStatus monitoringStatus, string id, string name, string type, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind, string volumeContainerId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.OperationStatus&gt; operationStatus, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.BackupStatus&gt; backupStatus, class System.Collections.Generic.IList`1&lt;string&gt; backupPolicyIds) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.Volume.#ctor(System.Int64,Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeType,System.Collections.Generic.IList{System.String},Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeStatus,Microsoft.Azure.Management.StorSimple8000Series.Models.MonitoringStatus,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.Kind},System.String,System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.OperationStatus},System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.BackupStatus},System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.Volume : int64 * Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeType * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeStatus * Microsoft.Azure.Management.StorSimple8000Series.Models.MonitoringStatus * string * string * string * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; * string * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.OperationStatus&gt; * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupStatus&gt; * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.Volume" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.Volume (sizeInBytes, volumeType, accessControlRecordIds, volumeStatus, monitoringStatus, id, name, type, kind, volumeContainerId, operationStatus, backupStatus, backupPolicyIds)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sizeInBytes" Type="System.Int64" />
        <Parameter Name="volumeType" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeType" />
        <Parameter Name="accessControlRecordIds" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="volumeStatus" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeStatus" />
        <Parameter Name="monitoringStatus" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.MonitoringStatus" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="kind" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt;" />
        <Parameter Name="volumeContainerId" Type="System.String" />
        <Parameter Name="operationStatus" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.OperationStatus&gt;" />
        <Parameter Name="backupStatus" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupStatus&gt;" />
        <Parameter Name="backupPolicyIds" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="sizeInBytes"><span data-ttu-id="6e4cc-103">バイトのボリュームのサイズ。</span><span class="sxs-lookup"><span data-stu-id="6e4cc-103">The size of the volume in bytes.</span></span></param>
        <param name="volumeType"><span data-ttu-id="6e4cc-104">ボリュームの種類。</span><span class="sxs-lookup"><span data-stu-id="6e4cc-104">The type of the volume.</span></span> <span data-ttu-id="6e4cc-105">使用可能な値が含まれます: '階層型'、'アーカイブ'、'LocallyPinned'</span><span class="sxs-lookup"><span data-stu-id="6e4cc-105">Possible values include: 'Tiered', 'Archival', 'LocallyPinned'</span></span></param>
        <param name="accessControlRecordIds"><span data-ttu-id="6e4cc-106">ボリュームに関連付けられている、アクセス制御レコードの Id。</span><span class="sxs-lookup"><span data-stu-id="6e4cc-106">The IDs of the access control records, associated with the volume.</span></span></param>
        <param name="volumeStatus"><span data-ttu-id="6e4cc-107">ボリュームの状態。</span><span class="sxs-lookup"><span data-stu-id="6e4cc-107">The volume status.</span></span> <span data-ttu-id="6e4cc-108">使用可能な値が含まれます: 'オンライン'、'Offline'</span><span class="sxs-lookup"><span data-stu-id="6e4cc-108">Possible values include: 'Online', 'Offline'</span></span></param>
        <param name="monitoringStatus"><span data-ttu-id="6e4cc-109">ボリュームの監視の状態。</span><span class="sxs-lookup"><span data-stu-id="6e4cc-109">The monitoring status of the volume.</span></span>
            <span data-ttu-id="6e4cc-110">使用可能な値が含まれます: 'Enabled'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="6e4cc-110">Possible values include: 'Enabled', 'Disabled'</span></span></param>
        <param name="id"><span data-ttu-id="6e4cc-111">オブジェクトを一意に識別するパス ID です。</span><span class="sxs-lookup"><span data-stu-id="6e4cc-111">The path ID that uniquely identifies the object.</span></span></param>
        <param name="name"><span data-ttu-id="6e4cc-112">オブジェクトの名前。</span><span class="sxs-lookup"><span data-stu-id="6e4cc-112">The name of the object.</span></span></param>
        <param name="type"><span data-ttu-id="6e4cc-113">オブジェクトの階層型です。</span><span class="sxs-lookup"><span data-stu-id="6e4cc-113">The hierarchical type of the object.</span></span></param>
        <param name="kind"><span data-ttu-id="6e4cc-114">オブジェクトの種類。</span><span class="sxs-lookup"><span data-stu-id="6e4cc-114">The Kind of the object.</span></span> <span data-ttu-id="6e4cc-115">現在は Series8000 はサポートされています。</span><span class="sxs-lookup"><span data-stu-id="6e4cc-115">Currently only Series8000 is supported.</span></span> <span data-ttu-id="6e4cc-116">使用可能な値が含まれます: 'Series8000'</span><span class="sxs-lookup"><span data-stu-id="6e4cc-116">Possible values include: 'Series8000'</span></span></param>
        <param name="volumeContainerId"><span data-ttu-id="6e4cc-117">このボリュームが作成される、ボリューム コンテナーの ID。</span><span class="sxs-lookup"><span data-stu-id="6e4cc-117">The ID of the volume container, in which this volume is created.</span></span></param>
        <param name="operationStatus"><span data-ttu-id="6e4cc-118">ボリューム上の操作状態です。</span><span class="sxs-lookup"><span data-stu-id="6e4cc-118">The operation status on the volume.</span></span>
            <span data-ttu-id="6e4cc-119">使用可能な値が含まれます 'None'、'更新'、'削除'、'復元'。</span><span class="sxs-lookup"><span data-stu-id="6e4cc-119">Possible values include: 'None', 'Updating', 'Deleting', 'Restoring'</span></span></param>
        <param name="backupStatus"><span data-ttu-id="6e4cc-120">ボリュームのバックアップの状態。</span><span class="sxs-lookup"><span data-stu-id="6e4cc-120">The backup status of the volume.</span></span>
            <span data-ttu-id="6e4cc-121">使用可能な値が含まれます: 'Enabled'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="6e4cc-121">Possible values include: 'Enabled', 'Disabled'</span></span></param>
        <param name="backupPolicyIds"><span data-ttu-id="6e4cc-122">このボリュームの一部では、バックアップ ポリシーの Id。</span><span class="sxs-lookup"><span data-stu-id="6e4cc-122">The IDs of the backup policies, in which this volume is part of.</span></span></param>
        <summary>
            <span data-ttu-id="6e4cc-123">ボリューム クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6e4cc-123">Initializes a new instance of the Volume class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessControlRecordIds">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; AccessControlRecordIds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; AccessControlRecordIds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Volume.AccessControlRecordIds" />
      <MemberSignature Language="VB.NET" Value="Public Property AccessControlRecordIds As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.AccessControlRecordIds : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Volume.AccessControlRecordIds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.accessControlRecordIds")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e4cc-124">取得またはボリュームに関連付けられている、制御レコードのアクセス権の Id を設定します。</span><span class="sxs-lookup"><span data-stu-id="6e4cc-124">Gets or sets the IDs of the access control records, associated with the volume.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupPolicyIds">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; BackupPolicyIds { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; BackupPolicyIds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Volume.BackupPolicyIds" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupPolicyIds As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.BackupPolicyIds : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Volume.BackupPolicyIds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.backupPolicyIds")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e4cc-125">このボリュームの一部では、バックアップ ポリシーの Id を取得します。</span><span class="sxs-lookup"><span data-stu-id="6e4cc-125">Gets the IDs of the backup policies, in which this volume is part of.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupStatus">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupStatus&gt; BackupStatus { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.BackupStatus&gt; BackupStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Volume.BackupStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupStatus As Nullable(Of BackupStatus)" />
      <MemberSignature Language="F#" Value="member this.BackupStatus : Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupStatus&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Volume.BackupStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.backupStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e4cc-126">ボリュームのバックアップの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="6e4cc-126">Gets the backup status of the volume.</span></span> <span data-ttu-id="6e4cc-127">使用可能な値が含まれます: 'Enabled'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="6e4cc-127">Possible values include: 'Enabled', 'Disabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MonitoringStatus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.MonitoringStatus MonitoringStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.MonitoringStatus MonitoringStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Volume.MonitoringStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property MonitoringStatus As MonitoringStatus" />
      <MemberSignature Language="F#" Value="member this.MonitoringStatus : Microsoft.Azure.Management.StorSimple8000Series.Models.MonitoringStatus with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Volume.MonitoringStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.monitoringStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.MonitoringStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e4cc-128">取得またはボリュームの監視の状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="6e4cc-128">Gets or sets the monitoring status of the volume.</span></span> <span data-ttu-id="6e4cc-129">使用可能な値が含まれます: 'Enabled'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="6e4cc-129">Possible values include: 'Enabled', 'Disabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationStatus">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.OperationStatus&gt; OperationStatus { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.OperationStatus&gt; OperationStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Volume.OperationStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationStatus As Nullable(Of OperationStatus)" />
      <MemberSignature Language="F#" Value="member this.OperationStatus : Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.OperationStatus&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Volume.OperationStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.operationStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.OperationStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e4cc-130">ボリューム上の操作状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="6e4cc-130">Gets the operation status on the volume.</span></span> <span data-ttu-id="6e4cc-131">使用可能な値が含まれます 'None'、'更新'、'削除'、'復元'。</span><span class="sxs-lookup"><span data-stu-id="6e4cc-131">Possible values include: 'None', 'Updating', 'Deleting', 'Restoring'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SizeInBytes">
      <MemberSignature Language="C#" Value="public long SizeInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SizeInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Volume.SizeInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property SizeInBytes As Long" />
      <MemberSignature Language="F#" Value="member this.SizeInBytes : int64 with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Volume.SizeInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sizeInBytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e4cc-132">取得またはボリュームのサイズをバイト単位で設定します。</span><span class="sxs-lookup"><span data-stu-id="6e4cc-132">Gets or sets the size of the volume in bytes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.Volume.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="volume.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6e4cc-133">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="6e4cc-133">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6e4cc-134">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6e4cc-134">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VolumeContainerId">
      <MemberSignature Language="C#" Value="public string VolumeContainerId { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VolumeContainerId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Volume.VolumeContainerId" />
      <MemberSignature Language="VB.NET" Value="Public Property VolumeContainerId As String" />
      <MemberSignature Language="F#" Value="member this.VolumeContainerId : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Volume.VolumeContainerId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.volumeContainerId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e4cc-135">このボリュームが作成される、ボリューム コンテナーの ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="6e4cc-135">Gets the ID of the volume container, in which this volume is created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VolumeStatus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeStatus VolumeStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeStatus VolumeStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Volume.VolumeStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property VolumeStatus As VolumeStatus" />
      <MemberSignature Language="F#" Value="member this.VolumeStatus : Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeStatus with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Volume.VolumeStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.volumeStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e4cc-136">取得またはボリュームの状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="6e4cc-136">Gets or sets the volume status.</span></span> <span data-ttu-id="6e4cc-137">使用可能な値が含まれます: 'オンライン'、'Offline'</span><span class="sxs-lookup"><span data-stu-id="6e4cc-137">Possible values include: 'Online', 'Offline'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VolumeType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeType VolumeType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeType VolumeType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Volume.VolumeType" />
      <MemberSignature Language="VB.NET" Value="Public Property VolumeType As VolumeType" />
      <MemberSignature Language="F#" Value="member this.VolumeType : Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeType with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Volume.VolumeType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.volumeType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e4cc-138">取得またはボリュームの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="6e4cc-138">Gets or sets the type of the volume.</span></span> <span data-ttu-id="6e4cc-139">使用可能な値が含まれます: '階層型'、'アーカイブ'、'LocallyPinned'</span><span class="sxs-lookup"><span data-stu-id="6e4cc-139">Possible values include: 'Tiered', 'Archival', 'LocallyPinned'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>