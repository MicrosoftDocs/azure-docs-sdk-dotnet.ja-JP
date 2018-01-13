<Type Name="DatabaseUpdate" FullName="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate">
  <TypeSignature Language="C#" Value="public class DatabaseUpdate : Microsoft.Azure.Management.Sql.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DatabaseUpdate extends Microsoft.Azure.Management.Sql.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate" />
  <TypeSignature Language="VB.NET" Value="Public Class DatabaseUpdate&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type DatabaseUpdate = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Sql.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="f8ea8-101">データベースの更新を表します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-101">Represents a database update.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DatabaseUpdate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f8ea8-102">DatabaseUpdate クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-102">Initializes a new instance of the DatabaseUpdate class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DatabaseUpdate (string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string collation = null, Nullable&lt;DateTime&gt; creationDate = null, Nullable&lt;long&gt; containmentState = null, Nullable&lt;Guid&gt; currentServiceObjectiveId = null, Nullable&lt;Guid&gt; databaseId = null, Nullable&lt;DateTime&gt; earliestRestoreDate = null, string createMode = null, string sourceDatabaseId = null, Nullable&lt;DateTime&gt; sourceDatabaseDeletionDate = null, Nullable&lt;DateTime&gt; restorePointInTime = null, string recoveryServicesRecoveryPointResourceId = null, string edition = null, string maxSizeBytes = null, Nullable&lt;Guid&gt; requestedServiceObjectiveId = null, string requestedServiceObjectiveName = null, string serviceLevelObjective = null, string status = null, string elasticPoolName = null, string defaultSecondaryLocation = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt; serviceTierAdvisors = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt; transparentDataEncryption = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.RecommendedIndex&gt; recommendedIndex = null, string failoverGroupId = null, Nullable&lt;Microsoft.Azure.Management.Sql.Models.ReadScale&gt; readScale = null, string sampleName = null, Nullable&lt;bool&gt; zoneRedundant = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string collation, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; creationDate, valuetype System.Nullable`1&lt;int64&gt; containmentState, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; currentServiceObjectiveId, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; databaseId, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; earliestRestoreDate, string createMode, string sourceDatabaseId, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; sourceDatabaseDeletionDate, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; restorePointInTime, string recoveryServicesRecoveryPointResourceId, string edition, string maxSizeBytes, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; requestedServiceObjectiveId, string requestedServiceObjectiveName, string serviceLevelObjective, string status, string elasticPoolName, string defaultSecondaryLocation, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt; serviceTierAdvisors, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt; transparentDataEncryption, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.RecommendedIndex&gt; recommendedIndex, string failoverGroupId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.ReadScale&gt; readScale, string sampleName, valuetype System.Nullable`1&lt;bool&gt; zoneRedundant) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.#ctor(System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.Nullable{System.DateTime},System.Nullable{System.Int64},System.Nullable{System.Guid},System.Nullable{System.Guid},System.Nullable{System.DateTime},System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.String,System.String,System.Nullable{System.Guid},System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor},System.Collections.Generic.IList{Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption},System.Collections.Generic.IList{Microsoft.Azure.Management.Sql.Models.RecommendedIndex},System.String,System.Nullable{Microsoft.Azure.Management.Sql.Models.ReadScale},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional collation As String = null, Optional creationDate As Nullable(Of DateTime) = null, Optional containmentState As Nullable(Of Long) = null, Optional currentServiceObjectiveId As Nullable(Of Guid) = null, Optional databaseId As Nullable(Of Guid) = null, Optional earliestRestoreDate As Nullable(Of DateTime) = null, Optional createMode As String = null, Optional sourceDatabaseId As String = null, Optional sourceDatabaseDeletionDate As Nullable(Of DateTime) = null, Optional restorePointInTime As Nullable(Of DateTime) = null, Optional recoveryServicesRecoveryPointResourceId As String = null, Optional edition As String = null, Optional maxSizeBytes As String = null, Optional requestedServiceObjectiveId As Nullable(Of Guid) = null, Optional requestedServiceObjectiveName As String = null, Optional serviceLevelObjective As String = null, Optional status As String = null, Optional elasticPoolName As String = null, Optional defaultSecondaryLocation As String = null, Optional serviceTierAdvisors As IList(Of ServiceTierAdvisor) = null, Optional transparentDataEncryption As IList(Of TransparentDataEncryption) = null, Optional recommendedIndex As IList(Of RecommendedIndex) = null, Optional failoverGroupId As String = null, Optional readScale As Nullable(Of ReadScale) = null, Optional sampleName As String = null, Optional zoneRedundant As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.DatabaseUpdate : string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Nullable&lt;DateTime&gt; * Nullable&lt;int64&gt; * Nullable&lt;Guid&gt; * Nullable&lt;Guid&gt; * Nullable&lt;DateTime&gt; * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * string * string * Nullable&lt;Guid&gt; * string * string * string * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.RecommendedIndex&gt; * string * Nullable&lt;Microsoft.Azure.Management.Sql.Models.ReadScale&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.Sql.Models.DatabaseUpdate" Usage="new Microsoft.Azure.Management.Sql.Models.DatabaseUpdate (id, name, type, tags, collation, creationDate, containmentState, currentServiceObjectiveId, databaseId, earliestRestoreDate, createMode, sourceDatabaseId, sourceDatabaseDeletionDate, restorePointInTime, recoveryServicesRecoveryPointResourceId, edition, maxSizeBytes, requestedServiceObjectiveId, requestedServiceObjectiveName, serviceLevelObjective, status, elasticPoolName, defaultSecondaryLocation, serviceTierAdvisors, transparentDataEncryption, recommendedIndex, failoverGroupId, readScale, sampleName, zoneRedundant)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="collation" Type="System.String" />
        <Parameter Name="creationDate" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="containmentState" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="currentServiceObjectiveId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="databaseId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="earliestRestoreDate" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="createMode" Type="System.String" />
        <Parameter Name="sourceDatabaseId" Type="System.String" />
        <Parameter Name="sourceDatabaseDeletionDate" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="restorePointInTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="recoveryServicesRecoveryPointResourceId" Type="System.String" />
        <Parameter Name="edition" Type="System.String" />
        <Parameter Name="maxSizeBytes" Type="System.String" />
        <Parameter Name="requestedServiceObjectiveId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="requestedServiceObjectiveName" Type="System.String" />
        <Parameter Name="serviceLevelObjective" Type="System.String" />
        <Parameter Name="status" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="defaultSecondaryLocation" Type="System.String" />
        <Parameter Name="serviceTierAdvisors" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt;" />
        <Parameter Name="transparentDataEncryption" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt;" />
        <Parameter Name="recommendedIndex" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.RecommendedIndex&gt;" />
        <Parameter Name="failoverGroupId" Type="System.String" />
        <Parameter Name="readScale" Type="System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.ReadScale&gt;" />
        <Parameter Name="sampleName" Type="System.String" />
        <Parameter Name="zoneRedundant" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="f8ea8-103">リソースの ID</span><span class="sxs-lookup"><span data-stu-id="f8ea8-103">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="f8ea8-104">リソース名。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-104">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="f8ea8-105">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-105">Resource type.</span></span></param>
        <param name="tags"><span data-ttu-id="f8ea8-106">リソース タグ。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-106">Resource tags.</span></span></param>
        <param name="collation"><span data-ttu-id="f8ea8-107">データベースの照合順序です。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-107">The collation of the database.</span></span> <span data-ttu-id="f8ea8-108">CreateMode が既定ではない場合、この値は無視されます。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-108">If createMode is not Default, this value is ignored.</span></span></param>
        <param name="creationDate"><span data-ttu-id="f8ea8-109">データベース (ISO8601 形式) の作成日。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-109">The creation date of the database (ISO8601 format).</span></span></param>
        <param name="containmentState"><span data-ttu-id="f8ea8-110">データベースのコンテインメントの状態。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-110">The containment state of the database.</span></span></param>
        <param name="currentServiceObjectiveId"><span data-ttu-id="f8ea8-111">現在サービス レベル目標の ID データベース。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-111">The current service level objective ID of the database.</span></span> <span data-ttu-id="f8ea8-112">これは、現在アクティブなサービス レベル目標の ID です。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-112">This is the ID of the service level objective that is currently active.</span></span></param>
        <param name="databaseId"><span data-ttu-id="f8ea8-113">データベースの ID。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-113">The ID of the database.</span></span></param>
        <param name="earliestRestoreDate"><span data-ttu-id="f8ea8-114">このレコードの最も早い開始日時を復元は、このデータベース (ISO8601 形式) で使用可能です。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-114">This records the earliest start date and time that restore is available for this database (ISO8601 format).</span></span></param>
        <param name="createMode"><span data-ttu-id="f8ea8-115">データベースの作成モードを指定します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-115">Specifies the mode of database creation.</span></span>
            
             <span data-ttu-id="f8ea8-116">既定値: 通常のデータベースを作成します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-116">Default: regular database creation.</span></span>
            
             <span data-ttu-id="f8ea8-117">: コピーには、既存のデータベースのコピーとして、データベースが作成されます。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-117">Copy: creates a database as a copy of an existing database.</span></span>
             <span data-ttu-id="f8ea8-118">sourceDatabaseId は、ソース データベースのリソース ID として指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-118">sourceDatabaseId must be specified as the resource ID of the source database.</span></span>
             
            <span data-ttu-id="f8ea8-119">OnlineSecondary/NonReadableSecondary: は、既存のデータベースのセカンダリ レプリカ (読み取り可能または不可) としてデータベースを作成します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-119">OnlineSecondary/NonReadableSecondary: creates a database as a (readable or nonreadable) secondary replica of an existing database.</span></span> <span data-ttu-id="f8ea8-120">sourceDatabaseId は、既存のプライマリ データベースのリソース ID として指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-120">sourceDatabaseId must be specified as the resource ID of the existing primary database.</span></span>
             
             <span data-ttu-id="f8ea8-121">PointInTimeRestore: ポイントイン タイム バックアップ、既存のデータベースを復元することによって、データベースを作成します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-121">PointInTimeRestore: Creates a database by restoring a point in time backup of an existing database.</span></span> <span data-ttu-id="f8ea8-122">sourceDatabaseId を既存のデータベースのリソース ID として指定する必要があり、restorePointInTime を指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-122">sourceDatabaseId must be specified as the resource ID of the existing database, and restorePointInTime must be specified.</span></span>
             
             <span data-ttu-id="f8ea8-123">回復:、geo レプリケーションのバックアップを復元することによって、データベースが作成されます。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-123">Recovery: Creates a database by restoring a geo-replicated backup.</span></span>
            <span data-ttu-id="f8ea8-124">sourceDatabaseId は、復元する回復可能なデータベース リソースの ID として指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-124">sourceDatabaseId must be specified as the recoverable database resource ID to restore.</span></span>
             
             <span data-ttu-id="f8ea8-125">復元:、削除されたデータベースのバックアップを復元することによって、データベースが作成されます。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-125">Restore: Creates a database by restoring a backup of a deleted database.</span></span> <span data-ttu-id="f8ea8-126">sourceDatabaseId を指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-126">sourceDatabaseId must be specified.</span></span> <span data-ttu-id="f8ea8-127">SourceDatabaseId がデータベースの元のリソース ID である場合は、sourceDatabaseDeletionDate を指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-127">If sourceDatabaseId is the database's original resource ID, then sourceDatabaseDeletionDate must be specified.</span></span> <span data-ttu-id="f8ea8-128">それ以外の場合 sourceDatabaseId は削除されたデータベースの復元可能なリソース ID である必要があり、sourceDatabaseDeletionDate は無視されます。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-128">Otherwise sourceDatabaseId must be the restorable dropped database resource ID and sourceDatabaseDeletionDate is ignored.</span></span> <span data-ttu-id="f8ea8-129">restorePointInTime はの以前の時点から復元するも指定することがあります。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-129">restorePointInTime may also be specified to restore from an earlier point in time.</span></span>
             
             <span data-ttu-id="f8ea8-130">RestoreLongTermRetentionBackup:、長期的な保存の資格情報コンテナーから復元することによって、データベースが作成されます。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-130">RestoreLongTermRetentionBackup: Creates a database by restoring from a long term retention vault.</span></span>
            <span data-ttu-id="f8ea8-131">回復ポイントのリソース ID として recoveryServicesRecoveryPointResourceId を指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-131">recoveryServicesRecoveryPointResourceId must be specified as the recovery point resource ID.</span></span>
             
             <span data-ttu-id="f8ea8-132">DataWarehouse エディションには、コピー、NonReadableSecondary、OnlineSecondary および RestoreLongTermRetentionBackup はサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-132">Copy, NonReadableSecondary, OnlineSecondary and RestoreLongTermRetentionBackup are not supported for DataWarehouse edition.</span></span> <span data-ttu-id="f8ea8-133">使用可能な値が含まれます: 'コピー'、'Default'、'NonReadableSecondary'、'OnlineSecondary'、'PointInTimeRestore'、' 復旧'、'Restore'、'RestoreLongTermRetentionBackup'</span><span class="sxs-lookup"><span data-stu-id="f8ea8-133">Possible values include: 'Copy', 'Default', 'NonReadableSecondary', 'OnlineSecondary', 'PointInTimeRestore', 'Recovery', 'Restore', 'RestoreLongTermRetentionBackup'</span></span></param>
        <param name="sourceDatabaseId"><span data-ttu-id="f8ea8-134">条件付きです。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-134">Conditional.</span></span> <span data-ttu-id="f8ea8-135">CreateMode がコピー、NonReadableSecondary、OnlineSecondary、PointInTimeRestore、復旧、または復元の場合は、この値が必要です。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-135">If createMode is Copy, NonReadableSecondary, OnlineSecondary, PointInTimeRestore, Recovery, or Restore, then this value is required.</span></span> <span data-ttu-id="f8ea8-136">ソース データベースのリソース ID を指定します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-136">Specifies the resource ID of the source database.</span></span> <span data-ttu-id="f8ea8-137">CreateMode が NonReadableSecondary または OnlineSecondary の場合は、ソース データベースの名前を作成する新しいデータベースと同じにする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-137">If createMode is NonReadableSecondary or OnlineSecondary, the name of the source database must be the same as the new database being created.</span></span></param>
        <param name="sourceDatabaseDeletionDate"><span data-ttu-id="f8ea8-138">条件付きです。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-138">Conditional.</span></span> <span data-ttu-id="f8ea8-139">CreateMode は復元 sourceDatabaseId は削除されたデータベースの元のリソース id ではなく、現在の復元可能な削除されたデータベース id) に存在していた場合は、この値が必要です。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-139">If createMode is Restore and sourceDatabaseId is the deleted database's original resource id when it existed (as opposed to its current restorable dropped database id), then this value is required.</span></span> <span data-ttu-id="f8ea8-140">データベースが削除された日時を指定します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-140">Specifies the time that the database was deleted.</span></span></param>
        <param name="restorePointInTime"><span data-ttu-id="f8ea8-141">条件付きです。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-141">Conditional.</span></span> <span data-ttu-id="f8ea8-142">CreateMode が PointInTimeRestore の場合は、この値が必要です。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-142">If createMode is PointInTimeRestore, this value is required.</span></span> <span data-ttu-id="f8ea8-143">CreateMode が復元の場合は、この値は省略できます。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-143">If createMode is Restore, this value is optional.</span></span> <span data-ttu-id="f8ea8-144">新しいデータベースを作成する復元するソース データベースの時刻 (ISO8601 形式) で、ポイントを指定します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-144">Specifies the point in time (ISO8601 format) of the source database that will be restored to create the new database.</span></span> <span data-ttu-id="f8ea8-145">ソース データベースの earliestRestoreDate 値以上にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-145">Must be greater than or equal to the source database's earliestRestoreDate value.</span></span></param>
        <param name="recoveryServicesRecoveryPointResourceId"><span data-ttu-id="f8ea8-146">条件付きです。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-146">Conditional.</span></span>
             <span data-ttu-id="f8ea8-147">CreateMode が RestoreLongTermRetentionBackup の場合は、この値が必要です。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-147">If createMode is RestoreLongTermRetentionBackup, then this value is required.</span></span> <span data-ttu-id="f8ea8-148">復元する回復ポイントのリソース ID を指定します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-148">Specifies the resource ID of the recovery point to restore from.</span></span></param>
        <param name="edition"><span data-ttu-id="f8ea8-149">データベースのエディションです。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-149">The edition of the database.</span></span> <span data-ttu-id="f8ea8-150">DatabaseEditions 列挙には、有効なすべてのエディションが含まれています。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-150">The DatabaseEditions enumeration contains all the valid editions.</span></span> <span data-ttu-id="f8ea8-151">CreateMode が NonReadableSecondary または OnlineSecondary の場合は、この値は無視されます。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-151">If createMode is NonReadableSecondary or OnlineSecondary, this value is ignored.</span></span> <span data-ttu-id="f8ea8-152">クエリ機能 API に指定できる値を表示する (/subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) operationId によって参照される:"Capabilities_ListByLocation"です。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-152">To see possible values, query the capabilities API (/subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) referred to by operationId: "Capabilities_ListByLocation.".</span></span>
             <span data-ttu-id="f8ea8-153">使用可能な値が含まれます: 'Web'、'ビジネス'、'Basic'、'Standard'、'Premium'、'無料'、'拡大'、'データ ウェアハウス'、'System'、'システム 2'</span><span class="sxs-lookup"><span data-stu-id="f8ea8-153">Possible values include: 'Web', 'Business', 'Basic', 'Standard', 'Premium', 'Free', 'Stretch', 'DataWarehouse', 'System', 'System2'</span></span></param>
        <param name="maxSizeBytes"><span data-ttu-id="f8ea8-154">バイト単位で表されるデータベースの最大サイズ。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-154">The max size of the database expressed in bytes.</span></span> <span data-ttu-id="f8ea8-155">CreateMode が既定ではない場合、この値は無視されます。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-155">If createMode is not Default, this value is ignored.</span></span> <span data-ttu-id="f8ea8-156">クエリ機能 API に指定できる値を表示する (/subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) operationId によって参照される:"Capabilities_ListByLocation"。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-156">To see possible values, query the capabilities API (/subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) referred to by operationId: "Capabilities_ListByLocation."</span></span></param>
        <param name="requestedServiceObjectiveId"><span data-ttu-id="f8ea8-157">データベースの構成済みのサービス レベル目標 ID。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-157">The configured service level objective ID of the database.</span></span> <span data-ttu-id="f8ea8-158">これは、データベースに適用されているプロセスでは、サービス レベル目標です。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-158">This is the service level objective that is in the process of being applied to the database.</span></span>
             <span data-ttu-id="f8ea8-159">正常に更新されると、その currentServiceObjectiveId プロパティの値は一致します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-159">Once successfully updated, it will match the value of currentServiceObjectiveId property.</span></span> <span data-ttu-id="f8ea8-160">RequestedServiceObjectiveId と requestedServiceObjectiveName がどちらも更新された場合、requestedServiceObjectiveId の値は requestedServiceObjectiveName の値をオーバーライドします。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-160">If requestedServiceObjectiveId and requestedServiceObjectiveName are both updated, the value of requestedServiceObjectiveId overrides the value of requestedServiceObjectiveName.</span></span> <span data-ttu-id="f8ea8-161">クエリ機能 API に指定できる値を表示する (/subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) operationId によって参照される:"Capabilities_ListByLocation"。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-161">To see possible values, query the capabilities API (/subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) referred to by operationId: "Capabilities_ListByLocation."</span></span></param>
        <param name="requestedServiceObjectiveName"><span data-ttu-id="f8ea8-162">データベースの構成済みのサービス レベル目標の名前。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-162">The name of the configured service level objective of the database.</span></span> <span data-ttu-id="f8ea8-163">これは、データベースに適用されているプロセスでは、サービス レベル目標です。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-163">This is the service level objective that is in the process of being applied to the database.</span></span> <span data-ttu-id="f8ea8-164">正常に更新されると、サービス レベル目標のプロパティの値には一致します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-164">Once successfully updated, it will match the value of serviceLevelObjective property.</span></span> <span data-ttu-id="f8ea8-165">クエリ機能 API に指定できる値を表示する (/subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) operationId によって参照される:"Capabilities_ListByLocation"です。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-165">To see possible values, query the capabilities API (/subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) referred to by operationId: "Capabilities_ListByLocation.".</span></span>
             <span data-ttu-id="f8ea8-166">使用可能な値が含まれます: 'Basic'、'S0'、'S1'、'S2'、'S3'、'P1'、'P2'、'P3'、'P4'、'P6'、'P11'、'P15'、'System'、'システム 2'、'ElasticPool'</span><span class="sxs-lookup"><span data-stu-id="f8ea8-166">Possible values include: 'Basic', 'S0', 'S1', 'S2', 'S3', 'P1', 'P2', 'P3', 'P4', 'P6', 'P11', 'P15', 'System', 'System2', 'ElasticPool'</span></span></param>
        <param name="serviceLevelObjective"><span data-ttu-id="f8ea8-167">現在サービス レベル目標のデータベースです。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-167">The current service level objective of the database.</span></span> <span data-ttu-id="f8ea8-168">使用可能な値が含まれます: 'Basic'、'S0'、'S1'、'S2'、'S3'、'P1'、'P2'、'P3'、'P4'、'P6'、'P11'、'P15'、'System'、'システム 2'、'ElasticPool'</span><span class="sxs-lookup"><span data-stu-id="f8ea8-168">Possible values include: 'Basic', 'S0', 'S1', 'S2', 'S3', 'P1', 'P2', 'P3', 'P4', 'P6', 'P11', 'P15', 'System', 'System2', 'ElasticPool'</span></span></param>
        <param name="status"><span data-ttu-id="f8ea8-169">データベースの状態。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-169">The status of the database.</span></span></param>
        <param name="elasticPoolName"><span data-ttu-id="f8ea8-170">弾力性プール データベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-170">The name of the elastic pool the database is in.</span></span> <span data-ttu-id="f8ea8-171">ElasticPoolName と requestedServiceObjectiveName がどちらも更新された場合、requestedServiceObjectiveName の値は無視されます。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-171">If elasticPoolName and requestedServiceObjectiveName are both updated, the value of requestedServiceObjectiveName is ignored.</span></span> <span data-ttu-id="f8ea8-172">DataWarehouse エディションのサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-172">Not supported for DataWarehouse edition.</span></span></param>
        <param name="defaultSecondaryLocation"><span data-ttu-id="f8ea8-173">このデータベースの既定のセカンダリ地域。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-173">The default secondary region for this database.</span></span></param>
        <param name="serviceTierAdvisors"><span data-ttu-id="f8ea8-174">このデータベースのサービス層アドバイザーの一覧。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-174">The list of service tier advisors for this database.</span></span> <span data-ttu-id="f8ea8-175">展開されたプロパティ</span><span class="sxs-lookup"><span data-stu-id="f8ea8-175">Expanded property</span></span></param>
        <param name="transparentDataEncryption"><span data-ttu-id="f8ea8-176">透過的なデータ暗号化は、このデータベースの情報です。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-176">The transparent data encryption info for this database.</span></span></param>
        <param name="recommendedIndex"><span data-ttu-id="f8ea8-177">このデータベースの推奨されるインデックスです。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-177">The recommended indices for this database.</span></span></param>
        <param name="failoverGroupId"><span data-ttu-id="f8ea8-178">このデータベースを含むグループのフェールオーバーのリソースの識別子です。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-178">The resource identifier of the failover group containing this database.</span></span></param>
        <param name="readScale"><span data-ttu-id="f8ea8-179">条件付きです。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-179">Conditional.</span></span> <span data-ttu-id="f8ea8-180">データベースが地理的セカンダリの場合は、readScale はかに、このデータベースに対する読み取り専用の接続を許可するかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-180">If the database is a geo-secondary, readScale indicates whether read-only connections are allowed to this database or not.</span></span> <span data-ttu-id="f8ea8-181">DataWarehouse エディションのサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-181">Not supported for DataWarehouse edition.</span></span> <span data-ttu-id="f8ea8-182">使用可能な値が含まれます: 'Enabled'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="f8ea8-182">Possible values include: 'Enabled', 'Disabled'</span></span></param>
        <param name="sampleName"><span data-ttu-id="f8ea8-183">このデータベースを作成するときに適用するサンプルのスキーマの名前を示します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-183">Indicates the name of the sample schema to apply when creating this database.</span></span> <span data-ttu-id="f8ea8-184">CreateMode が既定ではない場合、この値は無視されます。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-184">If createMode is not Default, this value is ignored.</span></span> <span data-ttu-id="f8ea8-185">DataWarehouse エディションのサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-185">Not supported for DataWarehouse edition.</span></span>
             <span data-ttu-id="f8ea8-186">使用可能な値が含まれます: 'AdventureWorksLT'</span><span class="sxs-lookup"><span data-stu-id="f8ea8-186">Possible values include: 'AdventureWorksLT'</span></span></param>
        <param name="zoneRedundant"><span data-ttu-id="f8ea8-187">このデータベースは、ゾーン冗長、このデータベースのレプリカを意味するかどうかは、複数の可用性ゾーン間で分散行われます。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-187">Whether or not this database is zone redundant, which means the replicas of this database will be spread across multiple availability zones.</span></span></param>
        <summary>
             <span data-ttu-id="f8ea8-188">DatabaseUpdate クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-188">Initializes a new instance of the DatabaseUpdate class.</span></span>
             </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Collation">
      <MemberSignature Language="C#" Value="public string Collation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Collation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.Collation" />
      <MemberSignature Language="VB.NET" Value="Public Property Collation As String" />
      <MemberSignature Language="F#" Value="member this.Collation : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.Collation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.collation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8ea8-189">取得またはデータベースの照合順序を設定します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-189">Gets or sets the collation of the database.</span></span> <span data-ttu-id="f8ea8-190">CreateMode が既定ではない場合、この値は無視されます。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-190">If createMode is not Default, this value is ignored.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainmentState">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; ContainmentState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; ContainmentState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.ContainmentState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContainmentState As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.ContainmentState : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.ContainmentState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.containmentState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8ea8-191">データベースの包含状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-191">Gets the containment state of the database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMode">
      <MemberSignature Language="C#" Value="public string CreateMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CreateMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.CreateMode" />
      <MemberSignature Language="VB.NET" Value="Public Property CreateMode As String" />
      <MemberSignature Language="F#" Value="member this.CreateMode : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.CreateMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.createMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
             <span data-ttu-id="f8ea8-192">取得または設定は、データベースの作成モードを指定します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-192">Gets or sets specifies the mode of database creation.</span></span>
            
             <span data-ttu-id="f8ea8-193">既定値: 通常のデータベースを作成します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-193">Default: regular database creation.</span></span>
            
             <span data-ttu-id="f8ea8-194">: コピーには、既存のデータベースのコピーとして、データベースが作成されます。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-194">Copy: creates a database as a copy of an existing database.</span></span>
             <span data-ttu-id="f8ea8-195">sourceDatabaseId は、ソース データベースのリソース ID として指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-195">sourceDatabaseId must be specified as the resource ID of the source database.</span></span>
             
            <span data-ttu-id="f8ea8-196">OnlineSecondary/NonReadableSecondary: は、既存のデータベースのセカンダリ レプリカ (読み取り可能または不可) としてデータベースを作成します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-196">OnlineSecondary/NonReadableSecondary: creates a database as a (readable or nonreadable) secondary replica of an existing database.</span></span> <span data-ttu-id="f8ea8-197">sourceDatabaseId は、既存のプライマリ データベースのリソース ID として指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-197">sourceDatabaseId must be specified as the resource ID of the existing primary database.</span></span>
             
             <span data-ttu-id="f8ea8-198">PointInTimeRestore: ポイントイン タイム バックアップ、既存のデータベースを復元することによって、データベースを作成します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-198">PointInTimeRestore: Creates a database by restoring a point in time backup of an existing database.</span></span> <span data-ttu-id="f8ea8-199">sourceDatabaseId を既存のデータベースのリソース ID として指定する必要があり、restorePointInTime を指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-199">sourceDatabaseId must be specified as the resource ID of the existing database, and restorePointInTime must be specified.</span></span>
             
             <span data-ttu-id="f8ea8-200">回復:、geo レプリケーションのバックアップを復元することによって、データベースが作成されます。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-200">Recovery: Creates a database by restoring a geo-replicated backup.</span></span>
            <span data-ttu-id="f8ea8-201">sourceDatabaseId は、復元する回復可能なデータベース リソースの ID として指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-201">sourceDatabaseId must be specified as the recoverable database resource ID to restore.</span></span>
             
             <span data-ttu-id="f8ea8-202">復元:、削除されたデータベースのバックアップを復元することによって、データベースが作成されます。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-202">Restore: Creates a database by restoring a backup of a deleted database.</span></span> <span data-ttu-id="f8ea8-203">sourceDatabaseId を指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-203">sourceDatabaseId must be specified.</span></span> <span data-ttu-id="f8ea8-204">SourceDatabaseId がデータベースの元のリソース ID である場合は、sourceDatabaseDeletionDate を指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-204">If sourceDatabaseId is the database's original resource ID, then sourceDatabaseDeletionDate must be specified.</span></span> <span data-ttu-id="f8ea8-205">それ以外の場合 sourceDatabaseId は削除されたデータベースの復元可能なリソース ID である必要があり、sourceDatabaseDeletionDate は無視されます。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-205">Otherwise sourceDatabaseId must be the restorable dropped database resource ID and sourceDatabaseDeletionDate is ignored.</span></span> <span data-ttu-id="f8ea8-206">restorePointInTime はの以前の時点から復元するも指定することがあります。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-206">restorePointInTime may also be specified to restore from an earlier point in time.</span></span>
             
             <span data-ttu-id="f8ea8-207">RestoreLongTermRetentionBackup:、長期的な保存の資格情報コンテナーから復元することによって、データベースが作成されます。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-207">RestoreLongTermRetentionBackup: Creates a database by restoring from a long term retention vault.</span></span>
            <span data-ttu-id="f8ea8-208">回復ポイントのリソース ID として recoveryServicesRecoveryPointResourceId を指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-208">recoveryServicesRecoveryPointResourceId must be specified as the recovery point resource ID.</span></span>
             
             <span data-ttu-id="f8ea8-209">DataWarehouse エディションには、コピー、NonReadableSecondary、OnlineSecondary および RestoreLongTermRetentionBackup はサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-209">Copy, NonReadableSecondary, OnlineSecondary and RestoreLongTermRetentionBackup are not supported for DataWarehouse edition.</span></span> <span data-ttu-id="f8ea8-210">使用可能な値が含まれます: 'コピー'、'Default'、'NonReadableSecondary'、'OnlineSecondary'、'PointInTimeRestore'、' 復旧'、'Restore'、'RestoreLongTermRetentionBackup'</span><span class="sxs-lookup"><span data-stu-id="f8ea8-210">Possible values include: 'Copy', 'Default', 'NonReadableSecondary', 'OnlineSecondary', 'PointInTimeRestore', 'Recovery', 'Restore', 'RestoreLongTermRetentionBackup'</span></span>
             </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreationDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreationDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.CreationDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreationDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreationDate : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.CreationDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.creationDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8ea8-211">データベース (ISO8601 形式) の作成日を取得します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-211">Gets the creation date of the database (ISO8601 format).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentServiceObjectiveId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; CurrentServiceObjectiveId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; CurrentServiceObjectiveId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.CurrentServiceObjectiveId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentServiceObjectiveId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.CurrentServiceObjectiveId : Nullable&lt;Guid&gt;" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.CurrentServiceObjectiveId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.currentServiceObjectiveId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8ea8-212">サービス レベル目標の現在の ID、データベースを取得します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-212">Gets the current service level objective ID of the database.</span></span> <span data-ttu-id="f8ea8-213">これは、現在アクティブなサービス レベル目標の ID です。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-213">This is the ID of the service level objective that is currently active.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; DatabaseId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; DatabaseId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.DatabaseId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.DatabaseId : Nullable&lt;Guid&gt;" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.DatabaseId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.databaseId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8ea8-214">データベースの ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-214">Gets the ID of the database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultSecondaryLocation">
      <MemberSignature Language="C#" Value="public string DefaultSecondaryLocation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DefaultSecondaryLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.DefaultSecondaryLocation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultSecondaryLocation As String" />
      <MemberSignature Language="F#" Value="member this.DefaultSecondaryLocation : string" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.DefaultSecondaryLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.defaultSecondaryLocation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8ea8-215">このデータベースの既定のセカンダリ地域を取得します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-215">Gets the default secondary region for this database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EarliestRestoreDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EarliestRestoreDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EarliestRestoreDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.EarliestRestoreDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EarliestRestoreDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EarliestRestoreDate : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.EarliestRestoreDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.earliestRestoreDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8ea8-216">このデータベース (ISO8601 形式) のこのレコードの最も早い開始日時を復元するが取得します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-216">Gets this records the earliest start date and time that restore is available for this database (ISO8601 format).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Edition">
      <MemberSignature Language="C#" Value="public string Edition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Edition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.Edition" />
      <MemberSignature Language="VB.NET" Value="Public Property Edition As String" />
      <MemberSignature Language="F#" Value="member this.Edition : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.Edition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.edition")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8ea8-217">取得またはデータベースのエディションを設定します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-217">Gets or sets the edition of the database.</span></span> <span data-ttu-id="f8ea8-218">DatabaseEditions 列挙には、有効なすべてのエディションが含まれています。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-218">The DatabaseEditions enumeration contains all the valid editions.</span></span> <span data-ttu-id="f8ea8-219">CreateMode が NonReadableSecondary または OnlineSecondary の場合は、この値は無視されます。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-219">If createMode is NonReadableSecondary or OnlineSecondary, this value is ignored.</span></span> <span data-ttu-id="f8ea8-220">クエリ機能 API に指定できる値を表示する (/subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) operationId によって参照される:"Capabilities_ListByLocation"です。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-220">To see possible values, query the capabilities API (/subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) referred to by operationId: "Capabilities_ListByLocation.".</span></span>
            <span data-ttu-id="f8ea8-221">使用可能な値が含まれます: 'Web'、'ビジネス'、'Basic'、'Standard'、'Premium'、'無料'、'拡大'、'データ ウェアハウス'、'System'、'システム 2'</span><span class="sxs-lookup"><span data-stu-id="f8ea8-221">Possible values include: 'Web', 'Business', 'Basic', 'Standard', 'Premium', 'Free', 'Stretch', 'DataWarehouse', 'System', 'System2'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ElasticPoolName">
      <MemberSignature Language="C#" Value="public string ElasticPoolName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ElasticPoolName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.ElasticPoolName" />
      <MemberSignature Language="VB.NET" Value="Public Property ElasticPoolName As String" />
      <MemberSignature Language="F#" Value="member this.ElasticPoolName : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.ElasticPoolName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.elasticPoolName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8ea8-222">取得またはデータベースが弾力性プールの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-222">Gets or sets the name of the elastic pool the database is in.</span></span> <span data-ttu-id="f8ea8-223">ElasticPoolName と requestedServiceObjectiveName がどちらも更新された場合、requestedServiceObjectiveName の値は無視されます。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-223">If elasticPoolName and requestedServiceObjectiveName are both updated, the value of requestedServiceObjectiveName is ignored.</span></span> <span data-ttu-id="f8ea8-224">DataWarehouse エディションのサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-224">Not supported for DataWarehouse edition.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailoverGroupId">
      <MemberSignature Language="C#" Value="public string FailoverGroupId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FailoverGroupId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.FailoverGroupId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FailoverGroupId As String" />
      <MemberSignature Language="F#" Value="member this.FailoverGroupId : string" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.FailoverGroupId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.failoverGroupId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8ea8-225">このデータベースを含むグループのフェールオーバーのリソース識別子を取得します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-225">Gets the resource identifier of the failover group containing this database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxSizeBytes">
      <MemberSignature Language="C#" Value="public string MaxSizeBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MaxSizeBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.MaxSizeBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxSizeBytes As String" />
      <MemberSignature Language="F#" Value="member this.MaxSizeBytes : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.MaxSizeBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maxSizeBytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8ea8-226">取得またはバイト数で表されるデータベースの最大サイズを設定します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-226">Gets or sets the max size of the database expressed in bytes.</span></span> <span data-ttu-id="f8ea8-227">CreateMode が既定ではない場合、この値は無視されます。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-227">If createMode is not Default, this value is ignored.</span></span> <span data-ttu-id="f8ea8-228">クエリ機能 API に指定できる値を表示する (/subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) operationId によって参照される:"Capabilities_ListByLocation"。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-228">To see possible values, query the capabilities API (/subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) referred to by operationId: "Capabilities_ListByLocation."</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadScale">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Sql.Models.ReadScale&gt; ReadScale { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.ReadScale&gt; ReadScale" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.ReadScale" />
      <MemberSignature Language="VB.NET" Value="Public Property ReadScale As Nullable(Of ReadScale)" />
      <MemberSignature Language="F#" Value="member this.ReadScale : Nullable&lt;Microsoft.Azure.Management.Sql.Models.ReadScale&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.ReadScale" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.readScale")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.ReadScale&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8ea8-229">取得または条件を設定します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-229">Gets or sets conditional.</span></span> <span data-ttu-id="f8ea8-230">データベースが地理的セカンダリの場合は、readScale はかに、このデータベースに対する読み取り専用の接続を許可するかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-230">If the database is a geo-secondary, readScale indicates whether read-only connections are allowed to this database or not.</span></span> <span data-ttu-id="f8ea8-231">DataWarehouse エディションのサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-231">Not supported for DataWarehouse edition.</span></span>
            <span data-ttu-id="f8ea8-232">使用可能な値が含まれます: 'Enabled'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="f8ea8-232">Possible values include: 'Enabled', 'Disabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecommendedIndex">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.RecommendedIndex&gt; RecommendedIndex { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.RecommendedIndex&gt; RecommendedIndex" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.RecommendedIndex" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RecommendedIndex As IList(Of RecommendedIndex)" />
      <MemberSignature Language="F#" Value="member this.RecommendedIndex : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.RecommendedIndex&gt;" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.RecommendedIndex" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.recommendedIndex")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.RecommendedIndex&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8ea8-233">このデータベースの推奨インデックスを取得します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-233">Gets the recommended indices for this database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoveryServicesRecoveryPointResourceId">
      <MemberSignature Language="C#" Value="public string RecoveryServicesRecoveryPointResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RecoveryServicesRecoveryPointResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.RecoveryServicesRecoveryPointResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property RecoveryServicesRecoveryPointResourceId As String" />
      <MemberSignature Language="F#" Value="member this.RecoveryServicesRecoveryPointResourceId : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.RecoveryServicesRecoveryPointResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.recoveryServicesRecoveryPointResourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8ea8-234">取得または条件を設定します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-234">Gets or sets conditional.</span></span> <span data-ttu-id="f8ea8-235">CreateMode が RestoreLongTermRetentionBackup の場合は、この値が必要です。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-235">If createMode is RestoreLongTermRetentionBackup, then this value is required.</span></span>
            <span data-ttu-id="f8ea8-236">復元する回復ポイントのリソース ID を指定します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-236">Specifies the resource ID of the recovery point to restore from.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestedServiceObjectiveId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; RequestedServiceObjectiveId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; RequestedServiceObjectiveId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.RequestedServiceObjectiveId" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestedServiceObjectiveId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.RequestedServiceObjectiveId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.RequestedServiceObjectiveId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.requestedServiceObjectiveId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8ea8-237">取得またはデータベースの構成済みのサービス レベル目標の ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-237">Gets or sets the configured service level objective ID of the database.</span></span> <span data-ttu-id="f8ea8-238">これは、データベースに適用されているプロセスでは、サービス レベル目標です。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-238">This is the service level objective that is in the process of being applied to the database.</span></span> <span data-ttu-id="f8ea8-239">正常に更新されると、その currentServiceObjectiveId プロパティの値は一致します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-239">Once successfully updated, it will match the value of currentServiceObjectiveId property.</span></span> <span data-ttu-id="f8ea8-240">RequestedServiceObjectiveId と requestedServiceObjectiveName がどちらも更新された場合、requestedServiceObjectiveId の値は requestedServiceObjectiveName の値をオーバーライドします。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-240">If requestedServiceObjectiveId and requestedServiceObjectiveName are both updated, the value of requestedServiceObjectiveId overrides the value of requestedServiceObjectiveName.</span></span> <span data-ttu-id="f8ea8-241">クエリ機能 API に指定できる値を表示する (/subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) operationId によって参照される:"Capabilities_ListByLocation"。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-241">To see possible values, query the capabilities API (/subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) referred to by operationId: "Capabilities_ListByLocation."</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestedServiceObjectiveName">
      <MemberSignature Language="C#" Value="public string RequestedServiceObjectiveName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestedServiceObjectiveName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.RequestedServiceObjectiveName" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestedServiceObjectiveName As String" />
      <MemberSignature Language="F#" Value="member this.RequestedServiceObjectiveName : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.RequestedServiceObjectiveName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.requestedServiceObjectiveName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8ea8-242">取得またはデータベースの構成済みのサービス レベル目標の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-242">Gets or sets the name of the configured service level objective of the database.</span></span> <span data-ttu-id="f8ea8-243">これは、データベースに適用されているプロセスでは、サービス レベル目標です。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-243">This is the service level objective that is in the process of being applied to the database.</span></span> <span data-ttu-id="f8ea8-244">正常に更新されると、サービス レベル目標のプロパティの値には一致します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-244">Once successfully updated, it will match the value of serviceLevelObjective property.</span></span>
            <span data-ttu-id="f8ea8-245">クエリ機能 API に指定できる値を表示する (/subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) operationId によって参照される:"Capabilities_ListByLocation"です。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-245">To see possible values, query the capabilities API (/subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) referred to by operationId: "Capabilities_ListByLocation.".</span></span>
            <span data-ttu-id="f8ea8-246">使用可能な値が含まれます: 'Basic'、'S0'、'S1'、'S2'、'S3'、'P1'、'P2'、'P3'、'P4'、'P6'、'P11'、'P15'、'System'、'システム 2'、'ElasticPool'</span><span class="sxs-lookup"><span data-stu-id="f8ea8-246">Possible values include: 'Basic', 'S0', 'S1', 'S2', 'S3', 'P1', 'P2', 'P3', 'P4', 'P6', 'P11', 'P15', 'System', 'System2', 'ElasticPool'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestorePointInTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; RestorePointInTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; RestorePointInTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.RestorePointInTime" />
      <MemberSignature Language="VB.NET" Value="Public Property RestorePointInTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.RestorePointInTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.RestorePointInTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.restorePointInTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8ea8-247">取得または条件を設定します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-247">Gets or sets conditional.</span></span> <span data-ttu-id="f8ea8-248">CreateMode が PointInTimeRestore の場合は、この値が必要です。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-248">If createMode is PointInTimeRestore, this value is required.</span></span> <span data-ttu-id="f8ea8-249">CreateMode が復元の場合は、この値は省略できます。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-249">If createMode is Restore, this value is optional.</span></span> <span data-ttu-id="f8ea8-250">新しいデータベースを作成する復元するソース データベースの時刻 (ISO8601 形式) で、ポイントを指定します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-250">Specifies the point in time (ISO8601 format) of the source database that will be restored to create the new database.</span></span>
            <span data-ttu-id="f8ea8-251">ソース データベースの earliestRestoreDate 値以上にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-251">Must be greater than or equal to the source database's earliestRestoreDate value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SampleName">
      <MemberSignature Language="C#" Value="public string SampleName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SampleName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.SampleName" />
      <MemberSignature Language="VB.NET" Value="Public Property SampleName As String" />
      <MemberSignature Language="F#" Value="member this.SampleName : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.SampleName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sampleName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8ea8-252">取得または設定は、このデータベースを作成するときに適用するサンプルのスキーマの名前を示します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-252">Gets or sets indicates the name of the sample schema to apply when creating this database.</span></span> <span data-ttu-id="f8ea8-253">CreateMode が既定ではない場合、この値は無視されます。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-253">If createMode is not Default, this value is ignored.</span></span> <span data-ttu-id="f8ea8-254">DataWarehouse エディションのサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-254">Not supported for DataWarehouse edition.</span></span> <span data-ttu-id="f8ea8-255">使用可能な値が含まれます: 'AdventureWorksLT'</span><span class="sxs-lookup"><span data-stu-id="f8ea8-255">Possible values include: 'AdventureWorksLT'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceLevelObjective">
      <MemberSignature Language="C#" Value="public string ServiceLevelObjective { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceLevelObjective" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.ServiceLevelObjective" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceLevelObjective As String" />
      <MemberSignature Language="F#" Value="member this.ServiceLevelObjective : string" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.ServiceLevelObjective" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serviceLevelObjective")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8ea8-256">データベースの現在のサービス レベル目標を取得します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-256">Gets the current service level objective of the database.</span></span> <span data-ttu-id="f8ea8-257">使用可能な値が含まれます: 'Basic'、'S0'、'S1'、'S2'、'S3'、'P1'、'P2'、'P3'、'P4'、'P6'、'P11'、'P15'、'System'、'システム 2'、'ElasticPool'</span><span class="sxs-lookup"><span data-stu-id="f8ea8-257">Possible values include: 'Basic', 'S0', 'S1', 'S2', 'S3', 'P1', 'P2', 'P3', 'P4', 'P6', 'P11', 'P15', 'System', 'System2', 'ElasticPool'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceTierAdvisors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt; ServiceTierAdvisors { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt; ServiceTierAdvisors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.ServiceTierAdvisors" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceTierAdvisors As IList(Of ServiceTierAdvisor)" />
      <MemberSignature Language="F#" Value="member this.ServiceTierAdvisors : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt;" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.ServiceTierAdvisors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serviceTierAdvisors")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8ea8-258">このデータベースのサービス層アドバイザーの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-258">Gets the list of service tier advisors for this database.</span></span> <span data-ttu-id="f8ea8-259">展開されたプロパティ</span><span class="sxs-lookup"><span data-stu-id="f8ea8-259">Expanded property</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceDatabaseDeletionDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; SourceDatabaseDeletionDate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; SourceDatabaseDeletionDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.SourceDatabaseDeletionDate" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceDatabaseDeletionDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.SourceDatabaseDeletionDate : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.SourceDatabaseDeletionDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sourceDatabaseDeletionDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8ea8-260">取得または条件を設定します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-260">Gets or sets conditional.</span></span> <span data-ttu-id="f8ea8-261">CreateMode は復元 sourceDatabaseId は削除されたデータベースの元のリソース id ではなく、現在の復元可能な削除されたデータベース id) に存在していた場合は、この値が必要です。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-261">If createMode is Restore and sourceDatabaseId is the deleted database's original resource id when it existed (as opposed to its current restorable dropped database id), then this value is required.</span></span> <span data-ttu-id="f8ea8-262">データベースが削除された日時を指定します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-262">Specifies the time that the database was deleted.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceDatabaseId">
      <MemberSignature Language="C#" Value="public string SourceDatabaseId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceDatabaseId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.SourceDatabaseId" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceDatabaseId As String" />
      <MemberSignature Language="F#" Value="member this.SourceDatabaseId : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.SourceDatabaseId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sourceDatabaseId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8ea8-263">取得または条件を設定します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-263">Gets or sets conditional.</span></span> <span data-ttu-id="f8ea8-264">CreateMode がコピー、NonReadableSecondary、OnlineSecondary、PointInTimeRestore、復旧、または復元の場合は、この値が必要です。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-264">If createMode is Copy, NonReadableSecondary, OnlineSecondary, PointInTimeRestore, Recovery, or Restore, then this value is required.</span></span> <span data-ttu-id="f8ea8-265">ソース データベースのリソース ID を指定します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-265">Specifies the resource ID of the source database.</span></span> <span data-ttu-id="f8ea8-266">CreateMode が NonReadableSecondary または OnlineSecondary の場合は、ソース データベースの名前を作成する新しいデータベースと同じにする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-266">If createMode is NonReadableSecondary or OnlineSecondary, the name of the source database must be the same as the new database being created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public string Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As String" />
      <MemberSignature Language="F#" Value="member this.Status : string" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8ea8-267">データベースの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-267">Gets the status of the database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tags")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8ea8-268">取得またはリソース タグを設定します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-268">Gets or sets resource tags.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransparentDataEncryption">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt; TransparentDataEncryption { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt; TransparentDataEncryption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.TransparentDataEncryption" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TransparentDataEncryption As IList(Of TransparentDataEncryption)" />
      <MemberSignature Language="F#" Value="member this.TransparentDataEncryption : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt;" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.TransparentDataEncryption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.transparentDataEncryption")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8ea8-269">このデータベースの透過的なデータの暗号化情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-269">Gets the transparent data encryption info for this database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ZoneRedundant">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ZoneRedundant { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ZoneRedundant" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.ZoneRedundant" />
      <MemberSignature Language="VB.NET" Value="Public Property ZoneRedundant As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ZoneRedundant : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.ZoneRedundant" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.zoneRedundant")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8ea8-270">取得またはこのデータベースが複数の可用性ゾーン、ゾーン冗長、このデータベースのレプリカを意味に分散するかどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="f8ea8-270">Gets or sets whether or not this database is zone redundant, which means the replicas of this database will be spread across multiple availability zones.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>